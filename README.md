#Problem Solving and Logical thinking Session#

##Cook the code(CTC)##

 1.Framing the logic ***[try to get the logic of the given program]***

 2.Algorithm(Recipe) ***[try to write the down the steps]***

 3.Ingredients ***[Eg: Variables,looping statements,Conditional statement,Array,,etc]***

  4.Template code ***[Write the down temp code]***

Example program with details,
1.  Armstrong number

Find whether the 153 is a Armstrong number
```
153 - 1*1*1 = 1
      5*5*5 = 125
      3*3*3 = 27
      Then adding => 1+125+27 = 153 (output)
```    

##Logic

Separating the digits from the number

Step 1: (First split)
153%10 = 3 
153/10 = 15

Step 2: (Second split)
15%10 = 5
15/10 = 1

Step 3: (Final split)
1%10 = 1
1/10 = 0 ---> Stop the process

==>Derivation from above steps,

input % 10 
input / 10

##Algorithm (write the steps in words)

    Step 1: Get the input
    Step 2: Split the numbers - Modulo divide and divide the input by 10 until the input becomes zero.
    Step 3: Take the power of splitted digits in the input and add the power.
    Step 4: Compare the input and derived result, if both are same then print armstrong 
        or else print not an armstrong.

##Ingredients

    Step 1: Variable

    Step 2: Looping Construct
    Needed details for the loop,
      - Where to start : NA (Not applicable)
      - Where to stop : input > 0
      - How to iterate/generate : NA
      - Which loop to use (for or while): While(input>0)

    Step 3: Variable (Counting the derivation)

    Step 4: Conditional Statements(if/else)

##Template code

    Step 1: Var input

    Step 2: while(input>0)

    Step 3: var count

    Step 4: if(input == derived result),else
