# Installation Instructions
## Copying files
In Firefox, go to about:profiles and look for the profile in use. Open the "Root Directory" folder. Copy the contents of /profile into this folder.  
Next you can go to your Firefox installation directory (It should be C:/Program Files (x86)/Mozilla Firefox. Copy the contents of /ffroot into this directory, you may need administrator permissions.

## Setting up
After restarting, you're going to need to go to about:config and enable these flags:
- toolkit.legacyUserProfileCustomizations.stylesheets - set to true
- svg.context-properties.content.enabled - set to true
- ui.prefersReducedMotion - set to 1, you may need to create a new "Number" value
- widget.non-native-theme.enabled - set to false,  
- extensions.unifiedExtensions.enabled - set to true, 109+ only

then restart Firefox.

## UI Configuration
After installation, right click on the tabs toolbar and press "Customize Toolbar". Here is a guide to help you:

NO IMAGE YET

**Make sure to enable Title Bar**  
