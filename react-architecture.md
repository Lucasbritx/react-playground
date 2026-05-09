# React Architecture

## Hydration
![alt text](image.png)
### https://github.com/reactwg/react-18/discussions/37
### https://www.reddit.com/r/reactjs/comments/18fky3q/what_is_hydration_in_react/
Hydration is the process when, after the HTML be pre-rendered, we add interactivity with JS.



## Virtual Dom
![alt text](image-1.png)
VDOM is the react representation in memory of DOM, to minimize reflows and repaints,
when state or props changes, react creates a new VDOM to compare with the previous one(process called reconciliation).

### React Fiber
Instead of rendering all DOM updates together. React breaks it in small chunks, can be paused, resumed or prioritized.

## Reconciliation
Identifier the minimum of changes to update the real DOM.

### Why is fast? what let virtual dom slow?
Basically minimizes real DOM mutations
Uses diffing (reconciliation)

## Reconciliation (process inside virtual dom)

## What other frameworks do/use?

### Vue - virtual dom?
### Angular - virtual dom?
### Svelte - virtual dom?

## Examples in react codebase



