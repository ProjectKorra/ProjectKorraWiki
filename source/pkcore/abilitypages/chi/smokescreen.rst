.. smokescreen:
################
SMOKESCREEN
################

Description
###########

**Element:** Chi

Smokescreen is a defensive chi ability that allows the user to create a thick cloud of smoke, disorienting opponents and obscuring vision. While the smokescreen is active, the user can move freely and use their abilities without being seen, making it a powerful tool for escape or surprise attacks.

Usage
#####

**Function 1:** Sneak to prepare the smokescreen  
**Function 2:** Left-click to release a dense cloud of smoke that covers a large area around the user  
**Function 3:** While in the smokescreen, the user can remain hidden, and opponents will have reduced vision

.. tip:: Smokescreen is ideal for quick escapes or to blind enemies during a fight. Combine with offensive chi abilities to confuse opponents.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-----------------------------+---------+
| Permission                          | Function                    | Default |
+-------------------------------------+-----------------------------+---------+
| bending.ability.smokescreen          | Access to Smokescreen ability| true    |
+-------------------------------------+-----------------------------+---------+

Configuration
#############

.. code:: YAML

    Smokescreen:
      Enabled: true
      Cooldown: 25000
      Radius: 4
      Duration: 12
