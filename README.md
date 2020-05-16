# React Native Sonos client

## Installation

```
yarn add https://github.com/ainar/react-native-sonos.git buffer events lodash react-native-network-info react-native-ssdp react-native-udp stream timers xml2js
```

## Usage

### Play a file

```js
import { Sonos } from 'react-native-sonos'

// Create Sonos object
sonos = Sonos("HOST", "PORT");
// Play music
sonos.play("music URI");
```

### Discover devices

```js
import { search } from 'react-native-sonos'

// show devices in console
search(null, console.log);
```
