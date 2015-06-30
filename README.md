# movinglife
A life simulator based on Java


# Goal
Create a life simulate environment just for fun

# Concept and Definition
A 2 dimention world with lifes in each slot. The life can move based on it's DNA and environment.

## world: The world is a N x N 2 dimention platform, a slot can contain one or zero life.

## environment: a slot can get it's environment, which refer the life near and the boundary of the world. 

## life: a life occupy a slot and try to move around inside the world. DNA will control the activity and interact with the world. The basic activity is move, merge, DNA exchange, split.

## DNA: a life has DAN which deside the movement and the way exchange DNA or merge with other life.

## move: a life can move to a spare slot nearby, up, right, down, left, up-right, right-down, left-down, up-left
+---+---+---+
| 8 | 1 | 2 |
+---+---+---+
| 7 | X | 3 |
+---+---+---+
| 6 | 5 | 4 |
+---+---+---+

## merge: a live can merge to another life and distory itself

## DNA exchange: a life can exchange information about other life and change it's own DNA

## split: a life can split to or creats a new life


# Structure and Design
## activity definition
### move:
input: DNA / environment
output: move or not, direction of move

split:
DNA exchange:
merge:

## DNA: 

# inviatation
Welcome to join the project.
