# alloy.babel
Appcelerator Titanium plugin which enables ES6, Pug (Jade), STSS support for Alloy projects

## Configuration
1. Place all your code in the folder `src` instead of `app`
2. Create a folder `${project_dir}/plugins/alloy.babel/0.0.1`
3. Place the plugin code in that folder
4. Add `<plugin version="0.0.1">alloy.babel</plugin>` to your `tiapp.xml > ti:app > plugins` XML element.
**Note:** this plugin should appear before `ti.alloy` plugin
