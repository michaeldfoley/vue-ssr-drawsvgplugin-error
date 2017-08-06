# Vue SSR DrawSVGPlugin Error Example

> Illustrates the error that occurs when using the DrawSVGPlugin with vue-server-renderer.

## Setup

```
$ npm install
```

Add DrawSVGPlugin to `node_modules/gsap` from the npm GreenSock folder
```
npm run dev
```

You should get the following error:
```
Error: Unhandled "error" event. (TypeError: Cannot read property 'defaultView' of undefined)
```
