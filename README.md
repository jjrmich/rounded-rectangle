# @jjrmich/rounded-rectangle
This repository holds the rounded-rectangle component, which allows for react-native-svg to render rectangles with a rounded bottom.  
[![npm (scoped)](https://img.shields.io/npm/v/@jjrmich/rounded-rectangle)](https://github.com/jjrmich/rounded-rectangle/) [![npm bundle size (scoped version)](https://img.shields.io/bundlephobia/min/@jjrmich/rounded-rectangle/0.1.0)](https://github.com/jjrmich/rounded-rectangle/)
## Install
Run either  
```
yarn add @jjrmich/rounded-rectangle
```  
or  
```
npm install @jjrmich/rounded-rectangle
```  
to add this component to your project, depending on your preferred package manager.

### Peer Dependencies
Since this is a React Native component, [React Native](https://facebook.github.io/react-native/docs/getting-started) needs to be installed in order for this to work. In addition, this component is created for [react-native-svg](https://github.com/react-native-community/react-native-svg), which also needs to be added to the project.

## Usage
To use this component, use the 
```
import Svg from 'react-native-svg';
import {RoundedRect} from '@jjrmich/rounded-rectangle';
```  
import statements. Then, utilize the `RoundedRect` component the same way you would use any of [react-native-svg](https://github.com/react-native-community/react-native-svg)'s various shapes. For example,  
```
<View>
  <Svg width="100%" height="100%">
    <RoundedRect
      x=120
      y=120
      height=200
      width=200
      curve=30
      fill='orange'
    />
  </Svg>
</View>
```
would be a valid input.
### Props
The component takes the following props  
  
| Name        | Default       | Description |  
|-------------|---------------|-------------|  
| x           | 0             |             |  
| y           | 0             |             |  
| height      | 10            |             |  
| width       | 10            |             |  
| height      | 10            |             |  
| curve       | 10            |             |  
| stroke      | `transparent` |             |  
| fill        | `transparent` |             |  
| strokeWidth | 0             |             |  
