# Custom Firefox theme

Adapted from [minimal-functional-fox](https://github.com/mut-ex/minimal-functional-fox)

Includes the following:

- [Compact extensions menu](https://github.com/datguypiko/Firefox-Mod-Blur/blob/master/EXTRA%20MODS/Compact%20extensions%20menu) by [datguypiko](github.com/datguypiko)
- [Right side MacOS min/max/close control buttons](https://github.com/datguypiko/Firefox-Mod-Blur/blob/master/EXTRA%20MODS/Min-max-close%20control%20buttons/Right%20side%20MacOS%20style%20buttons/min-max-close_buttons.css) by [datguypiko](github.com/datguypiko)

# ENABLING CSS CONFIGURATION
In ```about:config```, set ```toolkit.legacyUserProfileCustomizations.stylesheets``` to true

Windows: 
* Go to %APPDATA%\Mozilla\Firefox\Profiles\[yourprofile] (usually the topmost folder)
* Create a folder called chrome    
* ```git clone https://github.com/gmarsanich/firefoxcfg/```
* Place the contents of the folder into the chrome folder
* Restart Firefox if it's running
* ???
* profit

Linux/macOS:
* no idea, glhf


# THIN SCROLLBAR
in ```about:config```

Scrollbar style: ```widget.non-native-theme.scrollbar.style = 5```

The full list of available styles is:
* 0: Default Platform scrollbar style
* 1: macOs scrollbars
* 2: GTK Scrollbars
* 3: Android Scrollbars
* 4: Windows 10 scrollbars
* 5: Windows 11 scrollbars

Thin effect: ```widget.non-native-theme.win11.scrollbar.force-overlay-style = true```

Overlay scrollbar: ```ui.useOverlayScrollbars = 1```


# THEMES AND COMPONENTS
* [Theme](https://color.firefox.com/?theme=XQAAAAK7AQAAAAAAAABBKYhm849SCia9U4KEGccwS-xMDPr1qJSUaaq-qy5QgqeHG4K15QeC1qYkmgg2gaV51vfSMQphK2NQNG8ROqrpOCy9T52GB_kD69d6C9EpJkF8yZDENT9zED_lDm7GN5RvqkLWI8VLLAA2qZ-KViqNsOa-GnzFzKmrD69uz1_H5HOBANbLG7PQ9HDT1iw3fEefF60buGT_89VMML_N0YLosi5q3WR7FzpG4zUR8BywiW9MW-EsStRT4f6SVNA90pq-O29IV7rSqkaTran_akbVQxjw4tdH_ApzuiqDRwuQX9n_2uWkaQ)

* [Theme generator](https://www.color.firefox.com)

* [Theme map](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/theme/themes_components_annotations.png)

* [Iosevka font](https://github.com/be5invis/Iosevka/)
