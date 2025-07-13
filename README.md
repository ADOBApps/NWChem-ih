
# NWChem Input File Syntax Highlighting

This repository contains files that tell the Sublime Text 3 code editor how to color NWChem input file so that they are easier to read.

Put these files in your _User_ folder in Sublime Text 3 for file highlighting of NWChem input files. The _User_ folder can be accesed by going to menu: _Preferences > Browse Packages_. Usually the bottom folder will be _User_.

All files with extension *.nw should now show syntax highlighting.
You may have to close sublime and open it again for the changes to take effect.
## Snippets

In addition to syntax highlighting, we have created a few sublime snippets to make our lives a little easier:

1. To quickly add a geometry.  To use it type **geometry** followed by <kbd>Tab</kbd> to autocomplete the geometry section declaration.
2. To quickly add a PSeudopotential Plane-Wave section.  To use it type **pspw** followed by <kbd>Tab</kbd> to autocomplete.

_More snippets can easily be added by copying one of the .sublime-snippet files and then modifying it._ Go [here](http://sublimetext.info/docs/en/extensibility/snippets.html) for more information on snippets. 

## Source

This repository is based off of [ADOBApps/NWChem-ih](https://github.com/ADOBApps/NWChem-ih)

In [ADOBApps/NWChem-ih](https://github.com/ADOBApps/NWChem-ih) they use the old .tmLanguage file format.  This repository uses the new .sublime-syntax file format.
