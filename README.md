# react-use-toggle

Basically, what this hook does is that, it takes a parameter with value true or false and toggles that value to opposite. It's useful when we want to take some action into it's opposite action, for example: show and hide modal, show more/show less text, open/close side menu.

**Usage**

```
function App() {
 // Call the hook which returns, current value and the toggler function

 const [isTextChanged, setIsTextChanged] = useToggle();

 return (
     <button onClick={setIsTextChanged}>{isTextChanged ? 'Toggled' : 'Click to Toggle'}</button>
 );
}
```
