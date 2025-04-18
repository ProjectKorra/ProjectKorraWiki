.. airswipe:
############
AIRSWIPE
############

Description
###########

**Element:** Air

AirSwipe creates a fast-moving, crescent-shaped blade of air that travels forward, damaging and knocking back enemies in its path. It can also extinguish flames and break certain projectiles, making it both offensive and utility-based.

Usage
#####

**Function 1:** Left-click to launch a swipe of air in the direction you're facing

**Function 2:** Hold sneak and then left-click for a wider arc (if configured)

.. tip:: AirSwipe is a great all-around move — use it for offense, defense, and utility. Try using it to cancel incoming fire blasts or hit multiple enemies at once!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-----------------------------+---------+
| Permission                          | Function                    | Default |
+-------------------------------------+-----------------------------+---------+
| bending.ability.airswipe            | Access to AirSwipe ability  | true    |
+-------------------------------------+-----------------------------+---------+

Configuration
#############

.. code:: YAML

    AirSwipe:
      Enabled: true
      Damage: 2
      Range: 14
      Radius: 0.5
      Push: 0.5
      Arc: 16
      Speed: 25
      Cooldown: 1500
      ChargeFactor: 3
      MaxChargeTime: 2500
      Particles: 3
      StepSize: 4
