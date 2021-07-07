.. swiftkick:
############
SwiftKick
############

Description
###########

SwiftKick is a Chi ability.

SwiftKick allows a chiblocker to deal a powerful kick to an enemy for larger damage and a greater chance of blocking their chi. GIF TO BE ADDED


Usage
#####

USAGE GIF TO BE ADDED 

Function 1: [Left Click] the target entity while midair.




.. tip:: Use this with QuickStrike to increase the chance of blocking your opponent's chi!


Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+----------------------------+---------+
| Permission                          | Function                   | Default |
+-------------------------------------+----------------------------+---------+
| bending.ability.SwiftKick           | Grants access to SwiftKick | default |
+-------------------------------------+----------------------------+---------+




Configuration
#############

.. code:: YAML

     SwiftKick:
      Enabled: true
      Damage: 2
      ChiBlockChance: 15
      Cooldown: 4000

* ``Enabled`` determines whether the ability is available to use. It takes a boolean value [true/false].
* ``Damage`` determines the amount of damage the ability does when used on another entity. It takes any positive integer and is equivalent to number of half hearts of damage.
* ``Cooldown`` determines the cooldown of the ability after being used. It takes an integer value and is equivalent to number of milliseconds.
* ``ChiBlockChance`` determines the probability that SwiftKick will chiblock a bender. It takes an integer value from 1-100 is equivalent to additional percent of blocking chi based on ChiPassive.    
    
.. |swiftkick1| figure: swiftkick1.png
    :align: right
    :alt: Picture of []
    :figclass: align-center

    Insert caption
    
.. ADD MORE IMAGES BELOW HERE
