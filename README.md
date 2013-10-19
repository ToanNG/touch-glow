Touch Glow
==========

A jQuery plugin that provides visual feedback on mouse/touch actions. Try clicking on this panel.

# Usage

Include jQuery and Touch Glow script files in your project.

You can initialize the script in the following ways:

```javascript
$(selector).touchglow();
```
```javascript
$(selector).touchglow({
      touchBlurRadius: 30,
      touchSpread: 20
});
```
NOTE: Touch Glow options are set globally. Any subsequent settings will override the previous. To set style, simply call touch glow with options after it's been initialized:

```javascript
$.touchglow({
    touchBlurRadius: 30,
    touchSpread: 20
});
```

However, it is recommended that all the options set at the time of initilization.

# Options

All parameters are optional. Default values are shown rightmost.

| Options        | Description |
| -------------- | ----------- |
| touchName [string] | ID attribute of the touch div 'jquery-touch-glow' |
| touchBlurRadius [pixels] | The blur distance 60 |
| touchSpread [pixels] | Size of the touch glow 30 |
| touchOffsetX [pixels] | Horizontal offset from the mouse/touch position 0 |
| touchOffsetY [pixels] | Vertical offset from the mouse/touch position 0 |
| touchColor [color] | Color of the touch glow 'blueviolet' |
| innerWidth [pixels] | Solid inner width of the touch glow 0 |
| fadeInDuration [miliseconds] | Duration of the fade in animation 100 |
| fadeOutDuration [miliseconds] | Duration of the fade out animation 300 |
| afterFadeOut (element) [function] | Callback function to execute after the glow fades out |
