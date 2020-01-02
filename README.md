# Chore App

## Development

You need to install the following tools:

- [Node.js 12.14.0+ (LTS)](https://nodejs.org/en/)
- [Yarn package manager](https://yarnpkg.com/lang/en/docs/install/#alternatives-stable)
- [JDK 8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Android Studio](https://developer.android.com/studio/)

If developing the frontend application, follow the **Android development environment** [instructions](https://facebook.github.io/react-native/docs/getting-started) under "React Native CLI Quickstart" > "Linux" > "Android". You should only have to do #1 and #3.

Make sure to accept the Android SDK licenses by running:

```
~ $ sdkmanager --licenses
```

### Setup the development environment

```
~ $ cd app && yarn && cd ..
~ $ cd backend && yarn && cd ..
```

### Make sure tests pass

```
~ $ cd app && yarn test && cd ..
~ $ cd backend && yarn test && yarn build && cd ..
```

### Frontend development

In one terminal, run:

```
~/app $ yarn start
```

In another, run:

```
~/app $ yarn android
```

You should now see the app loaded in the Android emulator. Verify that making a change in the source code works.

### Backend development

```
~/backend $ yarn dev
```
