# react-native-web-svg

This package was written to be used as a [react-native-web](https://github.com/necolas/react-native-web) implementation of [react-native-svg](https://github.com/react-native-community/react-native-svg) library.

### Usage with [webpack](https://github.com/webpack/webpack)

```javascript
module.exports = {
  /* All of yours webpack config */
  resolve: {
    // ...
    alias: {
      // ...
      'react-native$': 'react-native-web',
      'react-native-svg$': 'react-native-web-svg',
    },
  },
};
```

Thats it!
