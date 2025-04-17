.. fireburst:
############
FIREBURST
############

Description
###########

**Element:** Fire

FireBurst is an explosive firebending move that creates a sudden burst of flames around the user. This move releases a concentrated burst of fire in all directions, dealing significant damage to enemies and knocking them back. It’s an excellent ability for crowd control or escaping tight situations by pushing away surrounding enemies.

Usage
#####

**Function 1:** Left-click to unleash a burst of fire, damaging and knocking back nearby enemies

**Function 2:** Hold sneak and left-click to increase the damage and radius of the burst, making it more powerful and affecting a larger area

.. tip:: FireBurst is perfect for disrupting groups of enemies or creating space between you and your opponents. Be mindful of your surroundings when using it, as it can damage allies or cause environmental hazards.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.fireburst           | Access to FireBurst ability   | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    FireBurst:
      Enabled: true
      Damage: 2
      Ignite: true
      ChargeTime: 3500
      Cooldown: 0
      Range: 14
      AnglePhi: 10
      AngleTheta: 10
      ParticlesPercentage: 5
