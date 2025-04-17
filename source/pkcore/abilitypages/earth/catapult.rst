.. catapult:
############
CATAPULT
############

Description
###########

**Element:** Earth

Catapult is an earthbending technique that allows the user to launch a large mass of earth or stone into the air at high velocity. This move can be used to launch projectiles or even enemies, making it an effective offensive tool to deal damage or disrupt enemy positioning.

Usage
#####

**Function 1:** Left-click to launch a large boulder or chunk of earth in the direction you’re facing

**Function 2:** Hold sneak and left-click to adjust the strength and trajectory of the projectile, sending it further or with more force

.. tip:: Catapult is great for attacking from a distance or using environmental cover to your advantage. It’s also useful for knocking enemies back or over obstacles.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.catapult            | Access to Catapult ability    | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    Catapult:
      Enabled: true
      Cooldown: 7000
      StageTimeMult: 2.0
      Angle: 45
      CancelWithAngle: false
