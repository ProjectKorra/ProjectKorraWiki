.. rapidpunch:
###########
RapidPunch
###########

Description
###########

RapidPunch is a Chi Ability.

RapidPunch allows the Chiblocker to punch an opponent multiple times in a short period, dealing massive damage. GIF TO BE ADDED


Usage
#####

USAGE GIF TO BE ADDED

Function 1: [Hit enemy]


.. tip:: RapidPunch is best used when the opponent is paralyzed as each punch has its own chance to block their chi!


Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.RapidPunch          | Grants access to RapidPunch   | default |
+-------------------------------------+-------------------------------+---------+




Configuration
#############

.. code:: YAML

    RapidPunch:
      Enabled: true
      Damage: 1
      Cooldown: 6000
      Punches: 3
      Interval: 500

* ``Enabled`` determines whether the ability is available to use. It takes a boolean value [true/false].
* ``Damage`` determines the amount of damage the ability does, per punch, when used on another entity. It takes any positive integer and is equivalent to number of half hearts of damage.
* ``Cooldown`` determines the cooldown of the ability after being used. It takes an integer value and is equivalent to number of milliseconds.]
* ``Punches`` determines the number of punches to apply to the target entity. It takes an integer value.
* ``Interval`` determines the the time interval in which the punches will occur. It takes an integer value and is equivalent to number of milliseconds.
    
    
.. |ABILNAMEHERE1| figure: abilnamegif1.png
    :align: right
    :alt: Picture of []
    :figclass: align-center

    Insert caption
    
.. ADD MORE IMAGES BELOW HERE
