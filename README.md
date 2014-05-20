# JSCapture

Records your screen with pure JavaScript.

## API

* `JSCapture.capture(config)` - Captures a new screenshot.
  * `config.x` - (Number) default value `0`. Specifies the left offset.
  * `config.y` - (Number) default value `0`. Specifies the top offset.
  * `config.width` - (Number) default value the screen width. Specifies the width of the screenshot.
  * `config.height` - (Number) default value the screen height. Specifies the height of the screenshot.
  * `config.process` - (Function|Array) default value an empty array. A list of filters, which are going to process the image.
  * `config.blackWhite` - (Boolean) default value `false`. Specifies whether we want to apply filter, which will make the image black and white.
  * `config.done` - (Function) default value is `undefined`. Callback, which is being called with the captured image.
  * `config.delay` - (Number) default value `0`. Specifies the delay after each the screenshot will be captured.
* `JSCapture.record(config)` - Capture a video.
  * `config.x` - (Number) default value `0`. Specifies the left offset.
  * `config.y` - (Number) default value `0`. Specifies the top offset.
  * `config.width` - (Number) default value the screen width. Specifies the width of the video.
  * `config.height` - (Number) default value the screen height. Specifies the height of the video.
  * `config.process` - (Function|Array) default value an empty array. A list of filters, which are going to process the individual frames.
  * `config.blackWhite` - (Boolean) default value `false`. Specifies whether we want to apply filter, which will make the video black and white.
  * `config.done` - (Function) default value is `undefined`. Callback, which is being called with the captured video.
  * `config.delay` - (Number) default value `0`. Specifies the delay after each the video will be captured.
  * `config.frameRate` - (Number) default value `60` frames per second. Specifies the number of frames per second.
  * `config.done` - function, which accepts the video as argument
* `JSCapture.stopRecording()` - Stops the video recording.

## Author

[![mgechev](http://www.gravatar.com/avatar/82bafb0432ce4ccc9dcc26f94d5fe5bc?s=117)](https://github.com/mgechev)

## License

This software is distributed under the terms of the MIT license.
