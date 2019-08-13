.. quickstrike:
###########
QuickStrike
###########

Description
###########

QuickStrike is a Chi Ability.

QuickStrike allows Chiblockers to quickly strike an enemy's chi paths, dealing increased damage, and resulting in a greater chance to block their chi. GIF TO BE ADDED


Usage
#####

USAGE GIF TO BE ADDED

Function 1: [Hit Enemy]

.. tip:: QuickStrike can block bending for short amount of time!

When hit with QuickStrike, the enemy will potentially be chi blocked, and will have been dealt damage as determined by the configuration.


Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+-------------------------------+---------+
| Permission                          | Function                      | Default |
+-------------------------------------+-------------------------------+---------+
| bending.ability.QuickStrike         | Grants access to QuickStrike  | default |
+-------------------------------------+-------------------------------+---------+




Configuration
#############

.. code:: YAML

     QuickStrike:
      Enabled: true
      Damage: 2
      Cooldown: 3000
      ChiBlockChance: 10

* ``Enabled`` determines whether the ability is available to use. It takes a boolean value [true/false].
* ``Damage`` determines the amount of damage the ability does when used on another entity. It takes any positive integer and is equivalent to number of half hearts of damage.
* ``Cooldown`` determines the cooldown of the ability after being used. It takes an integer value and is equivalent to number of milliseconds.
* ``ChiBlockChance`` determines the probability that QuickStrike will chiblock a bender. It takes an integer value from 1-100 is equivalent to percent increase of blocking chi.
    
    
.. |ABILNAMEHERE1| figure: abilnamegif1.png
    :align: right
    :alt: Picture of []
    :figclass: align-center

    Insert caption
    
.. ADD MORE IMAGES BELOW HERE
