# Vega WebRTC Website

This is the source for [vega-webrtc.github.io](http://vega-webrtc.github.io).

It's built with [Middleman](http://middlemanapp.com/).

The built source for the deployed site is
[here](https://github.com/vega-webrtc/vega-webrtc.github.io).

## Developing

Don't have [foreman](https://github.com/ddollar/foreman)?

```sh
$ gem install foreman
```

Run the server and watch sass:

```sh
$ foreman start
```

Source is in /source.

Thanks!

## Deploy

```sh
$ bin/deploy
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
