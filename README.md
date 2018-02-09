# Click-Thru Prototype

A Sketch plugin that creates a HTML click-through prototype of a website design so you can give your clients an idea what the website will look like. [Here's an example of a website](https://markhorgan.github.io/click-thru-prototype) generated by the plugin. Change the width of the browser to see the different responsive designs.

I've forked this repo - it's not actively maintained.  Works with Sketch 44.1 (check this).

Ideas for expansion:
* add placeholder element that allows scripts to run inpage
* add placeholder element that allows iframes

<img src="https://cloud.githubusercontent.com/assets/1472553/23585953/db0ff3f0-0182-11e7-8125-40abdfa17ee9.gif" alt="Screencast">

## Installation

To install, [download the zip file](https://github.com/markhorgan/click-thru-prototype/archive/master.zip) and double-click on `Click-Thru-Prototype.sketchplugin`. The commands will show up under `Plugins > Click-Thru Prototype`. To see it in action, open `demo.sketch` and then select `Plugins > Click-Thru Prototype > Export to HTML`.

## Usage

You can create links between artboards, add external links or show a JavaScript dialog. When you're finished adding these you can generate a HTML website of the current page by selecting `Export to HTML`. The generated files can then be uploaded to a server so you can show your client. 
 
### Responsive Design 
 
The plugin can handle responsive design, you just need to start your artboards with the same name e.g. `index`, `index tablet`, `index mobile`. When you change the width of your browser it will show a different artboard in the exported website. You can turn this feature off by unchecking `Responsive artboards` in Settings. You may need to update your artboard links after turning this setting on or off. 
 
<img src="https://cloud.githubusercontent.com/assets/1472553/23585670/f88e9c1c-017b-11e7-98c2-f8d70c6e58fa.png" alt="Responsive artboards">

### Mobile Menu

On mobile you will want to show a mobile menu rather than the normal horizontal menu. To do this you need to select which layer is the button that shows the menu by selecting `Set Mobile Menu Button`, and which layer is the mobile menu by selecting `Set Mobile Menu`.
 
<img src="https://cloud.githubusercontent.com/assets/1472553/23585671/fa923e74-017b-11e7-8f79-a242df8cd12e.png" alt="Mobile menu">

### Retina Images
 
By default it will show 2x images for high pixel density screens. To turn this off uncheck `Export retina images` in Settings and re-export the page.