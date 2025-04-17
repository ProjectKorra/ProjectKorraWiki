.. quickstrike:
################
QUICKSTRIKE
################

Description
###########

**Element:** Chi

QuickStrike is a swift and powerful chi ability that allows the user to deliver a fast, precise strike to an opponent. The speed of the strike makes it difficult to avoid or block, allowing the user to land a quick blow and potentially interrupt the enemy's actions or abilities.

Usage
#####

**Function 1:** Sneak to prepare for the strike, focusing chi into your hands  
**Function 2:** Left-click to perform a rapid strike toward a target, dealing damage and potentially stunning them for a brief period  
**Function 3:** The target remains stunned for a short duration, preventing them from moving or using abilities

.. tip:: QuickStrike is perfect for catching opponents off guard or interrupting their abilities. Use it to disable benders before they can react!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+------------------------------+---------+
| Permission                          | Function                     | Default |
+-------------------------------------+------------------------------+---------+
| bending.ability.quickstrike         | Access to QuickStrike ability| true    |
+-------------------------------------+------------------------------+---------+

Configuration
#############

.. code:: YAML

    QuickStrike:
      Enabled: true
      Damage: 2
      Cooldown: 3000
      ChiBlockChance: 10