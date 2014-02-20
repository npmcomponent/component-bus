*This repository is a mirror of the [component](http://component.io) module [component/bus](http://github.com/component/bus). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-bus`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# Bus

  Application-wide event bus component (a Singleton `Emitter`).

## Installation

```
$ npm install bus
```

## API
  
```js
var bus = require('bus');
bus.emit('stuff');
```