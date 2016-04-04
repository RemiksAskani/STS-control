### Character skills 

_These are basic skills for all templates. New or different skills can be added by Storytellers or players based on the character creation process. Skills have a value that goes from 0 to 5, 0 being completely untrained, and 5 meaining the character excels at the specific skill. There are also specialties, which needs to be considered when storing values. Specialties may be something like: Academis (3): Literature_.

1. Mental Skills
  * Academics
  * Computer
  * Crafts
  * Investigation
  * Medicine
  * Occult
  * Politics
  * Science
2. Physical Skills
  * Athletics
  * Brawl
  * Drive
  * Firearms
  * Larceny
  * Stealth
  * Survival
  * Weaponry
3. Social Skills
  * Animal Ken
  * Empathy
  * Expression
  * Intimidation
  * Persuasion
  * Socialize
  * Streetwise
  * Subterfuge

==

## Tables design

_skillClass_

**skill_class_id** | skill_class_name
------------------ | ----------------
char(32)           | text

_skill_

**skill_id** | skill_name | *skill_class*
------------ | ---------- | -------------
char(32)     | text       | char(32)    
