.. earthblast:
############
EARTHBLAST
############

Description
###########

**Element:** Earth

EarthBlast is a focused, ranged earthbending move that allows the user to launch a projectile of compressed stone toward enemies. The blast can deal significant damage and is useful for long-range combat, offering both offensive power and control over the battlefield.

Usage
#####

**Function 1:** Left-click to launch a single blast of earth at the targeted direction

**Function 2:** Hold sneak and left-click to fire a larger, more powerful blast that affects a wider area

.. tip:: EarthBlast can be used for both offense and strategic positioning. Aim for groups of enemies to maximize damage or to knock back individual targets.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.earthblast          | Access to EarthBlast ability  | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    EarthBlast:
      Enabled: true
      CanHitSelf: false
      SelectRange: 10
      Range: 30
      Speed: 35
      Revert: true
      Damage: 3
      Push: 0.3
      Cooldown: 500
      DeflectRange: 3
      CollisionRadius: 1.5
