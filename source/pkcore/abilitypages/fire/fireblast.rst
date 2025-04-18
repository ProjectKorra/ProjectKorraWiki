.. fireblast:
############
FIREBLAST
############

Description
###########

**Element:** Fire

FireBlast is a powerful offensive firebending ability that allows the user to unleash a concentrated burst of flame in a straight line. The blast causes damage to any enemies it hits and can also ignite the surrounding area. It’s a versatile ability, effective for both single-target and area damage, and can be used to strike enemies at a distance.

Usage
#####

**Function 1:** Left-click to unleash a fire blast, dealing damage to any enemies in its path

**Function 2:** Hold sneak and left-click to increase the size and damage of the blast, making it more powerful and wider

**Function 3:** Right-click to target a specific area, launching a fire blast that explodes upon impact, igniting nearby enemies and terrain

.. tip:: FireBlast is great for dealing with enemies at a distance or clearing obstacles. Make sure to take advantage of the blast’s range and power for effective long-range attacks.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.fireblast           | Access to FireBlast ability   | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    FireBlast:
      Enabled: true
      Speed: 20
      Range: 20
      CollisionRadius: 1.0
      Knockback: 0.3
      Damage: 3
      Cooldown: 1500
      Dissipate: false
      FireTicks: 0
      SmokeParticleRadius: 0.3
      FlameParticleRadius: 0.275
      Charged:
        ChargeTime: 3000
        Cooldown: 2000
        CollisionRadius: 2
        MinimumDamage: 2
        MaximumDamage: 4
        DamageRadius: 4
        DamageBlocks: true
        ExplosionRadius: 1
        Range: 20
        FireTicks: 0
