.. highjump:
#############
HIGHJUMP
#############

Description
###########

**Element:** Chi

HighJump is a chi ability that enhances the user's jumping capability, allowing them to leap great distances and reach higher elevations than usual. This ability is particularly useful for evading attacks or closing the distance quickly during combat.

Usage
#####

**Function 1:** Sneak to prepare your chi energy for the jump  
**Function 2:** Left-click to leap into the air, significantly increasing jump height and distance  
**Function 3:** The ability can be used multiple times in a row, but each jump requires a short cooldown period

.. tip:: HighJump can be a great tool for both offense and defense. Use it to surprise enemies from above or escape difficult situations!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-----------------------------+---------+
| Permission                          | Function                    | Default |
+-------------------------------------+-----------------------------+---------+
| bending.ability.highjump            | Access to HighJump ability  | true    |
+-------------------------------------+-----------------------------+---------+

Configuration
#############

.. code:: YAML

    HighJump:
      Enabled: true
      Height: 1.3
      Cooldown: 3000
