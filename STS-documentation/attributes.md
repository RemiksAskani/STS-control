### Character attributes (same for all templates)s

_Attributes have a minimum value of 1 (unless strictly specified by another trait or template)_.

1. Physical attributes:
 * Strength
 * Dexterity
 * Stamina
2. Mental attributes:
 * Intelligence
 * Wits
 * Resolve
3. Social attributes:
 * Presence
 * Manipulation
 * Composure

==

## Tables design

_attributeClass_

**attribute_class_id** | attribute_class_name
---------------------- | --------------------
char(32)               | text

_attribute_

**attribute_id** | attribute_name | *attribute_class*
---------------- | -------------- | -----------------
char(32)         | text           | char(32)
