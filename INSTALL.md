# Installation Instructions
## Graphical Installation
Navigate to `System Settings > Window Management > KWin Scripts` and:
* Either click on the `Import KWin script...` button and browse for the downloaded script,
* or click on the `Get New Scripts...` button and search for the script online through the `Get Hot New Stuff` dialog.

## Console Installation
`$ plasmapkg2 -i /path/to/movewindowtocenter.kwinscript`

# Uninstallation Instructions
If you installed the script through the `Get Hot New Stuff` dialog, you should uninstall it through the same dialog. Otherwise the following command will do:

`$ plasmapkg2 -t KWin/Script -r movewindowtocenter`

###### Note: The dollar sign (`$`) indicates a shell prompt.
