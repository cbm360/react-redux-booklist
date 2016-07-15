# React Redux Booklist

## What I Learned
- Redux- is in charge of managing application state, this is completely different that component state.
- Reducers- function that returns a piece of the application state, reducers get tied together using combineReducers in reducer_index.
- Containers/Smart Components- components that has direct access to state produce by Redux.
- Use Redux connect in a container to connect React and Redux.
- Action Creator- every action flows through all reducers and has the option to return a different piece of state.
- Need to set a defualt state to avoid errors- React will send actions through the reducers
on page load, so a default state or conditional is needed to handle null state and prevent errors.



## Resources
Udemy- [Modern React with Redux](https://www.udemy.com/react-redux/learn/v4/overview)

