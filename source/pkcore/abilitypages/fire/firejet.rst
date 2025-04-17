.. firejet:
############
FIREJET
############

Description
###########

**Element:** Fire

FireJet is a firebending ability that allows the user to propel themselves through the air using bursts of flame. This move allows for quick vertical and horizontal movement, creating a jet of fire beneath the user that provides short bursts of speed. It’s ideal for escaping danger or reaching high places with speed and agility.

Usage
#####

**Function 1:** Left-click to shoot a burst of flame beneath you, propelling you upward into the air

**Function 2:** Hold sneak and left-click to adjust the intensity of the jet, allowing for controlled upward and horizontal movement

**Function 3:** Right-click to activate a downward burst, allowing for a controlled landing or a quick descent

.. tip:: FireJet is great for both offense and evasion. Use it to gain a high vantage point or quickly escape combat situations. Be mindful of your fuel, as the ability consumes energy.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.firejet             | Access to FireJet ability     | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    FireJet:
      Enabled: true
      Speed: 0.8
      Duration: 2000
      Cooldown: 7000
      ShowGliding: false
