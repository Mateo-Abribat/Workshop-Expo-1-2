# Workshop-Expo-1-2

## Project setup

Before starting the project, set it up following the instructions in the [setup](./SETUP.md) section.

## Introduction

Expo is an open-source platform for developing and building native mobile applications for iOS and Android using JavaScript and React Native. It provides a unified development environment and a set of tools to streamline the mobile app development process, such as a simulator, debugging tools, and push notification services. With Expo, developers can focus on building the features and functionality of their app, rather than managing the underlying native infrastructure. Additionally, Expo has a large and growing community of developers, making it easy to find support and resources for building your app. This project is an introduction to Expo, where you will implement a basic screen with different components.

## First step

1. Play with different components in React Native:
   - Create a view with the text "Hello World".
   - Customize the view with a style (width, height, background, etc.).

## Second step

1. Create a text input with the native component `TextInput`.
2. Display the content of the text input in real time below it.
   - You can check the documentation of react native `TextInput` [here](https://reactnative.dev/docs/textinput).
   - Also try to play with `useEffect` function to see how it works: [useEffect](https://reactjs.org/docs/hooks-effect.html).

## Third step

1. Add a `Button` to submit the content of the `TextInput`.
2. Store the content of the `TextInput`.
3. Implement the functionality of the button so that it clears the text input after the content has been submitted.

## Fourth step

Now that you have stored the content of the `TextInput`,

1. Display the submitted content in a separate screen using the [`React Navigation`](https://reactnavigation.org/docs/getting-started/) library.
2. Add the ability to edit and delete the submitted content.
