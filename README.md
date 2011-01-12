Super Slider
============

A super little HTML slider widget designed for accurate control of values.  
Compatible with [jQuery](http://jquery.com/) or [Zepto.js](http://zeptojs.com/) frameworks.

Instructions
------------
Super slider allows fine control of setting values by providing keyboard input to adjust the values in small increments as well as alt and shift key modifiers when dragging with the mouse.

 * Normal dragging will change the value based on the step parameter.
 * ALT + drag will change by 0.1x the step parameter.
 * The up and down arrow keys will change the value when the mouse is over the slider widget.
 * SHIFT + arrows will change by 10x the step factor.
 * ALT + arrows will change by 0.1x the step factor.
 * Clicking the label will reset to the default value.

**Usage:**

    var slider = new SuperSlider(slider_id [, options])

**Options:**

    var options = {
      slider_class   : 'ss_slider', // slider class name
      track_class    : 'ss_track',  // track class name
      handle_class   : 'ss_handle', // handle class name
      input_class    : 'ss_input',  // input class name
      label_class    : 'ss_label',  // label class name
      min            : 0,           // minimum value
      max            : 1,           // maximum value
      step           : 0.01,        // step increment
      default_value  : 0.5,         // default value
      decimal_places : 3,           // decimal place rounding
      label          : null,        // label
      name           : null         // input name attribute
    };

**Compatibility**

Tested on Safari 5, Chrome 9, Firefox 3.6+ on Max OS X.

**About**

Created by [Tom Beddard](http://www.subblue.com).  
Released under the [MIT license](http://www.opensource.org/licenses/mit-license.php).