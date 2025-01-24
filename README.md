# React useEffect Hook Missing Dependency

This example demonstrates a common error in React's `useEffect` hook: omitting a dependency that's used within the effect. This often leads to unexpected re-renders or even infinite loops. The `setCount` function, which modifies state, is a key dependency that is missing from the `useEffect` call.  The solution shows how to fix this by adding `setCount` to the dependency array to properly manage the effect's execution.