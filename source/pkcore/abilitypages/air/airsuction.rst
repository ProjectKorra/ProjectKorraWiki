.. airsuction:
############
AIRSUCTION
############

Description
###########

**Element:** Air

AirSuction creates a vacuum of air in front of the user, pulling entities and projectiles toward a targeted location. It's useful for disrupting enemy positioning and manipulating the battlefield by dragging opponents toward you.

Usage
#####

**Function 1:** Click to pull entities toward your cursor location

**Function 2:** Hold sneak to repeatedly pull entities (if enabled in config)

.. tip:: Use AirSuction to pull enemies off ledges or into combos with other air abilities like AirSwipe!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+---------------------------------------+-------------------------------+---------+
| Permission                            | Function                      | Default |
+---------------------------------------+-------------------------------+---------+
| bending.ability.airsuction            | Access to AirSuction ability  | true    |
+---------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    AirSuction:
      Enabled: true
      Speed: 25
      Range: 20
      SelectRange: 10
      Radius: 0.5
      Push:
        Self: 2.0
        Others: 1.3
      Cooldown: 500
      Particles: 6
      SelectParticles: 6
