Super Theme Switcher is a jQuery plugin based on the original jQuery theme switcher that is no longer hosted or supported by the jQuery UI project.

### Example:
    $('#switcher').themeswitcher({
        imgpath: "images/",
    	loadTheme: "dot-luv"
    });

But since all parameters are optional you can just use it like this:
    $('#switcher').themeswitcher();
    
### Options
 
 * **imgPath**: String, path to image directory where theme icons are located
 * **rounded**: Boolean, rounded corners on themeswitcher link and dropdown
 * **themes**: An array of theme objects that will override the default themes.  
 [{title:"My theme",name:"my-theme",icon:"my-icon.png",url:"http://url-to-my-css-file.css"}]
 * **additionalThemes**: An array of theme objects that will be INCLUDED along with the default themes.  
 [{title:"My theme",name:"my-theme",icon:"my-icon.png",url:"http://url-to-my-css-file.css"}]
 * **jqueryUiVersion**: String, jQuery UI version of themes (Default themes are linked from Google CDN)
 * **themePath**: String, Base path to where the jQuery UI CSS themes are located (Default is Google CDN)
 * **onselect**: Callback receives the theme name and the theme url upon refreshing the css with the new theme

### Extras

http://preview3.visisoft.de/theme-switcher/themeroller.png

 * **Download Link**: Using the `onselect` callback the Demo shows how to assemble the download link to the themed jQueryUI zip archive.
 * **Link to ThemeRoller**: In the same way a link to the ThemeRoller App is generated where the selected theme can be edited and downloaded.

Demo located [here](http://preview3.visisoft.de/theme-switcher/sample.htm).

This plugin includes the awesome jQuery cookie plugin by Klaus Hartl found [here](https://github.com/carhartl/jquery-cookie)

Contact
----
seemann@visisoft.de