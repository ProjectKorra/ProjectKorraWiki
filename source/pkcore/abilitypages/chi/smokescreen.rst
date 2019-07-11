.. smokescreen:
###########
SmokeScreen
###########

Description
###########

SmokeScreen is a Chi Ability.

SmokeScreen enables a chiblocker to blind their enemies, allowing for a quick escape or an unseen approach. GIF TO BE ADDED


Usage
#####

USAGE GIF TO BE ADDED

Function 1: [Left Click] to launch a smokebomb in your desired direction.


.. tip:: Be careful not to blind yourself with SmokeScreen!


Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.SmokeScreen         | Grants access to SmokeScreen  | default |
+-------------------------------------+-------------------------------+---------+




Configuration
#############

.. code:: YAML

    Smokescreen:
      Enabled: true
      Cooldown: 25000
      Radius: 4
      Duration: 12

* ``Enabled`` determines whether the ability is available to use. It takes a boolean value [true/false].
* ``Cooldown`` determines the cooldown of the ability after being used. It takes an integer value and is equivalent to number of milliseconds.
* ``Radius`` determines the radius in which the blindness effect is applied. It takes an integer value and represents radius in blocks.
* ``Duration`` determines the length of the blindness effect applied to entities. It takes an integer value and represents duration in seconds.
    
.. |ABILNAMEHERE1| figure: abilnamegif1.png
    :align: right
    :alt: Picture of []
    :figclass: align-center

    Insert caption
    
.. ADD MORE IMAGES BELOW HERE
