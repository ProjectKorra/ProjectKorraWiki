.. airblast:
############
AIRBLAST
############

Description
###########

**Element:** Air

AirBlast is a quick, focused burst of wind that travels in a straight line. It can knock back enemies, extinguish flames, and deflect certain projectiles. It's a versatile utility move that can also interrupt enemy abilities and trigger redstone.

Usage
#####

**Function 1:** Left-click to launch a blast in the direction you're facing

**Function 2:** Sneak and left-click to target a specific entity or block

.. tip:: AirBlast is great for pushing enemies off cliffs or interrupting their charge attacks. Use it smartly in combo with other bending moves!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-----------------------------+---------+
| Permission                          | Function                    | Default |
+-------------------------------------+-----------------------------+---------+
| bending.ability.airblast            | Access to AirBlast ability  | true    |
+-------------------------------------+-----------------------------+---------+

Configuration
#############

.. code:: YAML

    AirBlast:
      Enabled: true
      Speed: 15
      Range: 20
      Radius: 0.5
      SelectRange: 10
      SelectParticles: 4
      Particles: 6
      Cooldown: 500
      Push:
        Self: 2.0
        Entities: 1.6
      CanFlickLevers: true
      CanOpenDoors: true
      CanPressButtons: true
      CanCoolLava: true
