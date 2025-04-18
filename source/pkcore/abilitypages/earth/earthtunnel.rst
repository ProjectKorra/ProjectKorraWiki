.. earthtunnel:
############
EARTHTUNNEL
############

Description
###########

**Element:** Earth

EarthTunnel is an earthbending technique that allows the user to create a tunnel beneath the ground, enabling underground travel. The tunnel can be used for sneaky maneuvers or escaping dangerous situations. However, it requires careful control, as the user must manage the earth around them to avoid getting trapped.

Usage
#####

**Function 1:** Sneak and right-click to start digging a tunnel beneath the ground

**Function 2:** Hold sneak and continue digging to expand the tunnel in any direction

**Function 3:** Right-click again to exit the tunnel at your chosen destination

.. tip:: EarthTunnel is perfect for escaping or setting up surprise attacks. Be aware of the terrain around you, as tunnels may collapse if not carefully managed.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.earthtunnel         | Access to EarthTunnel ability | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    EarthTunnel:
      Enabled: true
      RevertCheckTime: 300000
      Cooldown: 0
      MaxRadius: 1
      Range: 10
      Radius: 0.25
      Revert: true
      DropLootIfNotRevert: false
      IgnoredBlocks:
      - COAL_ORE
      - IRON_ORE
      - REDSTONE_ORE
      - LAPIS_ORE
      - DIAMOND_ORE
      - EMERALD_ORE
      - '#coal_ores'
      - '#iron_ores'
      - '#gold_ores'
      - '#copper_ores'
      - '#redstone_ores'
      - '#lapis_ores'
      - '#diamond_ores'
      - '#emerald_ores'
      - ANCIENT_DEBRIS
      - GILDED_BLACKSTONE
      - NETHER_QUARTZ_ORE
      Interval: 30
      BlocksPerInterval: 1
