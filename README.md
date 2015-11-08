# Lua plugin for Notepad++
  
* Verufy syntax of Lua scripts.
 
* Run the script from the current file.
* Print result in output console.

 Version Lua - 5.2.3 (http://www.lua.org).
 
 Additional libs:
	- lfs - v1.6.3 Copyright Kepler Project 2003 (http://www.keplerproject.org/luafilesystem)
	- marshal - v1.5 Richard Hundt <richardhundt@gmail.com> (https://github.com/richardhundt/lua-marshal)	

 Changes in Lua:
 - string.format can work with pattren %b for boolean values  
   (for example, print(string.format("%b_%b"), true, false) --> "true_false")
 - printf(fmt,...) same as print(string.format(fmt,...))
 - clear_console() - clear output console
 - show_console() - show console if it's hidden
 - messagebox (text [,caption, [wnd_type]] ) - show message box.  
 Caption is empty as default. Integer value wnd_type may be in interval 0..6.
 Result the function is the code of the pressed button.
