# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.
1. Text representation 
2. Graphical representation
3. Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description
Consider a situation a player(AGENT) is  playing in the football field.The aim of the player is to place the ball in goal state.

### State Space
{BAP,BWP,BOB,BG,} - {0,1,2,3}
 where, 
* BAP -> Ball is away from the player.
*  BG -> Ball is in the goal state.
*  BOB -> Ball is out of the Boundary.
* BWP -> Ball is with the player.

### Sample State
 BAP -> 0
*  Ball is away from the player.

### Action Space
{F,K} -{0,1}
where, 
  * F -> FALL
  * K -> KICK

### Sample Action
K -> 1
* KICK

### Reward Function
```
Reward function = { +1, when the ball is in the goal.
                    0, otherwise.
```
### Graphical Representation



## PYTHON REPRESENTATION:
```
P = {
    0:{
        0: [(1.0,0,0.0,False)],
        1: [(1.0,0,0.0,False)]
        
    },
    1:{
        0: [(1.0,1,1,True)],
        1: [(1.0,1,1,True)]
        
    },
    2:{
        0: [(1.0,2,0,False)],
        1: [(1.0,2,0,False)]
        
    },
    3:{
        0: [(1.0,0,0,False)],
        1: [(1.0,1,1,True)]
        
    }
}
P
```

## OUTPUT:
![reinexi1out](https://github.com/anithapalani2123/mdp-representation/assets/94184990/d25bd31f-2519-4e57-8020-34c520ef10fa)


## RESULT:
Thus, the given real world problem is successfully represented in a MDP form .

