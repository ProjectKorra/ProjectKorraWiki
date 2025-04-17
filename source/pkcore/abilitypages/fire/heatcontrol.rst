.. heatcontrol:
############
HEATCONTROL
############

Description
###########

**Element:** Fire

HeatControl is a firebending ability that allows the user to manipulate the temperature of their surroundings. By increasing or decreasing the heat, the user can either scorch enemies with intense heat or cool down an area to suppress flames and protect allies. This ability gives the user significant control over the environment, making it highly versatile for both combat and utility.

Usage
#####

**Function 1:** Left-click to increase the temperature in a targeted area, causing damage over time to enemies within it

**Function 2:** Hold sneak and left-click to lower the temperature, extinguishing fires or cooling down an area

**Function 3:** Right-click to stabilize the temperature, preventing any heat or cold effects in the area

.. tip:: HeatControl can be used to disrupt enemies or protect yourself and your allies by controlling the battlefield’s temperature. Use it wisely, as extreme temperature changes can affect the environment and mobs.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.heatcontrol         | Access to HeatControl ability | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    HeatControl:
      Enabled: true
      Cook:
        Interval: 1000
      Extinguish:
        Cooldown: 5000
        Radius: 6
      Melt:
        Range: 15
        Radius: 5
      Solidify:
        MaxRadius: 10
        Range: 7
        Revert: true
        RevertTime: 120000