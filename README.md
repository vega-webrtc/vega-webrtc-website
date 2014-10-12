# Vega WebRTC Website

This is the source for [vega-webrtc.github.io](http://vega-webrtc.github.io).

It's built with [Middleman](http://middlemanapp.com/).

The built source for the deployed site is
[here](https://github.com/vega-webrtc/vega-webrtc.github.io).

## Deploy

```sh
$ middleman deploy --build-before
```

### Deploying for the first time

Add the `build` remote:

```sh
$ git remote add build git@github.com:vega-webrtc/vega-webrtc.github.io.git
```

Then after you deploy:

```sh
$ cd build && git remote add build git@github.com:vega-webrtc/vega-webrtc.github.io.git
```
