# HoldOn.js
Prevent that your user do something stupid when you need to. Lock the ui with 1 line of code.

# Guide
## Open
The open function will show an overlay in the screen and will prevent the user interaction with the background.
```HoldOn.open()```

Params:
* theme (string)	The id of the selected theme (default will be sk-rect)
* message (string)	The message that will be viewed by the user when the plugin is executed. HTML is allowed.
* backgroundColor (string)	HEX Color (#1847B1) Defines the background color of the overlay
* textColor (string)	HEX Color (#1847B1) Defines the text color of the overlay
* content (string)	The HTML content of the overlay. This option only will be used if your theme is "custom"

### Available themes
* sk-rect
* sk-bounce
* sk-folding-cube
* sk-circle
* sk-dot
* sk-bounce
* sk-falding-circle
* sk-cube-grid

## Close
```HoldOn.close()```