# react-native-stretchy
A ReactNative scrollable stretchy header component


## Installation

You can install this package via `npm`:

```bash
npm install react-native-stretchy --save
```


## Usage

```js
import React, { Component } from 'react';
import { Text, View } from 'react-native';
import StretchyHeader from 'react-native-stretchy';

class MyStretchyHeader extends Component {
  render() {
    return (
      <StretchyHeader
          image={{uri: 'https://example.com/myImageAddress'}}
          title= 'My Stretchy Header Title'
          subtitle= 'Awesome Subtitle'
          gradientColors={["#000", "transparent", "#000"]}
          backgroundColor="#EFEFF4"
      >
          <Text>Foo</Text>
          <Text>Bar</Text>
      </StretchyHeader>
    );
  }
}
```


### Properties

* **image**: The image of the stretchy header ([RN image source](https://facebook.github.io/react-native/docs/images.html))
* **title**: The string title of stretchy header
* **subtitle**: The string subtitle of stretchy header
* **gradientColors**: The array of string colors for stretchy header gradient overlay
* **backgroundColor**: The background color of the inner content of the stretchy header


## Contribution

You can fork the repository, improve or fix some part of it and then send the pull requests back if you want to see them here. I really appreciate that. :wink:


## License

Licensed under the [MIT License](https://github.com/hamidhadi/react-native-stretchy/blob/master/LICENSE).
