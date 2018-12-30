# BabySitterKata

This is a calculator for babysitter pay. It takes three inputs, start time ("5:45PM"), end time, and a family ("A", "B", "C").

Assumption: going to implement the business logic for this. The product won't be an executable, but that might be produced as a side effect of testing it.

Assumption: it is ok to throw an exception on the occurrence of entering an invalid time

Assumption: Something has to be done with fractional hours. Assuming it will just ignore the fractional part for now. Thus, if the start time is "5:16PM" and the end time is "11:10PM", that is only considered 5 hours.

Assumption: for family C, it says there is a certain rate before 9PM. Thus, if they start at "8:14PM", that is not a full hour, so would not get paid for that fraction. If the start time was "7:15PM" that would be only 1 hour for the same reason. 

