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
  IF character index is bigger or equal than 0<br>
    SET new word to new word + character at the character index<br>
    SET charcter index to -1<br>
  
## Exercise Four

#### V1
GET numbers<br>
COMPUTE greatest common divisor<br>

#### V2
GET numbers<br>
SET num1 to one of the numbers<br>
SET num2 to the other number<br>


#### V3
GET numbers<br>
SET num1 to one of the numbers<br>
SET num2 to the other number<br>
SET smallest to the minimum of num1 and num2<br>
FOR every number between 1 and smallest<br>
  IF num1 % the number == 0 and num2 % the number == 0<br>
    SET commonDivisor to the number<br>
  ELSE<br>
    SET commonDivisor to 1<br>
 
    
  
