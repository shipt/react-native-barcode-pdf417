# react-native-barcode-pdf417

React native component for pdf417 barcode. This module is based on https://github.com/bkuzmic/pdf417-js.

![screen shot 2017-06-19 at 2 52 59 pm](https://user-images.githubusercontent.com/902357/27300810-09ec0efa-54ff-11e7-971b-fef49851525f.png)

### Pre install:

Uses React Native SVG

### Install:

```
npm install --save react-native-barcode-pdf417 react-native-svg
```

### Link native code:

```
cd ios && pod install
```

### Usage:

```js
import Barcode from "react-native-barcode-pdf417";
//...
<Barcode text="123124123" width={250} height={100} />
```

LICENSE: MIT
