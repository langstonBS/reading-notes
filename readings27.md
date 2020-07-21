## Snapshot Testing 
- to see major chages 

## state 
- tracks changes
- can be anything 
- ubdater
- READING NOTES
- Update to a component state should be done using setState()
- You can pass an object or a function to setState()
- Pass a function when you can to update state multiple times
- Do not depend on this.state immediately after calling setState() and make use of the updater function instead.

## Reconciliation
- render()
- The algorithm will not try to match subtrees of different component types. If you see yourself alternating between two component types with very similar output, you may want to make it the same type. In practice, we haven’t found this to be an issue.
- Keys should be stable, predictable, and unique. Unstable keys (like those produced by Math.random()) will cause many component instances and DOM nodes to be unnecessarily recreated, which can cause performance degradation and lost state in child components.