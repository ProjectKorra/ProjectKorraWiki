.. airburst:
############
AIRBURST
############

Description
###########

**Element:** Air

Unleash a massive burst of air around you, damaging and knocking back nearby enemies. AirBurst is an advanced move that can be triggered instantly or charged for greater effect.

Usage
#####

**Function 1:** Sneak then Release Sneak (while in mid-air)

**Function 2:** Sneak to charge, then Release Sneak

.. tip:: Practice makes perfect! AirBurst is great for crowd control and breaking up group fights. Try using it when surrounded.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-----------------------------+---------+
| Permission                          | Function                    | Default |
+-------------------------------------+-----------------------------+---------+
| bending.ability.airburst            | Access to AirBurst ability  | true    |
+-------------------------------------+-----------------------------+---------+
| bending.ability.airburst.instant    | Use instant AirBurst        | true    |
+-------------------------------------+-----------------------------+---------+
| bending.ability.airburst.charged    | Use charged AirBurst        | true    |
+-------------------------------------+-----------------------------+---------+

Configuration
#############

.. code:: YAML

    AirBurst:
      Enabled: true
      FallThreshold: 10
      PushFactor: 2.8
      ChargeTime: 1750
      Damage: 0
      Cooldown: 0
      SneakParticles: 10
      ParticlePercentage: 50
      AnglePhi: 10
      AngleTheta: 10
