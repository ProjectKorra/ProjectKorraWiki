========================
Commands and Permissions
========================

Description
===========
.. note:: This page contains all of the commands and permissions in ProjectKorra (Core). It was last updated for v1.8.6.

The base command for the ProjectKorra plugin is /bending. Within this command, there are aliases and subcommands. Aliases are other words that you can use to execute the base command. Aliases for ProjectKorra are /b, /bend, /tla, /mtla, /korra, /projectkorra, /pk, /minecrafttla. Subcommands are the functions of the command, such as bind or help.

When reading the help page, anything that is enclosed in <> is required and anything enclosed in [] is optional. The command will still function if you do not fill in anything where the brackets ([]) are. If you see a "|" in a command, it means "or".

If you'd like to take permissions away, for those that default to a rank, you can remove them by negating their permission. Whenever you want to negate a permission, add the permission with a '-' in front of it. For example, if I'm using PermissionsEX and I wanted to remove the ability for players to create presets, I'd do this command:

.. code::
/pex group (group) add -bending.commands.presets.*

Player Commands and Permissions
-------------------------------
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| Command          | Description                                                                                                                                                          | Usage                                              | Permission Node                           |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending help    | Shows help on a given command.                                                                                                                                       | /bending help [command]                            | bending.command.help (DEFAULT)            |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending bind    | Binds an ability so a player can use it. If a slot is not specified, it will bind to whichever item slot the player is currently on.                                 | /bending bind <ability> [slot#]                    | bending.command.bind (DEFAULT)            |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending choose  | Chooses an element. Players can rechoose their bending with the appropriate permissions and admins with appropriate permissions can pick elements for other players. | /bending choose <element> [player]                 | bending.command.choose (DEFAULT)          |
|                  |                                                                                                                                                                      |                                                    |                                           |
|                  |                                                                                                                                                                      |                                                    | bending.command.rechoose (OP)             |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending clear   | Clears a bound ability. If no slot is specified, it'll clear all bound abilities.                                                                                    | /bending clear [slot#]                             | bending.command.clear (DEFAULT)           |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending preset  | This command manages presets, which are saved sets of bound abilities.                                                                                               | /bending preset <list|create|delete|bind> [preset] | bending.command.preset.list (DEFAULT)     |
|                  |                                                                                                                                                                      |                                                    | bending.command.preset.create.2 (DEFAULT) |
|                  |                                                                                                                                                                      |                                                    | bending.command.preset.create (DEFAULT)   |
|                  |                                                                                                                                                                      |                                                    | bending.command.preset.bind (DEFAULT)     |
|                  |                                                                                                                                                                      |                                                    | bending.command.preset.delete (DEFAULT)   |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending toggle  | Toggles a player's bending on/off. Server admins can use this to toggle specific elements or bending for the entire server.                                          | /bending toggle [all|element|player]               | bending.command.toggle (DEFAULT)          |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending version | Checks to see which version of ProjectKorra you are running on.                                                                                                      | /bending version                                   | bending.command.version (DEFAULT)         |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending who     | Views information of players on a server, or a specific player if one is specified.                                                                                  | /bending who [page|player]                         | bending.command.who (DEFAULT)             |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+

Admin Commands and Permissions
------------------------------
