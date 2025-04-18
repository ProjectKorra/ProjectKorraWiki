.. tremorsense:
############
TREMORSENSE
############

Description
###########

**Element:** Earth

TremorSense is an earthbending ability that allows the user to sense vibrations in the ground, detecting nearby entities even through walls or obstacles. The vibrations provide a detailed map of the surrounding area, helping the user locate hidden or moving targets with precision.

Usage
#####

**Function 1:** Sneak to activate TremorSense and begin sensing vibrations around you

**Function 2:** The user can detect entities within a specific radius, even those that are underground or behind walls

.. tip:: TremorSense is a great utility ability for tracking enemy movements or finding hidden players. Use it strategically to anticipate ambushes or surprise attacks.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.tremorsense         | Access to TremorSense ability | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    Tremorsense:
      Enabled: true
      MaxDepth: 10
      Radius: 5
      LightThreshold: 7
      Cooldown: 1000
      StickyRange: 3
