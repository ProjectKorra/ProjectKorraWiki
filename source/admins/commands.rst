========================
Commands and Permissions
========================

Description
===========
.. note:: This page contains all of the commands and permissions in ProjectKorra (Core). It was last updated for v1.8.6.

The base command for the ProjectKorra plugin is /bending. Within this command, there are aliases and subcommands. Aliases are other words that you can use to execute the base command. Aliases for ProjectKorra are /b, /bend, /tla, /mtla, /korra, /projectkorra, /pk, /minecrafttla. Subcommands are the functions of the command, such as bind or help.

When reading the help page, anything that is enclosed in <> is required and anything enclosed in [] is optional. The command will still function if you do not fill in anything where the brackets ([]) are. If you see a "|" in a command, it means "or".

When using subcommand permissions, they'll often be in the format bending.Main.Sub.SubSub. Using an asterisk (*) symbol, you can easily add all of the sub-permissions with one permission node. For example, if you wanted to add all bending abilities, the permission node would be bending.ability.*.

If you'd like to take permissions away, for those that default to a rank, you can remove them by negating their permission. Whenever you want to negate a permission, add the permission with a '-' in front of it. For example, if I'm using PermissionsEX and I wanted to remove the ability for players to create presets, I'd do this command:

.. code::

/pex group (group) add -bending.commands.presets.*

Player Commands and Permissions
-------------------------------
General Permissions
~~~~~~~~~~~~~~~~~~~

+-------------------------------+-------------------------------------------------------------+
| Permission Node               | Description                                                 |
+-------------------------------+-------------------------------------------------------------+
| bending.player                | Grants access to most abilities and basic commands.         |
+-------------------------------+-------------------------------------------------------------+
| bending.air                   | Grants access to Air Bending passives and most abilities.   |
+-------------------------------+-------------------------------------------------------------+
| bending.water                 | Grants access to Water Bending passives and most abilities. |
+-------------------------------+-------------------------------------------------------------+
| bending.earth                 | Grants access to Earth Bending passives and most abilities. |
+-------------------------------+-------------------------------------------------------------+
| bending.fire                  | Grants access to Fire Bending passives and most abilities.  |
+-------------------------------+-------------------------------------------------------------+
| bending.chi                   | Grants access to Chi Blocking passives and most abilities.  |
+-------------------------------+-------------------------------------------------------------+
| bending.avatar                | Grants access to the avatar color.                          |
+-------------------------------+-------------------------------------------------------------+
| bending.ability.<AbilityName> | Grants access to the ability that replaces "<AbilityName>"  |
+-------------------------------+-------------------------------------------------------------+
| bending.ability.AirCombo      | Grants access to the air combos.                            |
+-------------------------------+-------------------------------------------------------------+
| bending.ability.WaterCombo    | Grants access to the water combos.                          |
+-------------------------------+-------------------------------------------------------------+
| bending.ability.EarthCombo    | Grants access to the earth combos.                          |
+-------------------------------+-------------------------------------------------------------+
| bending.ability.FireCombo     | Grants access to the fire combos.                           |
+-------------------------------+-------------------------------------------------------------+
| bending.ability.ChiCombo      | Grants access to the chi combos.                            |
+-------------------------------+-------------------------------------------------------------+

Player Commands
~~~~~~~~~~~~~~~

+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| Command          | Description                                                                                                                                                          | Usage                                              | Permission Node                           |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending help    | Shows help on a given command.                                                                                                                                       | /bending help [command]                            | bending.command.help (DEFAULT)            |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending bind    | Binds an ability so a player can use it. If a slot is not specified, it will bind to whichever item slot the player is currently on.                                 | /bending bind <ability> [slot#]                    | bending.command.bind (DEFAULT)            |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending display | Displays your current bound abilities and abilities of each element on the server.                                                                                   | /bending display [element]                         | bending.command.display (DEFAULT)         |
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
| /bending copy    | Copy's another player's binds to yours.                                                                                                                              | /bending copy <player>                             | bending.command.copy (DEFAULT)            |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending toggle  | Toggles a player's bending on/off. Server admins can use this to toggle specific elements or bending for the entire server.                                          | /bending toggle [all|element|player]               | bending.command.toggle (DEFAULT)          |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending version | Checks to see which version of ProjectKorra you are running on.                                                                                                      | /bending version                                   | bending.command.version (DEFAULT)         |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+
| /bending who     | Views information of players on a server, or a specific player if one is specified.                                                                                  | /bending who [page|player]                         | bending.command.who (DEFAULT)             |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+-------------------------------------------+

Admin Commands and Permissions
------------------------------

General Permissions
~~~~~~~~~~~~~~~~~~~

+------------------------------------+-------------------------------------------------------------------------------+
| Permission Node                    | Description                                                                   |
+------------------------------------+-------------------------------------------------------------------------------+
| bending.admin                      | Gives all permissions, commands, and abilities to the permission holder.      |
+------------------------------------+-------------------------------------------------------------------------------+
| bending.player                     | Gives most abilities, passives, and basic commands to the permission holder.  |
+------------------------------------+-------------------------------------------------------------------------------+
| bending.donor                      | Gives the donor tag to the permission holder.                                 |
+------------------------------------+-------------------------------------------------------------------------------+
| bending.ability.AvatarState        | Grants access to use AvatarState.                                             |
+------------------------------------+-------------------------------------------------------------------------------+
| bending.water.BloodBending         | Enables the BloodBending subelement.                                          |
+------------------------------------+-------------------------------------------------------------------------------+
| bending.water.BloodBending.anytime | Makes it so that the player can use bloodbending any time, not just at night. |
+------------------------------------+-------------------------------------------------------------------------------+
| bending.Ability.Flight             | Grants access to use Flight.                                                  |
+------------------------------------+-------------------------------------------------------------------------------+
| bending.Ability.MetalClips.loot    | Grants access to use MetalClips to loot players.                              |
+------------------------------------+-------------------------------------------------------------------------------+
| bending.Ability.MetalClips.4clips  | Grants access to use 4 metal clips while using MetalClips.                    |
+------------------------------------+-------------------------------------------------------------------------------+
| bending.Ability.MetalClips.throw   | Grants access to throw the player under control when using MetalClips.        |
+------------------------------------+-------------------------------------------------------------------------------+

Admin Commands
~~~~~~~~~~~~~~

+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+
| Command              | Description                                                                                                                           | Usage                                              | Permission Node                            |
+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+
| /bending reload      | Disables and re-enables the ProjectKorra plugin to reload the configuration file.                                                     | /bending reload                                    | bending.command.reload                     |
+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+
| /bending avatar      | Gives the player all elements, abilities, passives, and the purple name.                                                              | /bending avatar <player>                           | bending.command.avatar                     |
+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+
| /bending add         | Adds an element to the player's current element(s).                                                                                   | /bending add <Player> <Element|SubElement>         | bending.command.add                        |
|                      |                                                                                                                                       |                                                    | bending.command.add.others                 |
+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+
| /bending import      | Imports data from Orion's original MinecraftTLA plugin. This should only be done once.                                                | /bending import                                    | bending.command.import                     |
+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+
| /bending toggle      | Can toggle specific elements or bending for the entire server.                                                                        | /bending toggle [all|element|player]               | bending.command.toggle.all                 |
|                      |                                                                                                                                       |                                                    | bending.admin.toggle                       |
+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+
| /bending invincible  | Toggles invincible mode where you will not be affected by any bending ability.                                                        | /bending invincible                                | bending.command.invincible                 |
+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+
| /bending check       | Checks to see if you're using the latest ProjectKorra version.                                                                        | /bending check                                     | bending.command.check                      |
+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+
| /bending preset      | Manages player ability presets.                                                                                                       | /bending preset <list|create|delete|bind> [preset] | bending.command.preset.bind.assign         |
|                      |                                                                                                                                       |                                                    | bending.command.preset.bind.external       |
|                      |                                                                                                                                       |                                                    | bending.command.preset.bind.external.other |
+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+
| /bending remove      | Removes specified element from player, or all of a player's Bending if no element is specified.                                       | /bending remove <player> [element]                 | bending.admin.remove                       |
+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+
| /bending permaremove | Permanently removes a player's bending. Players will not be able to pick their bending again until this command is run on them again. | /bending permaremove <player>                      | bending.admin.permaremove                  |
+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+
| /bending debug       | Outputs information about ProjectKorra and the installed add-ons on your server in the ProjectKorra plugin folder.                    | /bending debug                                     | bending.admin.debug                        |
+----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------+--------------------------------------------+