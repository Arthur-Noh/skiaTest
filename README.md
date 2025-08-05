This is a test project for `@shopfiy/react-native-skia@2.2.0`.

## Environment

```
react-native@0.79.5
@shopify/react-native-skia@2.2.0

yarn@4.9.2

disable newArch
```

## Start (with installation)

Just 4 steps.

```
> npx @react-native-community/cli@latest init skiaTest --version 0.79.5

# disable new arch
# android/gradle.properties

> yarn add @shopify/react-native-skia

# add proguard rule
# android/app/proguard-rules.pro

# start metro
> yarn start

# start android
> yarn android start
```

## Result

```
FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':shopify_react-native-skia:compileDebugJavaWithJavac'.
> Compilation failed; see the compiler output below.
  /Users/arthurnoh/workspace/skiaTest/node_modules/@shopify/react-native-skia/android/src/main/java/com/shopify/reactnative/skia/SkiaPictureViewManager.java:35: error: method does not override or implement a method from a supertype
      @Override
      ^
  Note: Some input files use or override a deprecated API.
  Note: Recompile with -Xlint:deprecation for details.
  Note: Some input files use unchecked or unsafe operations.
  Note: Recompile with -Xlint:unchecked for details.
  1 error

* Try:
> Check your code and dependencies to fix the compilation error(s)
> Run with --scan to get full insights.
```
