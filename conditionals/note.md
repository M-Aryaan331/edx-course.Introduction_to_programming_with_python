there are conditionals operators:
 <,>,<=,>=,!=

If: this keyword is use to take output between two conditions
- eg:  x=3
-      y=4
-     if(x<y):
-     ....print('yes')
we use identitions in if-conditions as shown above in dots.it is use instead of {} any other languages.

elif: it is also use if conditions to improve program faster and good and it is use as
- eg:  x=3
-      y=4
-     if(x<y):
-     ....print('yes')
-     elif(x>y):
-     ....print('good')

else: it is use to end the conditions at a last.

or: this keywords is use to take conditions like
-   if(x>y or x<y):
-   ....print('x not equal to y')

and: this keyword is use in conditions if both of conditions is true.
- eg: if(num <=3 and num>=0):

boolean func: boolean functions is use to take output or give conditions in true or false 
  its written as True and False

 eg: def main():
     ....x=int(input('what's x?')
     ....if is_even(x):
         ....print('even')
         else:
         ....print('odd')
     def is_even(n):
     ....if n%2==0:
         ....return True
         else:
         ....return False
  OR:    return True if n%2==0 else False
  OR:    return n%2==0
match: match is use for conditions same as if-statement.
- eg: name=input('what is your name?')
-     match name:
-     ...case "harry":
-        ....print('good')
-     ...case 'ali':
-        ....print('fine')
OR:      case 'harry' | 'ali':
      case_:
      ....print('who')
