Project: better-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate conditional statements.
How to start this project: Create one or more TicketMachine objects.



Q47: No the balance does not change when there is an error message it stays 0.I predict that
 there will still be a errorif I enter 0 as the parameter.I ended up being right about it.
 
 
 Q48: I predict that it will allow us to insert $0.It infact did not let me insert $0,
 it showed me the same error as last time (use positive amount rather than ...).
 
 It's behaviour changed,when I insert an amount less or equal to 0,it shows an error
 on the output in my terminal window (use positive amount rather than ...)
 When I try to insert an amount greater than 0,it does not show up on my output.
 
 
 
 Q50: The boolean was isVisible,and yes it was well suited because it is either 
 visible or invisible.


 
 
 Q51: 
 The price is included in the total to ensure that only the required
 amount for one ticket is accounted for.It is then deducted from 
 the balance so that the final charge reflects just the cost of a single ticket
 
 
 
 Q52: Yes the code still compiles with no errors.Nothing happened because the else statement no longer tells you 
 that I need to insert more money.
 
 
 
 Q53: No it can't because we always have to insert
 a positive amount greater than $0.
 
 
 
 Q55:
 saving = price * discount; 
 
 
 
 Q56: mean= total / count
 
 
 
 Q58:I find it easier to understand when the budget shows 
 up along with the message.
 
 
 
 
 Q59: The second version,the balance is reset to 0,and then returned,for that
 reason,no matter what the balance was initially,it will always return 0.
 In the original version,the amountToRefund,becomes whatever the balance is.
 Returning amountToRefund will always be correct because it has been already
 assigned with the previous balance before reseting to 0.The test i did
 to demonstrate that it does not give the same results:
 With the original version,I inserted an amount of money.
 I then checked my balance and and my balance was the same as what i inserted
 I then called the  refundBalance method and it displayed my balance before refunding.
 My balance was then 0.
 
 
 Whilst the other version, directly displayed my new account balance ($0) 
 while calling the refundBalance method.


 Q60: It does not compile.Any statement that runs below any return statement,will be considered by the program as
 an unreachable statement.

 
 
 Q61: Yes it does compile.I noticed with the original version,our int price is shown on the
 value of the price field (example:20)in the inspector,Whilst with the second version, the int price is set at 0,
 even though that isn't the actual case.This happens because we already have a int price in the class.


 
 
 
 
