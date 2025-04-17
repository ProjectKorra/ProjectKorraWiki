.. collapse:
############
COLLAPSE
############

Description
###########

**Element:** Earth

Collapse is an advanced earthbending ability that allows the user to create a localized seismic event, causing the ground beneath enemies to collapse inward. This move can deal significant damage, trap enemies, or even cause the terrain to shift, leaving foes disoriented and vulnerable.

Usage
#####

**Function 1:** Left-click to create a small shockwave that causes the ground beneath your target to collapse

**Function 2:** Hold sneak and left-click to create a larger shockwave with a wider radius, affecting multiple targets

.. tip:: Collapse can be a game-changer when you need to trap or deal damage to a group of enemies. It’s most effective when the enemies are clustered in one area.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.collapse            | Access to Collapse ability    |  true   |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    Collapse:
      Enabled: true
      SelectRange: 20
      Radius: 7
      Speed: 8
      Column:
        Height: 6
        Cooldown: 500
      Wall:
        Height: 6
        Cooldown: 500
