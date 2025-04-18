.. acrobatstance:
##################
ACROBATSTANCE
##################

Description
###########

**Element:** Chi

AcrobatStance is a passive chi-blocking stance that enhances the user's agility, balance, and evasion capabilities. While active, it improves movement speed and reduces fall damage, making it perfect for fast-paced combat and evasive maneuvers.

Usage
#####

**Function 1:** Sneak to activate the stance, boosting movement capabilities  
**Function 2:** While active, receive bonus movement speed and take reduced fall damage  
**Function 3:** Deactivate by sneaking again or after a set duration

.. tip:: AcrobatStance is great for staying mobile in battle. Use it to dodge bending abilities or close the gap quickly!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+----------------------------------------+-------------------------------+---------+
| Permission                             | Function                      | Default |
+----------------------------------------+-------------------------------+---------+
| bending.ability.acrobatstance          | Access to AcrobatStance       | true    |
+----------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    AcrobatStance:
      Enabled: true
      Cooldown: 0
      Duration: 0
      ChiBlockBoost: 3
      Speed: 3
      Jump: 3
