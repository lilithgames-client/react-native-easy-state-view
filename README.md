# <img alt="React Native Easy State View" src="https://github.com/WrathChaos/react-native-easy-state-view/blob/master/assets/Screenshots/logo.png" width="1050"/>

[![Battle Tested ✅](https://img.shields.io/badge/-Battle--Tested%20%E2%9C%85-03666e?style=for-the-badge)](https://github.com/WrathChaos/react-native-button)

[![Fully customizable State View with plug & play usage for React Native.](https://img.shields.io/badge/-Fully%20customizable%20State%20View%20with%20plug%20%26%20play%20usage%20for%20React%20Native.-lightgrey?style=for-the-badge)](https://github.com/WrathChaos/react-native-easy-state-view)

[![npm version](https://img.shields.io/npm/v/react-native-easy-state-view.svg?style=for-the-badge)](https://www.npmjs.com/package/react-native-easy-state-view)
[![npm](https://img.shields.io/npm/dt/react-native-easy-state-view.svg?style=for-the-badge)](https://www.npmjs.com/package/react-native-easy-state-view)
![Platform - Android and iOS](https://img.shields.io/badge/platform-Android%20%7C%20iOS-blue.svg?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

<p align="center">
<img alt="React Native Easy State View Image" src="assets/Screenshots/example.png" width="49.7%" height="820"/>
<img alt="React Native Easy State View Image" src="assets/Screenshots/example4.png" width="49.7%" height="820"/>
</p>

<p align="center">
<img alt="React Native Easy State View Image" src="assets/Screenshots/example3.png" width="49.7%" height="820"/>
<img alt="React Native Easy State View Image" src="assets/Screenshots/example2.png" width="49.7%" height="820"/>
</p>

## Installation

Add the dependency:

```ruby
npm i react-native-easy-state-view
```

## Peer Dependencies

##### IMPORTANT! You need install them.

```js
"react-native-material-ripple": ">= 0.8.0"
```

## Basic Usage

```jsx
<StateView
  isCenter
  enableButton
  style={{ top: "40%" }}
  title="No Favorites Yet!"
  imageSource={require("./assets/your-image")}
  subtitle="There is no favorites but here are some gifts from santa :)"
/>
```

### Example Application

- I shared the example project to check what it is:
  [check the code](examples/App.js), and yes! :) all of the images, screenshots are directly taken
  from this example. Of course, you can simply clone the project and run the example on your own environment.

### Configuration - Props

| Property                    | Type      | Default                | Description                                                  |
| --------------------------- | --------- | ---------------------- | ------------------------------------------------------------ |
| style                       | style     | { top: 0 }             | use this to implement your own style for whole StateView.    |
| title                       | string    | " "                    | use this to write your title                                 |
| titleStyle                  | style     | check the source code  | use this to change your title's style                        |
| onPress                     | function  | undefined              | use this to handle the press the button                      |
| subtitle                    | string    | " "                    | use this to change your subtitle's style                     |
| subtitleStyle               | style     | check the source code  | use this to change your subtitle's style                     |
| isCenter                    | boolean   | false                  | use this to center the StateView's content (recommended)     |
| imageStyle                  | style     | check the source code  | use this to change your own image STyle                      |
| imageResizeMode             | string    | "contain"              | use this to change your image's resize mode                  |
| imageSource                 | image     | Cutie Snow Globe Image | use this to set your own image source                        |
| enableButton                | boolean   | false                  | set the enableButton to use the button                       |
| buttonComponent             | component | default ripple button  | use this to implement your own button                        |
| rippleColor                 | color     | "white"                | use this to change ripple color                              |
| rippleDuration              | int       | 750                    | use this to set ripple duration                              |
| rippleContainerBorderRadius | int       | 16                     | use this to change ripple's border radius                    |
| buttonContainerStyle        | style     | check the source code  | use this to implement your own style for button container    |
| buttonColor                 | color     | "#FFAF10"              | use this to change button's container color                  |
| buttonTextStyle             | style     | check the source code  | use this to implement your own style for button's text style |
| buttonTextColor             | color     | "white"                | use this to change button's text color                       |
| buttonText                  | string    | "Let's Go!"            | use this to set your button's text                           |
| shadowColor                 | color     | "#000"                 | use this to change button's shadow color                     |
| shadowStyle                 | style     | \_shadowStyle          | use this to set your own shadow style                        |

## Credits

Thanks for Kaylylai for these awesome illustrations :O I love her work a lot!
Here is the Kaylylai's Dribbble portfolio : [Kaylylai's Dribble](https://dribbble.com/kaylylai)

## Author

FreakyCoder, kurayogun@gmail.com

## License

React Native Easy State View Library is available under the MIT license. See the LICENSE file for more info.
