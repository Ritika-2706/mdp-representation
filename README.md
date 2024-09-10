# MDP REPRESENTATION

## AIM:
To represent any one real-world problem in Markov Decision Problem(MDP) form.

## PROBLEM STATEMENT:

### Problem Description
The agent's role is to manage the traffic signal controls by adjusting the signal colors based on traffic conditions.

### State Space
{0,1,2} = {Red,Yellow,Green}

### Sample State
{0} = {Red}

### Action Space
{0,2} = {Stop the vehicle on red signal hits, ready to go} 

### Sample Action
{0} = {Stop the vehicle on red signal}

### Reward Function
R = {If +1,ready to go when signal returns green, otherwise 0}

### Graphical Representation
![gp](https://github.com/user-attachments/assets/460bb76e-7a44-46d1-9912-4ec994f59506)


## PYTHON REPRESENTATION:
```
Developed by: Ritika S
Reg no: 212221240046
```
```
P = {
0: {0: [(0.9, 0, 0.0, True), (0.1, 1, 0.0, False)],  
    1: [(0.0, 0, 0.0, True), (1.0, 2, 0.0, False)]},

1: {0: [(0.8, 0, 0.0, True), (0.2, 1, 0.0, False)],  
    1: [(0.0, 1, 0.0, True), (1.0, 2, 1.0, False)]},

2: {0: [(0.7, 2, 0.0, True), (0.3, 0, 0.0, False)],  
    1: [(0.0, 2, 0.0, True), (1.0, 0, 0.0, False)]}
}

```

## OUTPUT:
![Screenshot 2024-09-03 204827](https://github.com/user-attachments/assets/f923a5f4-d780-4ddf-83e6-8e0839b90574)


## RESULT:
Thus, a real-world problem is represented in MDP form.


