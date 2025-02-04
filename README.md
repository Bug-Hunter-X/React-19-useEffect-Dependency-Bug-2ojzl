# React 19 useEffect Bug

This repository demonstrates an uncommon bug in React 19 related to the `useEffect` hook and its dependency array.  The bug showcases how an incorrect or missing dependency array can lead to unexpected behavior.

## Bug Description
The `useEffect` hook is used incorrectly, causing it to execute more frequently than expected. This leads to an infinite render loop in this specific example, or unexpected behavior in other cases.

## Reproduction
1. Clone the repository
2. Run `npm install`
3. Run `npm start`
4. Observe the console for infinite logs (or other unexpected behavior in altered versions)

## Solution
The solution involves correctly specifying the dependency array in the `useEffect` hook.  This ensures the effect runs only when the specified dependencies change. 
