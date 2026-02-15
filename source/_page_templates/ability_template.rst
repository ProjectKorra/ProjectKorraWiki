.. ability_template:
############
EXAMPLE
############

Description
###########

**Element:** Insert Element Here

Insert a brief description of the ability here, including its general purpose and how it fits into the element's overall theme.

Usage
#####

**Function 1:** Function 1 description here  
**Function 2:** Function 2 description here  
**Function 3:** Function 3 description here

.. tip:: Insert Tips here i.e Practice makes perfect!

Permissions
###########
Below is a table that outlines the permission nodes for this ability.

+-------------------------------------+------------------------------+---------+
| Permission                          | Function                     | Default |
+-------------------------------------+------------------------------+---------+
| bending.ability.ABILITYNAME         | Access to ABILITYNAME ability| true    |
+-------------------------------------+------------------------------+---------+

Configuration
#############

.. code:: YAML

    ExampleAbility:
      Enabled: true
      Cooldown: 20000
      OtherConfigOption: value