.. airscooter:
############
AIRSCOOTER
############

Description
###########

**Element:** Air

AirScooter is a high-speed movement ability that allows the user to zip across the ground on a cushion of air. By controlling the flow of wind beneath them, the user can travel quickly while being agile, avoiding obstacles, and outrunning opponents.

Usage
#####

**Function 1:** Hold sneak to ride a controlled air scooter beneath you

**Function 2:** Use directional movement keys to steer and accelerate

.. tip:: Use AirScooter to move swiftly around the battlefield or to escape combat quickly. It's great for hit-and-run tactics or evading enemies.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.airscooter          |  Access to AirScooter ability | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    AirScooter:
      Enabled: true
      ShowSitting: false
      Speed: 0.675
      Interval: 100
      Radius: 1
      Cooldown: 7000
      Duration: 0
      MaxHeightFromGround: 7
