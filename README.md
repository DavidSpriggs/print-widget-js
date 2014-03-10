print-widget-js
===============

A print widget for the esri js api.

```javascript
var printWidget = new Print({
        map: map,
        printTaskURL: "https://utility.arcgisonline.com/arcgis/rest/services/Utilities/PrintingTools/GPServer/Export%20Web%20Map%20Task",
        authorText: "Dave",
        copyrightText: "2014",
        defaultTitle: "My Map",
        defaultFormat: "PDF",
        defaultLayout: null
    }, 'printDijit');
printWidget.startup();
```

Screen from Sample page:

![Screenshot](https://raw.github.com/DavidSpriggs/print-widget-js/master/screenshot.PNG)