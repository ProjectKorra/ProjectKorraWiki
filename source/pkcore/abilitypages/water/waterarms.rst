.. waterarms:
############
WATERARMS
############

Description
###########

**Element:** Water

WaterArms is a waterbending technique that allows the user to extend their bending prowess by manifesting multiple fluid, flexible arms. These arms can be used for offensive strikes, grabbing enemies, or manipulating objects at a distance, providing enhanced control during combat and utility situations.

Usage
#####

**Function 1:** Sneak near a water source to summon water arms that extend from the user  
**Function 2:** Left-click to lash out with a water arm, delivering a strike or push to an enemy  
**Function 3:** Aim and click to grab or manipulate objects with the water arms, controlling enemy movement or interacting with the environment

.. tip:: WaterArms offer a unique way to increase your reach and versatility in combat. Practice using them in different scenarios to master both offensive and defensive maneuvers.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+--------------------------------------+---------+
| Permission                          | Function                             | Default |
+-------------------------------------+--------------------------------------+---------+
| bending.ability.waterarms           | Access to WaterArms ability          | true    |
+-------------------------------------+--------------------------------------+---------+

Configuration
#############

.. code:: YAML

    WaterArms:
      Enabled: true
      DisplayBoundMsg: false
      Arms:
        InitialLength: 4
        SourceGrabRange: 12
        MaxAttacks: 10
        MaxAlternateUsage: 50
        MaxIceShots: 8
        Cooldown: 20000
        AllowPlantSource: true
        Lightning:
          Enabled: true
          Damage: 10.0
          KillUser: false
        Cooldowns:
          UsageCooldown:
            Enabled: false
            Pull: 200
            Punch: 200
            Grapple: 200
            Grab: 200
            Freeze: 200
            Spear: 200
      Whip:
        MaxLength: 12
        MaxLengthWeak: 8
        NightAugments:
          MaxLength:
            Normal: 16
            FullMoon: 20
        Pull:
          Multiplier: 0.15
        Punch:
          Damage: 0.5
          MaxLength: 8
          NightAugments:
            MaxLength:
              Normal: 11
              FullMoon: 13
        Grapple:
          RespectRegions: false
        Grab:
          Duration: 3500
      Freeze:
        Range: 20
        Damage: 2
      Spear:
        Range: 30
        Damage: 3
        DamageEnabled: true
        SphereRadius: 2
        Duration: 4500
        Length: 18
        NightAugments:
          Range:
            Normal: 45
            FullMoon: 60
          Sphere:
            Normal: 3
            FullMoon: 6
          Duration:
            Normal: 7000
            FullMoon: 12000
