
# react-native-zxz-utils

## Getting started

`$ npm install react-native-zxz-utils --save`

### Mostly automatic installation

`$ react-native link react-native-zxz-utils`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-zxz-utils` and add `RNReactNativeZxzUtils.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNReactNativeZxzUtils.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNReactNativeZxzUtilsPackage;` to the imports at the top of the file
  - Add `new RNReactNativeZxzUtilsPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-zxz-utils'
  	project(':react-native-zxz-utils').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-zxz-utils/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-zxz-utils')
  	```

## Usage
```javascript
import RNReactNativeZxzUtils from 'react-native-zxz-utils';

// TODO: What do with the module?
RNReactNativeZxzUtils;
```
  