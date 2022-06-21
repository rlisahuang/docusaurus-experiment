---
sidebar_label: 'Hi!'
sidebar_position: 3
---

# Hello
<!-- the h1 header also corresponds to the default sidebar label -->

### Some Z3 input code using the SMT-LIB 2.0 format.
NOTE: we might want to request the Z3 syntax highlighting from prism.js.

```lisp
(echo "starting Z3...")
(declare-const a Int)
(declare-fun f (Int Bool) Int)
```

Below is some code snippet taken from the tutorial that executes the code live.
```jsx live title="src/components/blaj.js"
// you can edit it live
// QUESTION: where is the below function ever called? really confusing
function rip() {
    return (
        <h1>Hello, Oops!</h1>
    )
}
```

### The creation of a React component taken from the tutorial.
export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '20px',
      color: '#fff',
      padding: '10px',
      cursor: 'pointer',
    }}
    onClick={() => {
      alert(`You clicked the color ${color} with label ${children}`)
    }}>
    {children}
  </span>
);

This is <Highlight color="#25c2a0">Docusaurus green</Highlight> !

This is <Highlight color="#1877F2">Facebook blue</Highlight> !

### My WIP experiment with creating a MDX codeblock + a button + an area that renders the execution of the code.

**References**
- Tutorial?: https://ped.ro/writing/code-blocks-but-better
- Use React Code Blocks? Need to install react-code-block
    - See demo https://codesandbox.io/s/react-code-blocks-xgjrr?fontsize=14&file=/src/index.js:75-131