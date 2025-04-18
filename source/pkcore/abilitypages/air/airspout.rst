.. airspout:
############
AIRSPOUT
############

Description
###########

**Element:** Air

AirSpout allows the user to hover high above the ground on a swirling column of air. It provides vertical mobility and a safe vantage point, useful for traveling or avoiding ground-based combat. The spout can be maintained as long as the user remains still or moves slowly.

Usage
#####

**Function 1:** Hold sneak to rise into the air on a spout of wind

**Function 2:** Move around slowly while sneaking to stay on the spout

.. tip:: Use AirSpout to reach high places or escape combat. Be cautious—projectiles or abilities can still knock you off!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-----------------------------+---------+
| Permission                          | Function                    | Default |
+-------------------------------------+-----------------------------+---------+
| bending.ability.airspout            | Access to AirSpout ability  | true    |
+-------------------------------------+-----------------------------+---------+

Configuration
#############

.. code:: YAML

     AirSpout:
      Enabled: true
      Cooldown: 0
      Duration: 0
      Height: 16
      Interval: 100
