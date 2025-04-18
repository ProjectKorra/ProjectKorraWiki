.. earthgrab:
############
EARTHGRAB
############

Description
###########

**Element:** Earth

EarthGrab allows the user to manipulate the earth beneath their enemies, causing the ground to rise up and ensnare them. This ability immobilizes the target, leaving them vulnerable to other attacks while they are trapped by the earth. It’s an effective control move for dealing with aggressive enemies or escaping a tight spot.

Usage
#####

**Function 1:** Left-click to grab a nearby enemy by the ground, immobilizing them in place

**Function 2:** Hold sneak and left-click to strengthen the earth’s grip, making the target unable to escape for a longer duration

.. tip:: EarthGrab works well for setting up other attacks or giving you time to retreat. Be mindful of its cooldown, as it can be countered by opponents with strong mobility.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.earthgrab           | Access to EarthGrab ability   | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    EarthGrab:
      Enabled: true
      SelectRange: 7
      DragSpeed: 0.8
      Cooldown: 5000
      Range: 14
      TrapHitInterval: 400
      TrapHP: 3
      DamageThreshold: 4
