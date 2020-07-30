# contex

- Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. 
- For example, in the code below we manually thread through a “theme” prop in order to style the Button component:

### API
- React.createContext
- Creates a Context object. When React renders a component that subscribes to this Context object it will read the current context value from the closest matching Provider above it in the tree.
### Dynamic Context
- react matreal ui