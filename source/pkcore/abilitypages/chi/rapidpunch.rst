.. rapidpunch:
################
RAPIDPUNCH
################

Description
###########

**Element:** Chi

RapidPunch is a fast and relentless chi ability that allows the user to deliver a series of quick, high-speed punches infused with chi energy. These punches deal moderate damage and are designed to overwhelm opponents with speed and precision, making it difficult for them to retaliate.

Usage
#####

**Function 1:** Sneak to charge up chi energy in your fists  
**Function 2:** Left-click to release a rapid barrage of punches, each dealing moderate damage  
**Function 3:** The punches continue for a short duration or until the user stops attacking

.. tip:: RapidPunch is effective for disrupting enemies and dealing continuous damage. Use it to keep pressure on opponents and prevent them from reacting!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-----------------------------+---------+
| Permission                          | Function                    | Default |
+-------------------------------------+-----------------------------+---------+
| bending.ability.rapidpunch          | Access to RapidPunch ability| true    |
+-------------------------------------+-----------------------------+---------+

Configuration
#############

.. code:: YAML

    RapidPunch:
      Enabled: true
      Damage: 1
      Cooldown: 6000
      Punches: 3
      Interval: 500
