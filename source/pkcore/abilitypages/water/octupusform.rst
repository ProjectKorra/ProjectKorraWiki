.. octupusform:
################
OCTOPUSFORM
################

Description
###########

**Element:** Water

OctopusForm is a defensive and offensive waterbending ability that allows the user to create multiple water tentacles that revolve around them. These tentacles can be used to strike nearby enemies, knock them back, and provide a rotating defense. It excels in close combat and crowd control, especially when surrounded.

Usage
#####

**Function 1:** Sneak near a water source to form revolving tentacles made of water

**Function 2:** Maintain sneak to keep the form active—tentacles will damage and knock back nearby entities

**Function 3:** Look toward an enemy and click to extend a tentacle in that direction, hitting or pushing the target

.. tip:: OctopusForm is ideal when outnumbered—stand your ground and let the tentacles protect you!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+------------------------------------------+----------------------------------+---------+
| Permission                               | Function                         | Default |
+------------------------------------------+----------------------------------+---------+
| bending.ability.octupusform              | Access to OctopusForm ability    | true    |
+------------------------------------------+----------------------------------+---------+

Configuration
#############

.. code:: YAML

    OctopusForm:
      Enabled: true
      Range: 10
      AttackRange: 2.5
      Radius: 3
      Damage: 2
      Knockback: 1.75
      FormDelay: 40
      Cooldown: 0
      Duration: 0
      UsageCooldown: 0
      AngleIncrement: 45
