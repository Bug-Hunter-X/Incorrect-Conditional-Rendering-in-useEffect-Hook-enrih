# Incorrect Conditional Rendering in useEffect Hook

This repository demonstrates a common error in React's `useEffect` hook where conditional logic can lead to unexpected behavior. The `MyComponent` component attempts to update the document title based on the `count` state. However, due to an incorrect condition, the title is only updated when `count` is greater than 0, leaving it unchanged when `count` is 0. This can be unexpected and lead to a poor user experience. The solution file provides a corrected implementation.

## How to reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe that the document title does not update when `count` is 0.