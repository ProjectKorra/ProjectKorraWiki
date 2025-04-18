.. suffocate:
############
SUFFOCATE
############

Description
###########

**Element:** Air (Advanced Ability)

Suffocate is a high-level airbending technique that targets an enemy's breath. When used, it lifts the target into the air and surrounds their head with a tight sphere of air, dealing damage over time and immobilizing them. It requires precision and timing, making it a powerful combo finisher or control move.

Usage
#####

**Function 1:** Sneak to begin targeting a nearby entity

**Function 2:** Left-click to activate and lift the target into the air, suffocating them

.. tip:: Best used when your target is isolated or already stunned. You’re vulnerable while channeling, so don’t overcommit!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+--------------------------------+---------+
| Permission                          | Function                       | Default |
+-------------------------------------+--------------------------------+---------+
| bending.ability.suffocate           | Access to Suffocate ability    | false   |
+-------------------------------------+--------------------------------+---------+

Configuration
#############

.. code:: YAML

    Suffocate:
      Enabled: true
      ChargeTime: 500
      Cooldown: 6500
      Range: 20
      Damage: 2
      DamageInitialDelay: 2
      DamageInterval: 1
      SlowPotency: 1
      SlowDelay: 0.5
      SlowInterval: 1.25
      BlindPotentcy: 30
      BlindDelay: 2
      BlindInterval: 1.5
      CanBeUsedOnUndeadMobs: true
      RequireConstantAim: true
      RequireConstantAimRadius: 5
      AnimationRadius: 2.0
      AnimationParticleAmount: 1
      AnimationSpeed: 1.0
