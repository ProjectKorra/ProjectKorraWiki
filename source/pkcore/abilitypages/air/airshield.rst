.. airshield:
############
AIRSHIELD
############

Description
###########

**Element:** Air

AirShield creates a protective barrier of swirling air around the user, blocking incoming projectiles and pushing away nearby entities. It's a defensive move that provides temporary safety while still allowing limited movement.

Usage
#####

**Function 1:** Sneak to activate and maintain a rotating shield of air

**Function 2:** Move slowly while sneaking to carry the shield with you

.. tip:: Use AirShield to block incoming arrows, fire blasts, or other ranged attacks while closing the gap or escaping. Time your movements carefully!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.airshield           | Access to AirShield ability   | true    |
+-------------------------------------+-------------------------------+---------+

Configuration
#############

.. code:: YAML

    AirShield:
      Enabled: true
      Cooldown: 0
      Duration: 0
      MaxRadius: 7
      InitialRadius: 1
      Streams: 5
      Speed: 10
      Push: 0.5
      Particles: 5
      DynamicCooldown: false