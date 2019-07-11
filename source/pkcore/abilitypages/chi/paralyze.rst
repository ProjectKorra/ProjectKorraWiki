.. paralyze:
############
Paralyze
############

Description
###########

Paralyze is a Chi Ability.
Paralyze allows the Chiblocker to paralyze entities for a short time period. GIF 


Usage
#####

GIF TO BE ADDED

Function 1: [Left Click] the target entity 


.. tip:: After using Paralyze, be sure to follow up with your other abilities!


Permissions
###########
Below is a table that outlines the permission nodes for this ability.


+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.Paralyze            | Grants access to Paralyze     | default |
+-------------------------------------+-------------------------------+---------+




Configuration
#############

.. code:: YAML

     Paralyze:
      Enabled: true
      Cooldown: 10000
      Duration: 1500
      
* ``Enabled`` determines whether the ability is available to use. It takes a boolean value [true/false].
* ``Cooldown`` determines the cooldown of the ability after being used. It takes an integer value and is equivalent to number of milliseconds.
* ``Duration`` determines how long the ability remains active. It takes an integer value and is equivalent to number of milliseconds.    
    
.. |ABILNAMEHERE1| figure: abilnamegif1.png
    :align: right
    :alt: Picture of []
    :figclass: align-center

    Insert caption
    
.. ADD MORE IMAGES BELOW HERE
