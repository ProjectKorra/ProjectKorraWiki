.. highjump:
###########
HighJump
###########

Description
###########

HighJump is a Chi Ability.

HighJump allows the Chiblocker to launch themselves high in the air, letting them dodge and surpass obstacles.


Usage
#####

USAGE GIF TO BE ADDED

Function 1: [Left Click]


.. tip:: Be cautious of when you HighJump, it gives benders a prime opportunity to strike you.


Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.HighJump            | Grants access to HighJump     | default |
+-------------------------------------+-------------------------------+---------+




Configuration
#############

.. code:: YAML

  HighJump:
      Enabled: true
      Height: 1.3
      Cooldown: 3000

* ``Enabled`` determines whether the ability is available to use. It takes a boolean value [true/false].
* ``Height`` determines how far you will be launched into the air. It takes a double [decimal] value and is equivalent to a multiplier for the launch velocity.
* ``Cooldown`` determines the cooldown of the ability after being used. It takes an integer value and is equivalent to number of milliseconds.
    
    
.. |ABILNAMEHERE1| figure: abilnamegif1.png
    :align: right
    :alt: Picture of []
    :figclass: align-center

    Insert caption
    
.. ADD MORE IMAGES BELOW HERE
