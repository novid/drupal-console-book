# generate:plugin:ckeditorbutton
Generate CKEditor button plugin.

**Usage:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin ID. NOTE: This corresponds to the CKEditor plugin name. It is the first argument of the CKEDITOR.plugins.add() function in the plugin.js file.
--button-name | Button name. NOTE: This corresponds to the CKEditor button name. They are the first argument of the editor.ui.addButton() or editor.ui.addRichCombo() functions in the plugin.js file.
--button-icon-path | Button icon path. This is the path to the icon/image of the button.

## Examples
* Generate plugin CKEditor button specifying the module name, the class, the label, its id, the button name and the icon path
```
drupal generate:plugin:ckeditorbutton  \
  --module="modulename"  \
  --class="DefaultCKEditorButton"  \
  --label="Default ckeditor button"  \
  --plugin-id="default ckeditor button"  \
  --button-name="Default ckeditor button"  \
  --button-icon-path="modules/custom/modulename/js/plugins/default ckeditor button/images/icon.png"
```
