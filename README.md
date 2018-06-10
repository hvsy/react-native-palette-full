
# react-native-palette

## Getting started

`$ npm install react-native-palette --save`

### Mostly automatic installation

`$ react-native link react-native-palette`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-palette` and add `RNPalette.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNPalette.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import me.jerson.mobile.palette.RNPalettePackage;` to the imports at the top of the file
  - Add `new RNPalettePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-palette'
  	project(':react-native-palette').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-palette/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-palette')
  	```


## Usage
```javascript
import RNPalette from 'react-native-palette';

// TODO: What to do with the module?
RNPalette;
```
  