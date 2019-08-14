========================
Commands and Permissions
========================

This page contains all of the commands and permissions in ProjectKorra Core.

.. note:: Last updated for v1.8.8

Commands
========
The base command for the ProjectKorra plugin is ``/projectkorra``. Aliases for this
command are ``/bending, /b, /bend, /tla, /mtla, /korra,  /pk``.

.. tip:: The ``/projectkorra`` command is more commonly known as ``/bending`` and will be referred to below by that alias.

+++++

.. note:: All commands are actually subcommands of ``/bending``, where one would
          do /bending <subcommand> to perform a function. (i.e /bending help)

| Argument Syntax
| ``<> - mandatory``
| ``[] - optional``

+++++

Add
---
| Usage: ``/bending add <element> <player>``
| Aliases: ``[a]``

Adds the specified <element> to the target <player>.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.add                        | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.add.others                 | allows adding elements to other players | op       |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.add.<element>              | allows adding of a specific element     | default  |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Bind
----
| Usage: ``/bending bind <ability> [1-9]``
| Aliases: ``[b]``

Binds the <ability> to the selected slot [1-9] or the held item slot if not given.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.bind                       | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Check
-----
| Usage: ``/bending check``
| Aliases: ``[chk]``

Checks if the the server is running the latest version of ProjectKorra Core.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.check                      | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Choose
------
| Usage: ``/bending choose [player] <element>``
| Aliases: ``[ch]``

Changes the player's element to the given element. If the player has multiple elements,
they are removed before setting the new element.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.choose                     | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.choose.<element>           | allows choosing for a specific element  | default  |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.rechoose                   | allows players to change their element  | op       |
+--------------------------------------------+-----------------------------------------+----------+
| bending.admin.choose                       | allows choosing elements for others     | op       |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Clear
-----
| Usage: ``/bending clear``
| Aliases: ``[c, cl]``

Clears the user's binds.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.clear                      | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Copy
----
| Usage: ``/bending copy <player> [player]``
| Aliases: ``[co]``

Copies another player's binds to the targeted player or the user if not given.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.copy                       | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.copy.assign                | allows copying to other player's binds  | op       |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Debug
-----
| Usage: ``/bending debug``
| Aliases: ``[de]``

Creates a debug file in the ProjectKorra folder to be given with a bug report.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.debug                      | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Display
-------
| Usage: ``/bending display [(sub)element]``
| Aliases: ``[d, dis]``

Displays the user's binds or the abilities in the given element.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.display                    | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Help
----
| Usage: ``/bending help [topic]``
| Aliases: ``[h]``

Shows the help for a given topic, usually and ability, element, or other feature
of the plugin, or lists all bending commands if not given a topic.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.help                       | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Invincible
----------
| Usage: ``/bending invincible``
| Aliases: ``[i, inv]``

Makes the user invincible to bending effects.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.invincible                 | allows use of command                   | op       |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Permaremove
-----------
| Usage: ``/bending permaremove <player>``
| Aliases: ``[pr, premove, permremove]``

Permanently removes the bending of <player>. Can be reversed by doing
the command on them again.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.admin.permaremove                  | allows use of command                   | op       |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Preset
------
| Usage: ``/bending preset [list / create / delete / bind] [name] [player]``
| Aliases: ``[p, pre, set, presets]``

Base preset command, allows for creating, deleting, or binding a preset
if given a name, or listing them.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.preset                     | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.preset.list                | allows listing of user's presets        | default  |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.preset.create              | allows creating new presets             | default  |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.preset.create.#            | allows player to have # of presets (5)  | default  |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.preset.delete              | allows deleting existing presets        | default  |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.preset.bind                | allows binding of presets               | default  |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.preset.bind.assign         | allows binding presets to other players | op       |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.preset.bind.external       | allows binding of global presets        | op       |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.preset.bind.external.other | allows binding presets of other players | op       |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Reload
------
| Usage: ``/bending reload``
| Aliases: ``[r]``

Reloads ProjectKorra Core and all side plugins.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.admin.reload                       | allows use of command                   | op       |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Remove
------
| Usage: ``/bending remove <player> [element]``
| Aliases: ``[rm]``

Removes all of the elements from the <player> or solely [element].

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.admin.remove                       | allows use of command                   | op       |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Stats
-----
| Usage: ``/bending <get / leaderboard> <ability / element / all> <statistic> [player / page]``
| Aliases: ``[statistics]``

Command for viewing various stats on the server. They can be searched per player
or by the leaderboard, which will show everyone's stats for the given type. Stats
are also dependent on whether you want a specific ability, element, or all of them.

+--------------+
|  Statistics  |
+--------------+
| PlayerKills  |
+--------------+
| PlayerDamage |
+--------------+
| TotalKills   |
+--------------+
| TotalDamage  |
+--------------+

+++++

Toggle
------
| Usage: ``/bending toggle [element / player / all]``
| Aliases: ``[t]``

Toggles the selected element, or bending of the targeted player or all,
and toggles bending for self if not argument given.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.toggle                     | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.toggle.all                 | allows toggling of all bending          | op       |
+--------------------------------------------+-----------------------------------------+----------+
| bending.admin.toggle                       | allows toggling other players           | op       |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Version
-------
| Usage: ``/bending version``
| Aliases: ``[v]``

Displays the versions of ProjectKorra plugins installed on the server.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.version                    | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Who
---
| Usage: ``/bending who [player]``
| Aliases: ``[w]``

Displays detailed bending info about the given player, or lists all online players and their elements.

+-------------------------------------------------------------------------------------------------+
| Permissions                                                                                     |
+--------------------------------------------+-----------------------------------------+----------+
| bending.command.who                        | allows use of command                   | default  |
+--------------------------------------------+-----------------------------------------+----------+

+++++

Permissions
===========
The following table represents all other permissions in ProjectKorra Core.

To give or take permissions you can either define them in your permissions.yml or use a permissions plugin (i.e PermissionsEx or GroupManager).

In the absence of a permissions plugin, permissions marked ``default`` will be available to everyone whereas permissions designated as ``op`` will only be available to operators.

.. note:: Certain abilities and subelements (namely AvatarState, Bloodbending, and Flight) can only be used by opped players by default.

+--------------------------------+------------------------------------------------+---------+
| Permission                     | Description                                    | Default |
+--------------------------------+------------------------------------------------+---------+
| bending.player                 | Allows access to most of the plugin's features | true    |
+--------------------------------+------------------------------------------------+---------+
| bending.admin                  | Allows access to administrative features       | op      |
+--------------------------------+------------------------------------------------+---------+
| bending.admin.<command>        | Allows access to an administrative command     | op      |
+--------------------------------+------------------------------------------------+---------+
| bending.avatar                 | Gives the avatar color in chat                 | false   |
+--------------------------------+------------------------------------------------+---------+
| bending.<element>              | Allows access to <element>                     | true    |
+--------------------------------+------------------------------------------------+---------+
| bending.<element>.passive      | Allows access to <element> passives            | false   |
+--------------------------------+------------------------------------------------+---------+
| bending.<element>.<subelement> | Allows access to <subelement> of <element>     | varies  |
+--------------------------------+------------------------------------------------+---------+
| bending.ability.<ability>      | Allows usage of <ability>                      | varies  |
+--------------------------------+------------------------------------------------+---------+
| bending.donor                  | Shows the player as a donor in the who command | false   |
+--------------------------------+------------------------------------------------+---------+
| bending.command.<command>      | Allows usage of <command>                      | varies  |
+--------------------------------+------------------------------------------------+---------+
| bending.command.rechoose       | Allows the player to rechoose their element    | false   |
+--------------------------------+------------------------------------------------+---------+
| bending.message.daymessage     | Allows the player to see the day message       | true    |
+--------------------------------+------------------------------------------------+---------+
| bending.message.nightmessage   | Allows the player to see the night message     | true    |
+--------------------------------+------------------------------------------------+---------+
