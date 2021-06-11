# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

Context API makes data accessible globally instead of requiring you to pass props to each individial component. The trade-off is components made with this context API are significantly less reusable.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Actions are objects that get returned by action functions, they are then passed to our reducers to enact those 'actions'. The 'store' is known as a 'single source of truth' in our redux application because it can hold _all_ of your applications' state.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

Redux-thunk allows for us to create action-creators that run asynchronously, which is very useful for asynchronous functions like web requests, axios, and fetches.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

I love basic react/redux without thunks. I think that having application managed this way, and being able to see it all with my redux-logger, makes things a lot easier to understand what's being done in my application.