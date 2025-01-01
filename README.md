# React Native useRef Callback Error After Component Unmount

This repository demonstrates a common error encountered when using the `useRef` hook in React Native. The issue arises when a callback function within `useRef` attempts to access or modify the DOM (or similar) after the component has unmounted, leading to a warning or error.  The example showcases the problem and provides a solution using a cleanup function.

## Setup

1. Clone the repository.
2. Navigate to the directory.
3. Run `npm install`.
4. Run `npx react-native run-android` (or equivalent for iOS).