![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Statistics Foundations
In this lab we are going to put into practice what we learned about the foundations of statistics. You won't need to use Python, just your brain and a little bit of *Markdown*. 



## Challenges
### Challenge 1
One player rolls two dices. Describe the measurable space and the random variable for:
* A. The values that the player obtains.

    >**measurable space - 21 outcomes: (1,1), (1,2), (1,3), (1,4), (1,5), (1,6), (2,2), (2,3), (2,4), (2,5), (2,6), (3,3), (3,4), (3,5), (3,6), (4,4), (4,5), (4,6), (5,5), (5,6), (6,6)**
    **random variables is the combination of the rolls of the dice**

* B. The sum of the values obtained.
    
    >**measurable space - Range [2;12] - 11 potential outcomes**
     **random variables is the sum of the two sides of the dice**
        
* C. The maximum value obtained after rolling both dices.
    
    >**measurable space - 6 Outcomes: 1, 2, 3, 4, 5, 6**
     **random variable is the max of the two dice**

Describe the following events:
* Case A: Both values are greater than 5.
    
    >**One possible outcome (6,6)**
      
* Case B: The sum of values is even.
      
     >**12 Outcomes : unique sums of (2,2), (2,4), (2,6), (4,4), (4,6), (6,6), (1,1), (1,3), (1,5), (3,3), (3,5), (5,5), which is 6 oucomes: 2,4,6,8,10,12**
        
* Case C: The maximum is the value of both rolls.
     
     >**6 Outcomes: 1, 2, 3, 4, 5, 6 for events (1,1), (2,2), (3,3), (4,4), (5,5), (6,6)**

        

### Challenge 2
One player picks two cards from a poker deck. Describe the measurable space and the random variable for:
* A. The number of figures he picks.
    
    >**measurabel space - 498 outcomes: 66 (12*11/2 : 2 figure cards from 12 possible figure cards, no repetitions, order does not matter) + 432 (one figure and one regular card 12*36)** 
     **random variable - combination of cards**
    
* B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.

    >**measurable space - 19 outcomes are unique sums of (2|3|4|5|6|7|8|9|10|15) + (2|3|4|5|6|7|8|9|10|15), which is 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 25, 30** 
    **random variable - sum of two cards**

* C. The number of hearts or spades he picks.

    >**measurabel space - (heart+heart) | (spade+spade) | (heart and spade) : (26*25/2) = 325 outcomes** 
    **random variable - combinations of hearts and /or spades**


Describe the following events:
* Case A: The number of figures in the cards the player picked is two.
    
    >**66 outcomes - 2 figure cards from 12 possible figure cards, no repetitions, order does not matter)** 

* Case B: The sum of card values is 17.
    
    >**1 outcomes - out of 19 possible sums, combinations of cards: (7&jack) +(7&king)+(7&queen)+(7&10) = 4*(4*4) = 64 combinations** 
    
* Case C: The value of both cards is less than 8.

    >**combinations of cards of spades or hearts: (2|3|4|5|6|7) & (2|3|4|5|6|7) = 12*11/2 = 66** 

### Challenge 3
Two players roll a dice. Describe the measurable space and the random variable for:
* A. The score of player A.

    >**measurabel space - 6 outcomes : 1,2,3,4,5,6** 
    **random variable - value of the dice for player A**
    
* B. The greatest score.
    >**measurable space - 6 Outcomes: 1, 2, 3, 4, 5, 6, Can be 5 outcomes (2,3,4,5,6) if we ignore the ties **
     **random variable is the max of the two dice**

* C. The earnings of player A if the game rules state that:  
"The player with the greatest score gets a coin from the other player.".

    >**measurabel space - 3 outcomes : -1, 0, 1** 
    **random variable - value of the earnings**

* D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". 
   
   >**measurable space -  11 Outcomes : -5, -4, -3, -2, -1, 0, 1, 2, 3, 4, 5 **
    **random variable is the value of the earnings**

Describe the following events:
* Case A: The score of player A is 2.
    
    >**measurabel space - 1 outcome from 6**
    
* Case B: The greatest score is lower or equal than 2.
    > **measurable space - 2 Outcomes: 1, 2. Can be 1 outcome if we ignore the ties**

* Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins.
  
  >**measurable space - 3 Outcomes -  (5,1), (6,1), (6,2) **
      
  * Player A loses more than 2 coins.
  
  >**measurable space - 6 Outcomes -   (1,4), (1,5), (1,6), (2,5), (2,6), (3,6)**
  
  * Player A neither wins nor loses coins.
  
  >**measurable space - 6 Outcomes -  (1,1), (2,2), (3,3), (4,4), (5,5), (6,6)**

## Bonus challenges
### Bonus Challenge 1
Three players take balls from a box. Inside that box there are red, blue, green and black balls. The players can take three balls at mosts with the following rules:


* If the ball is blue, they can take another ball.
* If the ball is green, they get one point and they can take another ball.
* If the ball is red, they can’t take another ball.
* If the ball is black, they lose one point and they can’t take another ball.

Describe the measurable space and the random variable for:
* A. Player A wins. Do not consider ties as a win.
* B. Player A and B get the same points.
* C. All players get 0 points.

### Bonus Challenge 2
Consider the situation of bonus challenge 1 but now with four players. Does anything change in your solutions? What are the changes in each case?

### Bonus Challenge 3
One player takes three balls from a box. Inside the box there are 5 balls: two of them are black and the other three are white. 

Describe the measurable space and the random variable for:
* A. The number of white balls if every time we take a ball we keep it.
* B. The number of white balls if every time we take a ball we put it back again into the box.
* C. The number of black balls if every time we take a ball we keep it.
* D. The number of black balls if every time we take a ball we put it back into the box.