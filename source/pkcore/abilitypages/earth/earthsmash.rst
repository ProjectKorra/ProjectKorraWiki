.. earthsmash:
############
EARTHSMASH
############

Description
###########

**Element:** Earth

EarthSmash is a powerful earthbending move that allows the user to slam the ground with incredible force, creating a shockwave that damages and knocks back enemies in the surrounding area. It's a high-impact attack that can disrupt multiple foes at once, making it great for crowd control.

Usage
#####

**Function 1:** Left-click to smash the ground and create a shockwave in front of you

**Function 2:** Hold sneak and left-click to increase the power of the smash, dealing more damage and affecting a larger area

.. tip:: EarthSmash is perfect for clearing groups of enemies or creating space between you and multiple attackers. Use it strategically for maximum effect!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.earthsmash          | Access to EarthSmash ability  | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    EarthSmash:
      Enabled: true
      Duration: 30000
      SelectRange: 12
      ChargeTime: 1500
      Cooldown: 3000
      MinimumDamage: 2
      MaximumDamage: 5
      Knockback: 3.5
      Knockup: 0.15
      Lift:
        Knockup: 1.1
        Range: 3.5
      Flight:
        Enabled: true
        Speed: 0.72
        Duration: 3000
        AnimationInterval: 0
        DetectionRadius: 3.5
      Grab:
        Enabled: true
        Range: 16
        DetectionRadius: 2.5
      Shoot:
        Range: 25
        AnimationInterval: 25
        CollisionRadius: 2.5
      RequiredBendableBlocks: 11
      MaxBlocksToPassThrough: 3
      LiftAnimationInterval: 30
