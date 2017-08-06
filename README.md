# Vue SSR DrawSVGPlugin Error Example

> Illustrates the error that occurs when using the DrawSVGPlugin with vue-server-renderer.

## Setup

```
$ npm install
```

Add the DrawSVGPlugin from the GreenSock `bonus-files-for-npm-users` folder to `node_modules/gsap`
```
npm run dev
```

You should get the following error:
```
Error: Unhandled "error" event. (TypeError: Cannot read property 'defaultView' of undefined)
```
