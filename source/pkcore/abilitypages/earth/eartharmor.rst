.. eartharmor:
############
EARTHARMOR
############

Description
###########

**Element:** Earth

EarthArmor is a defensive ability that encases the user in a layer of hardened earth, providing enhanced protection against attacks. The armor absorbs damage and increases resistance to physical hits, but it also slows down movement, making it a trade-off between defense and mobility.

Usage
#####

**Function 1:** Sneak to activate EarthArmor, encasing yourself in a protective layer of earth

**Function 2:** Hold sneak to maintain the armor and absorb damage

.. tip:: EarthArmor is excellent for tanking hits from strong opponents, but you’re less mobile while using it. Consider using it when you need to withstand large amounts of damage.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-----------------------------+---------+
| Permission                          | Function                    | Default |
+-------------------------------------+-----------------------------+---------+
| bending.ability.eartharmor          | Access to EarthArmor ability| true    |
+-------------------------------------+-----------------------------+---------+

Configuration
#############

.. code:: YAML

    EarthArmor:
      Enabled: true
      SelectRange: 10
      GoldHearts: 4
      Cooldown: 7500
      MaxDuration: 17500
