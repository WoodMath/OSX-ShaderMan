ShaderMan.Next is new code, and some of it's parts are just not implemented or use simple stubs.
Thus, the following list of limitations:

  * Generated output files are always named using test123.* pattern - this name is hardcoded for now.
  * Unix mode is hardly functional except the example scene file - it's just here to show the possibilities of the tool
    besides the usual code generation.
  * Node display colors are hardcoded.
  * Auto-update of preview doesn't work when editing the parameters of node. Hovewer it works OK when you connect/disconnect nodes.
  * Source code isn't really documented, however some important and tricky parts are.
  * Source code doesn't really adhere to PEP8 standards - I've mostly used the wxPython naming conventions and 8-spaces-tabulation.
