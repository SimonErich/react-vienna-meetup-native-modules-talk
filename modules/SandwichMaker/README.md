
# react-native-sandwich-maker

## Getting started

`$ npm install react-native-sandwich-maker --save`

### Mostly automatic installation

`$ react-native link react-native-sandwich-maker`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-sandwich-maker` and add `RNSandwichMaker.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNSandwichMaker.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNSandwichMakerPackage;` to the imports at the top of the file
  - Add `new RNSandwichMakerPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-sandwich-maker'
  	project(':react-native-sandwich-maker').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-sandwich-maker/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-sandwich-maker')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNSandwichMaker.sln` in `node_modules/react-native-sandwich-maker/windows/RNSandwichMaker.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Sandwich.Maker.RNSandwichMaker;` to the usings at the top of the file
  - Add `new RNSandwichMakerPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNSandwichMaker from 'react-native-sandwich-maker';

// TODO: What to do with the module?
RNSandwichMaker;
```
  