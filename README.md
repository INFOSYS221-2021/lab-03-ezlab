# Group 1 - Lab 3

## Names

* Jack McGrath
* Amos Lou
* Olivia Joe-West

## Exercise One

Write the pseudocode instructions for the following:

Given a word or a sentence, display the given word/sentence in reverse order.

#### V1
GET word or sentence<br>
SET word backwards

#### V2
GET word or sentence<br>
INIT new word<br>
FOR every letter in the word backwards<br>
  ADD the letter to new word<br>

#### V3
GET word or sentence<br>
INIT new word<br>
FOR every character in word<br>
  IF character index is bigger or equal than 0
    SET new word to new word + character at the character index
    SET charcter index to -1
  
## Exercise Four

#### V1
GET numbers
COMPUTE greatest common divisor

#### V2
GET numbers
SET num1 to one of the numbers
SET num2 to the other number


#### V3
GET numbers
SET num1 to one of the numbers
SET num2 to the other number
SET smallest to the minimum of num1 and num2
FOR every number between 1 and smallest
  IF num1 % the number == 0 and num2 % the number == 0
    SET commonDivisor to the number
  ELSE
    SET commonDivisor to 1
 
    
  
