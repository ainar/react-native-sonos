# React Native Sonos client

## Installation

```
yarn add https://github.com/ainar/react-native-sonos.git buffer events lodash react-native-network-info react-native-sonos react-native-ssdp react-native-udp stream timers xml2js
```

## Usage

```js

import { Sonos } from 'react-native-sonos'

// Create Sonos object
sonos = Sonos("HOST", "PORT");
// Play music
sonos.play("music URI");
```
