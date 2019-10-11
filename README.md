# awesome_wm_simple_widgets
Very simple interactive widgets for awesome wm.  
![screenshot](/misc/screenshot.png)  
Usage:  
&ensp;&ensp;&ensp;&ensp;Copy desired widget directory to ~/.config/awesome  
&ensp;&ensp;&ensp;&ensp;Add to your rc.lua:  
```lua
        ...
        -- Short tip about the widget
        local %widgetname% = require("%widgetname%")
        local my%widgetname% = %widgetname%()
        ...
```
&ensp;&ensp;&ensp;&ensp;Then inscribe 'my%widgetname%.widget' to s.mywibox:  
```lua
        ...
        mysystray,
        my%widgetname%.widget,
        mytextclock
        ...
```
&ensp;&ensp;&ensp;&ensp;Adjust widget's variables and its code.
