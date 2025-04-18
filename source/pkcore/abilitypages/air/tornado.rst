.. tornado:
############
TORNADO
############

Description
###########

**Element:** Air

Tornado summons a powerful vortex of swirling wind that lifts entities into the air and throws them around. It's a crowd-control move perfect for disrupting groups of enemies, controlling zones, or buying time to escape or reposition.

Usage
#####

**Function 1:** Sneak to summon a tornado around you

**Function 2:** Remain sneaking to keep the tornado active and move it with your direction

.. tip:: Use Tornado to break up enemy formations or send attackers flying. Be aware that it uses a lot of control and can leave you vulnerable while channeling.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-----------------------------+---------+
| Permission                          | Function                    | Default |
+-------------------------------------+-----------------------------+---------+
| bending.ability.tornado             | Access to Tornado ability   | true    |
+-------------------------------------+-----------------------------+---------+

Configuration
#############

.. code:: YAML

    Tornado:
      Enabled: true
      Cooldown: 0
      Duration: 0
      Radius: 10
      Height: 20
      Range: 25
      Speed: 1
      NpcPushFactor: 1
      PlayerPushFactor: 1
