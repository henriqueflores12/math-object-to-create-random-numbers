# math-object-to-create-random-numbers

this example is designed to generate a ramdom whole number between 1 and 10
the Math object's ramdom() method generetes a random number between 0 and 1 (with many decimal places)
to get a random whole number between 1 and 10 you need to multiply the randomly generated number by 10
this number will still have many decimal places so you can round it down to the nearest integer the floor()method is used to specifically round a number down (rather than up or down)
this will give you a value between 0 and 9 you then Add 1 to make it a number between 1 and 10
if you used the round () method istead of the floor()method the numbers 1 and 10 would chosen around half of the number of times that 2-9 would be chosen anything between 1.5 and 1.999
would get rounded up to 2 and anything between 9 and 9.5
would be rounded dowm to 9
using the floor() method ensures that the numbers is always rounded down to the nearest integer,and you then can add 1 to ensure the number is between 1 and 10...
