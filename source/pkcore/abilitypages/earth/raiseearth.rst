.. raiseearth:
############
RAISEEARTH
############

Description
###########

**Element:** Earth

RaiseEarth is a powerful earthbending move that allows the user to lift large chunks of earth from the ground, shaping them into walls, platforms, or projectiles. It provides both offensive and defensive uses, allowing the user to block incoming attacks or launch boulders at enemies.

Usage
#####

**Function 1:** Sneak and left-click to raise a chunk of earth from the ground

**Function 2:** Hold sneak and then left-click to shape the raised earth into a wall or platform

.. tip:: Use RaiseEarth to block incoming projectiles or create barriers for cover. It's also great for creating high ground when fighting!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.raiseearth          | Access to RaiseEarth ability  | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    RaiseEarth:
      Enabled: true
      Speed: 10
      Column:
        SelectRange: 20
        Height: 6
        Cooldown: 500
      Wall:
        SelectRange: 20
        Height: 6
        Width: 6
        Cooldown: 500
