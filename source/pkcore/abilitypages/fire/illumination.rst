.. illumination:
############
ILLUMINATION
############

Description
###########

**Element:** Fire

Illumination is a firebending ability that allows the user to create and control light using flames. By manipulating fire at a low intensity, the user can produce a steady, glowing light source that can brighten dark areas, make signals, or light up the surroundings for exploration or combat advantages. It’s a useful utility skill for both exploration and tactical positioning.

Usage
#####

**Function 1:** Left-click to create a small flame at the tip of your hand or staff, providing light in the immediate area

**Function 2:** Hold sneak and left-click to increase the radius and intensity of the light, illuminating a larger area

**Function 3:** Right-click to extinguish the light and remove any fire-based illumination

.. tip:: Illumination is perfect for lighting up dark environments, signaling allies, or creating distractions in combat. Be careful not to rely on it too much in combat, as it can alert enemies to your presence.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.illumination        | Access to Illumination ability| true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    Illumination:
      Enabled: true
      Passive: true
      Range: 5
      Cooldown: 500
      LightThreshold: 7
      LightLevel: 13
