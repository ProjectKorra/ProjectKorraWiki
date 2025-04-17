.. torrent:
############
TORRENT
############

Description
###########

**Element:** Water

Torrent is a powerful waterbending ability that allows the user to gather and manipulate a large stream of water, which can be launched at enemies with immense force. The ability is highly versatile—capable of being used defensively to block attacks, or offensively to knock back and damage opponents. It requires a water source to initiate.

Usage
#####

**Function 1:** Hold sneak to gather water from a source into a swirling stream around the user

**Function 2:** Release sneak to launch the torrent forward, dealing damage and knocking back any targets in its path

**Function 3:** Aim the torrent to wrap around the user as a water shield before launching it in any direction

.. tip:: Practice timing your sneak and release to maximize control of the torrent. Great for crowd control and turning defense into offense.

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+------------------------------+---------+
| Permission                          | Function                     | Default |
+-------------------------------------+------------------------------+---------+
| bending.ability.torrent             | Access to Torrent ability    | true    |
+-------------------------------------+------------------------------+---------+

Configuration
#############

.. code:: YAML

    Torrent:
      Enabled: true
      Range: 25
      SelectRange: 16
      InitialDamage: 3
      DeflectDamage: 1
      SuccessiveDamage: 1
      MaxLayer: 3
      MaxHits: 2
      Knockback: 1
      Angle: 20
      Radius: 3
      Knockup: 0.2
      Interval: 30
      Cooldown: 0
      ChargeTimeout: 0
      Revert: true
      RevertTime: 60000
      Wave:
        Radius: 12
        Knockback: 1.5
        Height: 1
        GrowSpeed: 0.5
        Interval: 30
        Cooldown: 0