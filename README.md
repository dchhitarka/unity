# Games in Unity/C#

## If you are unable to load the games in your browser, then try the following steps for yopur respective browser ti turn on WebGL support. 

### Firefox (recommended browser for running WebGL)

    1. Type about:config in the navigation bar
    2. Search for the security.fileuri.strict_origin_policy parameter
    3. Click that parameter to change it to false

### Chrome

    1. Add a shortcut to Chrome on your desktop if you don't have one
    2. Right click the shortcut and select Properties
    3. Select the Target text box, go to the end, add a space and add --allow-file-access-from-files
    4. Double-click the index html file for the WebGL build and copy the URL in the navigation bar when the browser opens
    5. Close the browser
    6. Start the browser using the shortcut, paste in the URL you copied in Step 4 and press enter

### Microsoft Edge

	1. No need to do anything, WebGL builds work fine.

### Safari

    1. Enable the develop menu using the preferences panel, under Advanced → “Show develop menu in menu bar”.
    1. From the safari “Develop” menu, select “Disable local file restrictions”. 
