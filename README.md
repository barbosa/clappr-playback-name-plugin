# Clappr Playback's Name Plugin

[![Join the chat at https://gitter.im/clappr/clappr-playback-name-plugin](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/clappr/clappr-playback-name-plugin?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

<img src="https://raw.githubusercontent.com/barbosa/clappr-playback-name-plugin/master/screenshot.png"/>

## Usage

Add both Clappr and Playback's Name plugin scripts to your HTML:

```html
<head>
  <script type="text/javascript" src="http://cdn.clappr.io/latest/clappr.min.js"></script>
  <script type="text/javascript" src="dist/playbackname.js"></script>
</head>
```

Then just add `PlaybackName` into the list of plugins of your player instance:

```javascript
var player = new Clappr.Player({
  source: "http://your.video/here.mp4",
  plugins: {
    'container': [PlaybackName]
  }
});
```

*Note: There is a minified version served through CDNs too:*
```html
<script type="text/javascript" 
        src="//cdn.jsdelivr.net/clappr.playback-name/latest/playbackname.min.js"></script>
```
