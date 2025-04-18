.. watermanipulation:
#######################
WATERMANIPULATION
#######################

Description
###########

**Element:** Water

WaterManipulation is a core waterbending ability that allows the user to bend a stream of water from a source block and launch it at enemies. It’s fast, precise, and effective as both an offensive and tactical move. This ability can deal damage, knock back targets, and even freeze depending on conditions or combo usage.

Usage
#####

**Function 1:** Sneak to select a water source within range and begin drawing water toward you

**Function 2:** Left-click to launch the stream of water at your target, dealing damage and knockback

**Function 3:** (Optional) If configured, the stream may freeze on contact or push entities depending on the setting

.. tip:: Master this ability to quickly follow up with combos. It’s great for pressuring enemies or knocking them into hazards.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+----------------------------------------------+-------------------------------+---------+
| Permission                                   | Function                      | Default |
+----------------------------------------------+-------------------------------+---------+
| bending.ability.watermanipulation            | Access to WaterManipulation   | true    |
+----------------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    WaterManipulation:
      Enabled: true
      Damage: 3.0
      Range: 25
      SelectRange: 16
      CollisionRadius: 1.0
      DeflectRange: 3
      Speed: 35
      Knockback: 0.3
      Cooldown: 1000
