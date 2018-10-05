# Membrane Multimedia Framework: H264 video format definition

[![Build Status](https://travis-ci.com/membraneframework/membrane-caps-video-h264.svg?branch=master)](https://travis-ci.com/membraneframework/membrane-caps-video-h264)

This package provides H264 video format definition (so-called caps) for the
[Membrane Multimedia Framework](https://membraneframework.org).

## Installation

Unless you're developing an Membrane Element it's unlikely that you need to
use this package directly in your app, as normally it is going to be fetched as
a dependency of any element that operates on H264 video stream.

However, if you are developing an Element or need to add it due to any other
reason, just add the following line to your `deps` in the `mix.exs` and run
`mix deps.get`.

```elixir
{:membrane_caps_video_h264, "~> 0.1"}
```
