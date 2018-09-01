# BUMLR
Bottom-Up Multi-Level Representation

Rules:
- a person can have only one other person as a representative
- a representative can have a maximum of 6 people to represent
- every person has a level assigned
- every person is level 1 (L1) by default
- a person can represent only people on his level or one level below
- if a represents 4 or more people his level is increased
- a person can choose a representative only on the same level or one level above
- a person can choose a representative only if the other person already represents less than 6 people
- all recalculations of levels are done at the same time, once a day
- a person loses it's representative if he becomes 2 levels above and can choose another one
- there is no maximum of the existing leves
- a new level is generated when there are 4 people at the highest level who shoose the same representative
- the highest level 
- a person can not choose to be it's own representative

Comments:
- in case of around 10,250,000 total people and an average of 5 people represented by one representative this makes the following structure:

L9:          2
L8:         13
L7:         64
L6:        320
L5:      1,600
L4:      8,000
L3:     40,000
L2:    200,000
L1: 10,000,000

* Without accounting for the people which representative is at the same level as them and represents less than 4 people, so can't go to the next level
