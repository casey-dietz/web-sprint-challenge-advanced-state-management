# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
In a typical React application, data is passed top-down via props, but this can be cumbersome for certain types of props that are required by many components within an application. Context provides a way to share values between components without having to explicitly pass a prop through every level of the tree.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

An action is an object that includes a string specifying the type of action to be performed, and any data needed by the reducer to properly update state.

Reducer takes an action and current state (both objects!) and returns the new state.

Store holds the state of your application.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

Redux Thunk is a middleware that lets you call action creators that return a function instead of an action object.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

Context because it was easier for me, and less steps. Redux has way too much typing and steps.