========================
Commands and Permissions
========================

.. note:: This page contains all of the commands and permissions in ProjectKorra (Core). It was last updated for v1.8.7.

Commands
========
This following chart represents all of the available, functional, commands in ProjectKorra. 

The base command for the ProjectKorra plugin is /bending. There are aliases for this command. Aliases for /bending are /b, /bend, /tla, /mtla, /korra, /projectkorra, /pk, /minecrafttla. 

.. note:: Commands are all actually subcommands of /bending, where one would do /bending <subcommand> to perform a function. (i.e /bending help)

| <> - mandatory
| [] - optional


+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| Command             | Description                                                                          | Usage                                 | Aliases | Permission                                  |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending add        | Adds an element to the player                                                        | /bending add <player> <element>       | a       | bending.command.add                         |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      |                                       |         | bending.command.add.others                  |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending bind       | Binds an ability to the selected/chosen slot                                         | /bending bind [#1-9]                  | b       | bending.command.bind                        |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending check      | Check's if the server is running the latest version of ProjectKorra                  | /bending check                        |         | bending.command.check                       |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending choose     | Changes the player's element to given element                                        | /bending choose [player] <element>    | ch      | bending.command.choose                      |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      |                                       |         | bending.command.choose.[element]            |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      |                                       |         | bending.command.rechoose                    |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      |                                       |         | bending.admin.choose                        |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending clear      | Clears the player's binds                                                            | /bending clear                        | c       | bending.command.clear                       |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending copy       | Copies another players binds                                                         | /bending copy <player> [player]       |         | bending.command.copy                        |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      |                                       |         | bending.command.copy.assign                 |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending display    | Display's the player's binds or the abilities in a given element                     | /bending display [element|subelement] | d       | bending.command.display                     |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending debug      | Creates a debug file within the ProjectKorra directory of the server's plugin folder | /bending debug                        |         | bending.admin.debug                         |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending help       | Displays an ability description and usage                                            | /bending help [ability]               | h       | bending.command.help                        |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending invincible | Renders the user unaffected by bending                                               | /bending invincible                   |         | bending.command.invincible                  |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending preset     | Creates a preset of bound abilities for easy binding                                 | /bending preset list                  | p, l|c  | bending.command.preset                      |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      | /bending preset create [name]         |         | bending.command.preset.create               |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      | /bending preset delete [name]         |         | bending.command.preset.list                 |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      | /bending preset bind [name]           |         | bending.command.preset.bind                 |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      |                                       |         | bending.command.preset.bind.assign          |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      |                                       |         | bending.command.preset.bind.external        |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      |                                       |         | bending.command.preset.bind.external.other  |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      |                                       |         | bending.command.preset.delete               |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending permaremove| Permanently removes bending from the player                                          | /bending permaremove <player>         |         | bending.admin.permaremove                   |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending remove     | Removes bending from the player                                                      | /bending remove <player>              | r       | bending.admin.remove                        |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending toggle     | Toggles all bending and passives                                                     | /bending toggle [name|all]            | t       | bending.command.toggle                      |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      |                                       |         | bending.command.toggle.all                  |
|                     |                                                                                      |                                       |         |                                             |
|                     |                                                                                      |                                       |         | bending.admin.toggle                        |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending version    | Displays the installed ProjectKorra version                                          | /bending version                      | v       | bending.command.version                     |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+
| /bending who        | Displays a list of online players and their bending information                      | /bending who [name]                   | w       | bending.command.who                         |
+---------------------+--------------------------------------------------------------------------------------+---------------------------------------+---------+---------------------------------------------+


+++++

Permissions
===========
The following table represents all other permissions in ProjectKorra.

To give or take permissions you can either define them in your permissions.yml or use a plugin like PermissionsEx or GroupManager. These will allow you to remove or give the following permissions nodes to your players.

Permissions marked default are available to everyone in the absence of a permissions plugin and op is available to opped players.

.. note:: Certain abilities (namely Bloodbending and AvatarState) can only be used by opped players by default

+--------------------------------+-----------------------------------------------------------+------------+
| Permission                     | Description                                               | Default    |
+--------------------------------+-----------------------------------------------------------+------------+
| bending.admin                  | Grants access to all abilities and commands               | op         |
+--------------------------------+-----------------------------------------------------------+------------+
| bending.ability.[Ability]      | Grants access to ability                                  | default/op |
+--------------------------------+-----------------------------------------------------------+------------+
| bending.air                    | Grants access to all default Air abilities and passives   | default    |
|                                |                                                           |            |
| bending.air.passive            |                                                           |            |
|                                |                                                           |            |
| bending.air.Flight             |                                                           |            |
+--------------------------------+-----------------------------------------------------------+------------+
| bending.chi                    | Grants access to all default Chi abilities and passives   | default    |
|                                |                                                           |            |
| bending.chi.passive            |                                                           |            |
+--------------------------------+-----------------------------------------------------------+------------+
| bending.donor                  | Gives the donor tag to the player                         | none       |
+--------------------------------+-----------------------------------------------------------+------------+
| bending.earth                  | Grants access to all default Earth abilities and passives | default    |
|                                |                                                           |            |
| bending.earth.passive          |                                                           |            |
|                                |                                                           |            |
| bending.earth.lavabending      |                                                           |            |
|                                |                                                           |            |
| bending.earth.metalbending     |                                                           |            |
|                                |                                                           |            |
| bending.earth.sandbending      |                                                           |            |
+--------------------------------+-----------------------------------------------------------+------------+
| bending.fire                   | Grants access to all default Fire abilities and passives  | default    |
|                                |                                                           |            |
| bending.fire.passive           |                                                           |            |
|                                |                                                           |            |
| bending.fire.combustionbending |                                                           |            |
|                                |                                                           |            |
| benfing.fire.lightningbending  |                                                           |            |
+--------------------------------+-----------------------------------------------------------+------------+
| bending.message                | Displays night/day messages for Waterbenders/Firebenders  | default    |
|                                |                                                           |            |
| bending.message.nightmessage   |                                                           |            |
|                                |                                                           |            |
| bending.message.daymessage     |                                                           |            |
+--------------------------------+-----------------------------------------------------------+------------+
| bending.water                  | Grants access to all default Water abilities and passives | default    |
|                                |                                                           |            |
| bending.water.passive          |                                                           |            |
|                                |                                                           |            |
| bending.water.healing          |                                                           |            |
|                                |                                                           |            |
| bending.water.icebending       |                                                           |            |
|                                |                                                           |            |
| bending.water.plantbending     |                                                           |            |
+--------------------------------+-----------------------------------------------------------+------------+
