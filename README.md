# Expo Invariant Violation Bug
This repository demonstrates a common bug encountered in Expo projects when using SafeAreaView: `Invariant Violation: requireNativeComponent: "RCTSafeAreaView" was not found in the UIManager`.

## Issue Description
The error occurs because the `SafeAreaView` component might not be correctly linked or configured within the Expo environment. This often happens due to issues with the Expo SDK version, dependencies, or incorrect usage.

## Reproduction
1. Clone this repository.
2. Install the dependencies using `npm install` or `yarn install`.
3. Run the project using `expo start`.
4. Observe the error message in the console.