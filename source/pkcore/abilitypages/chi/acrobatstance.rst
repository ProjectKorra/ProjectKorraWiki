.. acrobatstance:
#############
AcrobatStance
#############

Description
###########

AcrobatStance is a Chi Ability.

AcrobatStance gives the Chiblocker a boost in mobility, allowing them to catch fast moving targets. GIF TO BE ADDED


Usage
#####

USAGE GIF TO BE ADDED

Function 1: [Left Click]


.. tip:: AcrobatStance increases your chance to block someones chi!


Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-----------------------------------+---------+
| Permission                          | Function                          | Default |
+-------------------------------------+-----------------------------------+---------+
| bending.ability.AcrobatStance       | Grants access to AcrobatStance    | default |
+-------------------------------------+-----------------------------------+---------+




Configuration
#############

.. code:: YAML

    AcrobatStance:
      Enabled: true
      Cooldown: 0
      ChiBlockBoost: 3
      Speed: 1
      Jump: 1

* ``Enabled`` determines whether the ability is available to use. It takes a boolean value [true/false].
* ``Cooldown`` determines the cooldown of the ability after being used. It takes an integer value and is equivalent to number of milliseconds.
* ``ChiBlockBoost`` determines the percent that AcrobatStance will boost chiblock probability. It takes an integer value from 1-100 is equivalent to percent chance of blocking chi.
* ``Speed`` determines the strength of the speed effect added by AcrobatStance. It takes an integer value and represents the level of the speed effect.    
* ``Jump`` determines the strength of the jump boost effect added by AcrobatStance. It takes an integer value and represents the level of the jump boost effect.    
    
.. |ABILNAMEHERE1| figure: abilnamegif1.png
    :align: right
    :alt: Picture of []
    :figclass: align-center

    Insert caption
    
.. ADD MORE IMAGES BELOW HERE
