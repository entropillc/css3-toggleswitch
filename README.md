CSS3 Toggle Switch
==================

CSS3 Toggle Switch is a 100% pure CSS solution for styling checkbox inputs to look like toggle switches typically seen on mobile devices.

Usage
-----

Simply drop the CSS onto any page:

``` html
<link rel="stylesheet" type="text/css" href="toggleswitch.css"/>
```

To style a checkbox input, wrap it with the following HTML:

``` html
<label class="toggleswitch" onclick> <!-- The onclick attribute is required by iOS -->
  <input type="checkbox"/> <!-- Replace this with the checkbox you want to style -->
  <span class="toggleswitch-inner">
    <span class="toggleswitch-on">On</span> <!-- The checked state: On, Yes, etc. -->
    <span class="toggleswitch-off">Off</span> <!-- The unchecked state: Off, No, etc. -->
    <span class="toggleswitch-handle"></span>
  </span>
</label>
```

License
---------------------

Copyright 2011 Entropi Software, LLC.

Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0
