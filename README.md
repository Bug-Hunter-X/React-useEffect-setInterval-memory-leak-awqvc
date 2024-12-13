# React useEffect setInterval Memory Leak
This example demonstrates a common error in React applications involving the `useEffect` hook and the `setInterval` function.  The problem arises from failing to properly clean up the interval when the component unmounts.  This results in a memory leak and potentially unexpected behavior.

The `bug.js` file shows the incorrect implementation. The `bugSolution.js` file provides the corrected version.