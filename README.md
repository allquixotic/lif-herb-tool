# lif-herb-tool
Herbalism tool for Life is Feudal computer game

## Installation

* Place the files in the directory mod/lif-herb-tool/ under the game root directory.
* Add the following line in the file script/client/init.cs. It should be placed around Line 128, at the end of the block of statements beneath the comment `// CM_Inventory` in the section `// Client Scripts`.

  `exec("mod/lif-herb-tool/init.cs");`
  * Alternatively, it is possible to load the mod from the console, instead of automactically from a script file  (if you just want to test the mod). Join your server, open the console using `ctrl`+`~`, and then write `exec("mod/lif-herb-tool/init.cs");`

## Usage

* Open your inventory
* Press Ctrl+S to sort all herbs
