# electron-is-dev

> Check if [Electron](http://electron.atom.io) is running in development

Useful for disable debug feature during production mode.

## Install

```
$ npm install --save electron-isDev
```


## Usage

```typescript
import {isDev} from "./isDev";

if (isDev) {
    // Development Mode
} else {
	// Production Mode
}
```


## Related

