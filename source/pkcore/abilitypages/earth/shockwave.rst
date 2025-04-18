.. shockwave:
############
SHOCKWAVE
############

Description
###########

**Element:** Earth

Shockwave is a powerful earthbending move that sends a concentrated shockwave through the ground, knocking back and damaging enemies in its path. This move is especially effective for crowd control, pushing opponents away or disrupting their formations, and can be used to clear large areas quickly.

Usage
#####

**Function 1:** Left-click to send a shockwave in the direction you're facing, knocking back enemies and dealing damage

**Function 2:** Hold sneak and left-click to increase the strength and radius of the shockwave, affecting more enemies

.. tip:: Shockwave is ideal for pushing enemies away from you or disrupting their positioning. Use it to clear space in tight areas or to break enemy lines.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.shockwave           | Access to Shockwave ability   | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    Shockwave:
      Enabled: true
      FallThreshold: 12
      ChargeTime: 2500
      Cooldown: 6000
      Damage: 4
      Knockback: 1.1
      Range: 15
      Angle: 40
