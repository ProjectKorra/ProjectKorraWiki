.. warriorstance:
##################
WARRIORSTANCE
##################

Description
###########

**Element:** Chi

WarriorStance is a powerful chi ability that allows the user to enter a defensive stance, significantly increasing their strength and resilience. While in this stance, the user gains increased damage resistance, making it ideal for tanking hits and withstanding powerful attacks in combat.

Usage
#####

**Function 1:** Sneak to enter WarriorStance, increasing defense and attack power  
**Function 2:** While active, the user’s physical damage is increased, and they take reduced damage from enemies  
**Function 3:** Deactivate by sneaking again or after a set duration

.. tip:: Use WarriorStance when you need to hold the front lines or tank damage for your team. It’s particularly effective when facing multiple enemies.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+----------------------------------------+-------------------------------+---------+
| Permission                             | Function                      | Default |
+----------------------------------------+-------------------------------+---------+
| bending.ability.warriorstance          | Access to WarriorStance       | true    |
+----------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    WarriorStance:
      Enabled: true
      Cooldown: 0
      Duration: 0
      Strength: 1
      Resistance: -3
