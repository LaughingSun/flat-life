
flatlife
========

A 2D life simulator involving multi-sided shapes that move around, Foraging for 
resources, breeding, interaction, form relationships, and try to survive.  
Species are based on their number of sides.  Every species can have different 
races which are the coloring.  Race plays a role in their interaction and 
formign relationships, but not for breeding although individuals are more 
likely to breed with others that they have formed a relationship with, but 
since proximity and availibility play a role in all of the above it is still 
fairly random.

Movement
========
Flatlife can move at angle angle that is a multiple of 360 degrees divided by 
the number of sides. Flatlife will not move if it is contented, that is has no 
requirements.  Requirements can include need for foods, breeding, socializing 
and space.

Foraging for resources
======================
Flatlife require nutrients such as: water, fruit, green and rooty vegetables, 
grain, beans and fungus. Based of species the consumables will include the 
number of sides of the above list.  FE 3 sided will be able to consume water, 
fruit and greens. For species with more than 7 sides they will require twice 
as many and the modulos of their number of sides.

Breeding
========
Species are defined by the number of sides.  Difference species can not breed.
Flatlife of the same species can breed regardless of color(s).  When flatlife 
breeds the incubator(female) will have a single offspring on an open side.  
Not all species have set genders. Species with an odd number of sides will 
have a gender identity which can still change under certain circumstances.  
For species with gender identity, changing gender requires the number of sides 
to change.  For species with no gender identity there will be no offspring if 
either dominance or availability is equal.  If there is no space for offspring 
then none will be produced.  Gender identity is simply 2 roles, either Seed or 
Host.

SIDES IDENTITY  CHANGABLE
   3  no        availability/no
   4  yes       dominance
   5  no        availability/no
   6  yes       no
   7  no        dominance/no
   8  yes       availability
   9  no        no
  10  yes       dominance

Interaction
============
Individuals will interact in a number of ways, including:
  Gossip: information on their experience including individuals and resources;
  Socializing: simple glue that fullfills that requirment;
  Fighting: individuals will fight for food, mates and space;
  Relationships: one of 3 types... 
    family (offspring, parents and siblings), 
    friends (those they have socialized with before)
    enemies (those they have fought with before)
    romantic (those they areor have breed with)
    * note that that Hosts will be manogomous with Seeds and non-gender 
    identity individuals not. 

Statistics:
  Health
  Strength
  Hunger (for each usable resource)
  Age
  Family list
  Friend list
  Enemy list
  Social list
  Fight list
  Kill list
  Resource list
  Space list
  Memory ability
  Social ability
  Fight ability
  Consumerism
  Social need
  Fight need
  Breed need
  Species
  Race
