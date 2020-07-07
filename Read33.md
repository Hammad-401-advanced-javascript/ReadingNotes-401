## Context

##### Context provides a way to pass data through the component tree without having to pass props down manually at every level.
**In a typical React application, data is passed top-down (parent to child) via props, but this can be cumbersome for certain types of props
(e.g. locale preference, UI theme) that are required by many components within an application. Context provides a way to share values like
these between components without having to explicitly pass a prop through every level of the tree.**

**If you only want to avoid passing some props through many levels, component composition is often a simpler solution than context.**

**React.createContext: When React renders a component that subscribes to this Context object it will read the current context value from the closest 
matching Provider above it in the tree.**

![image](https://cmichel.io/you-might-not-need-react-context/react-context-vs-hoc.png)
