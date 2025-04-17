.. waterspout:
############
WATERSPOUT
############

Description
###########

**Element:** Water

WaterSpout is a mobility-focused waterbending ability that allows the user to ride atop a column of water, elevating them above the ground. This is ideal for reaching high places, gaining tactical advantages in combat, or simply traversing difficult terrain. While on a spout, the user can continue bending and performing other actions.

Usage
#####

**Function 1:** Sneak to summon a vertical spout of water beneath you, lifting you into the air

**Function 2:** Move around while on the spout to hover over terrain and obstacles

**Function 3:** Stop sneaking or move off the spout to descend and deactivate the ability

.. tip:: WaterSpout is excellent for mobility and avoiding melee combat. Combine it with ranged bending abilities for best results.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.waterspout          | Access to WaterSpout ability  | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    WaterSpout:
      Enabled: true
      Cooldown: 0
      Duration: 0
      Height: 16
      Interval: 50
      BlockSpiral: true
      Particles: false
      SpoutHop:
        Enabled: true
        Power: 0.85
        Cooldown: 0
      Wave:
        Particles: false
        Enabled: true
        AllowPlantSource: true
        Radius: 3.8
        WaveRadius: 1.5
        SelectRange: 6
        AnimationSpeed: 1.2
        ChargeTime: 500
        FlightDuration: 2500
        Speed: 1.3
        Cooldown: 6000
        TrailRevertTime: 1000

