# Class 41

Three Core Components of React Native

- View

Acts as a container for other components and views. It is analogous to a <div> in web development.

- Text

Used to display text. It supports nesting, styling, and touch handling, similar to a <p> or <span> tag in web development.

- Image

Used to display images. It supports different image formats and can handle image resizing and styling.

What Problem Does React Native Solve?

- React Native allows developers to build mobile apps using JavaScript and React. It solves the problem of having to write separate codebases for iOS and Android by enabling code reuse and sharing between platforms, hence the name "native" as it provides a near-native performance and user experience.

Building Blocks of a React Native App vs. a React App

- React Native App:

Uses components like View, Text, and Image.
These components map to native UI components on iOS and Android.

- React App:

Uses HTML elements like <div>, <span>, and <img>.
These elements are rendered in a web browser.

Solution Provided by Expo

- Expo provides a set of tools and services built around React Native, simplifying the development process. It handles many complexities of building and deploying React Native apps.

- Managed workflow: Expo takes care of much of the configuration and setup, allowing developers to focus on writing their application code.

Difference Between React Native and Expo

- React Native: A framework for building native apps using React.
- Expo: A platform and a set of tools built on top of React Native that simplifies the development process by managing configurations and providing additional APIs and services.

What Snack Allows You to Do

- Snack is an online editor provided by Expo that allows you to write, run, and share React Native code directly in your browser. It provides an easy way to prototype and experiment with React Native apps without setting up a local development environment.

What Does “Eject” Mean Within the Context of Expo?

"Ejecting" refers to transitioning from the managed Expo workflow to a bare workflow. This gives you full control over your project configuration, allowing you to add custom native code or use unsupported libraries.

When Should You Not Eject?

- When you do not need to use custom native modules or libraries that are not supported by Expo.
If you want to keep benefiting from Expo's managed workflow and easy updates.

Why Might You Choose to Eject?

- To use custom native modules or third-party libraries that require native code changes.
- To have full control over the native code and configurations of your app.
