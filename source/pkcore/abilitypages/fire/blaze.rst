.. blaze:
############
BLAZE
############

Description
###########

**Element:** Fire

Blaze is a fiery offensive ability that allows the user to summon intense flames that deal significant damage over time to enemies within its radius. The user can control the direction and spread of the fire, making it effective for dealing with groups of enemies or blocking paths. Blaze is perfect for aggressive firebenders who want to overwhelm their opponents with continuous damage.

Usage
#####

**Function 1:** Left-click to release a concentrated burst of flame, dealing damage to enemies in a small radius

**Function 2:** Hold sneak and left-click to create a larger, spreading flame that affects a wider area and lasts longer

**Function 3:** Right-click to ignite the ground beneath your enemies, causing continuous fire damage as they stand within the flames

.. tip:: Blaze is highly effective for area denial and dealing persistent damage to enemies who are trapped or chasing you. Use it to create a deadly barrier or control key locations.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.blaze               | Access to Blaze ability       | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    Blaze:
      Enabled: true
      Arc: 14
      Range: 7
      Speed: 15
      Cooldown: 500
      Ring:
        Range: 7
        Angle: 10
        Cooldown: 1000
