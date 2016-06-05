# setup-code-program
My program for setting up files with code

## Config

### Warning: To be able to edit the config and the changes work you have to put the path of your directory where the config is inside of the SetUp.lua file.

**The config template is**

Folder/Where/Lua/files/go

Folder/Where/HTML/files/go

Folder/Where/Java/files/go

Folder/Where/ShellScript/files/go

Folder/Where/Love/Projects/go

y or n for Hero's Library which overrides LuaFileSystem Library added to Lua Projects

y or n for LuaFileSystem Library added to Lua Projects

y or n for Automaticly adding Assets folder to Love Projects

y or n for parts of Hero's Library from lua to Love Projects

y or n for parts of Hero's Library from lua and Automaticly adding Assets folder to Love Projects

**The config does not care what you put after line 10**

## Errors

If the error is simmilar to "lua: SetUp.lua:172: attempt to index a nil value (global 'file')" then you have selected invalid file.

If the error is simmilar to "lua: SetUp.lua:210: attempt to concatenate a nil value (global 'startCodeDirLua')" then the path to the config file is wrong.
