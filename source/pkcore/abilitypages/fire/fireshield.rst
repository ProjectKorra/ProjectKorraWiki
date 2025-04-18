.. fireshield:
############
FIRESHIELD
############

Description
###########

**Element:** Fire

FireShield is a defensive firebending ability that surrounds the user with a protective barrier of flame. The shield deflects incoming projectiles and deals damage to enemies who come into direct contact with it. It's perfect for defending against ranged attacks or pushing back enemies trying to get too close.

Usage
#####

**Function 1:** Left-click to activate the shield, surrounding yourself with a fiery barrier

**Function 2:** Hold sneak and left-click to increase the size and strength of the shield, expanding its defensive capabilities

.. tip:: FireShield can be used strategically to block ranged attacks or to intimidate enemies. It’s also a great way to keep attackers at bay when you're surrounded.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.fireshield          | Access to FireShield ability  | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    FireShield:
      Enabled: true
      Shield:
        Radius: 3
        Duration: 0
        Cooldown: 0
        FireTicks: 2
      Disc:
        Radius: 1.5
        Duration: 1000
        Cooldown: 500
        FireTicks: 2
