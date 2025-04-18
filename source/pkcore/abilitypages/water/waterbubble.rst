.. waterbubble:
###############
WATERBUBBLE
###############

Description
###########

**Element:** Water

WaterBubble is a utility waterbending ability that allows the user to create a breathable bubble of water around their head while underwater. This grants the user temporary underwater breathing, perfect for exploration, stealth, or escaping danger in aquatic environments. The bubble is purely functional and does not offer offensive or defensive capabilities.

Usage
#####

**Function 1:** Sneak while underwater to form a water bubble around your head, granting temporary breathing

**Function 2:** Remain still to maintain the bubble and conserve duration

**Function 3:** Move freely underwater with the bubble active, but movement and time will drain its duration faster

.. tip:: Perfect for underwater builds, treasure hunts, or escaping drowning. Pair with water mobility abilities for extended exploration!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+----------------------------------------+-------------------------------+---------+
| Permission                             | Function                      | Default |
+----------------------------------------+-------------------------------+---------+
| bending.ability.waterbubble            | Access to WaterBubble ability | true    |
+----------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    WaterBubble:
      Enabled: true
      Cooldown:
        Shift: 0
        Click: 0
      Radius: 4.0
      Speed: 0.5
      ClickDuration: 2000
      MustStartAboveWater: false
