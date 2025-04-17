.. paralyze:
############
PARALYZE
############

Description
###########

**Element:** Chi

Paralyze is a chi-blocking ability that allows the user to temporarily freeze an opponent’s body, restricting their movements and preventing them from using their bending abilities. The user targets a specific enemy, channeling chi into them to disrupt their flow of energy and induce a state of immobility.

Usage
#####

**Function 1:** Sneak to charge the ability and lock onto an enemy  
**Function 2:** Left-click to release the paralyzing chi, freezing the enemy in place  
**Function 3:** The target remains paralyzed for a short duration, unable to move or use bending abilities

.. tip:: Use Paralyze to disable powerful opponents or stop enemies from escaping. Timing is key to preventing a counterattack!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-----------------------------+---------+
| Permission                          | Function                    | Default |
+-------------------------------------+-----------------------------+---------+
| bending.ability.paralyze            | Access to Paralyze ability  | true    |
+-------------------------------------+-----------------------------+---------+

Configuration
#############

.. code:: YAML

    Paralyze:
      Enabled: true
      Cooldown: 10000
      Duration: 1500
