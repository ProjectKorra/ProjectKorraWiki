.. surge:
############
SURGE
############

Description
###########

**Element:** Water  
**Subelement:** Ice

Surge is a dynamic waterbending ability that allows the user to manipulate water in two primary forms: as a high-pressure blast or as a protective wall. Depending on how the ability is used, Surge can deal damage and knockback enemies or defend against incoming attacks. The blast can also freeze on contact, making this ability versatile for both offense and defense.

Usage
#####

**Function 1:** Left-click to launch a surge of water forward, damaging and knocking back enemies  
**Function 2:** Hold sneak to form a temporary wall of water in front of the user, blocking projectiles and attacks  
**Function 3:** If the water blast hits a surface or enemy, it can freeze and trap them briefly

.. tip:: Use the wall to block arrows or fire blasts, then counterattack with a frozen surge for crowd control!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+------------------------------+---------+
| Permission                          | Function                     | Default |
+-------------------------------------+------------------------------+---------+
| bending.ability.surge               | Access to Surge ability      | true    |
+-------------------------------------+------------------------------+---------+

Configuration
#############

.. code:: YAML

    Surge:
      Enabled: true
      Wave:
        Radius: 3
        Range: 20
        SelectRange: 12
        Knockback: 1
        Knockup: 0.2
        MaxFreezeRadius: 7
        Cooldown: 500
        Interval: 30
        SolidifyLava:
          Enabled: true
          Duration: 36000
        IceRevertTime: 60000
      Wall:
        Range: 5
        SelectRange: 5
        Radius: 2
        Cooldown: 0
        Duration: 0
        Interval: 30
        SolidifyLava:
          Enabled: true
          Duration: 36000
