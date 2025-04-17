.. swiftkick:
############
SWIFTKICK
############

Description
###########

**Element:** Chi

SwiftKick is a fast-paced chi-blocking move that allows the user to dash forward and deliver a quick, precise kick. While it doesn't deal high damage, it excels at disabling bending abilities temporarily, making it a key technique for interrupting and controlling opponents in battle.

Usage
#####

**Function 1:** Sneak to prepare your strike  
**Function 2:** Left-click to dash forward and deliver a chi-infused kick  
**Function 3:** If landed, disables the target's bending abilities for a short time

.. tip:: Perfect for initiating fights or interrupting enemy combos. Combine with other chi-blocking moves to shut down powerful benders.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+------------------------------+---------+
| Permission                          | Function                     | Default |
+-------------------------------------+------------------------------+---------+
| bending.ability.swiftkick           | Access to SwiftKick ability  | true    |
+-------------------------------------+------------------------------+---------+

Configuration
#############

.. code:: YAML

    SwiftKick:
      Enabled: true
      Damage: 2
      ChiBlockChance: 15
      Cooldown: 4000
