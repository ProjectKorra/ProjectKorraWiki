.. walloffire:
############
WALLOFFIRE
############

Description
###########

**Element:** Fire

WallOfFire is a firebending ability that allows the user to create a wall of flames, providing both offense and defense. The wall acts as a barrier, blocking enemies and projectiles, while also dealing continuous damage to anyone who comes into contact with it. It's a versatile ability, useful for area denial or separating foes from the user.

Usage
#####

**Function 1:** Left-click to create a wall of fire in front of you, blocking movement and projectiles

**Function 2:** Hold sneak and left-click to extend the length and height of the wall, making it harder for enemies to pass through

.. tip:: WallOfFire can be a great tool for controlling the battlefield, forcing enemies to move around it or take damage. Use it strategically to separate dangerous mobs or players.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.walloffire          | Access to WallOfFire ability  | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    WallOfFire:
      Enabled: true
      Range: 3
      Height: 4
      Width: 4
      Duration: 5000
      Damage: 1
      Cooldown: 11000
      Interval: 250
      DamageInterval: 500
      FireTicks: 0
      MaxAngle: 50
