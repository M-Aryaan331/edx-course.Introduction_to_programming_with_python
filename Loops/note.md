Loops condition is use to repeat a code.

While: this keyword is use in loop condition to repeat a code 
- eg: i=3
      wile i!=0:
      ....print('hello')
          i=i-1
In first line of code, it is a initial value given to variable and in second line,there is a condition that is true that i is not equal to 0 and the value will be print in this condition unless when condition will false and the value of i when comes equal to 0 then code will terminate because of condition false.

For: for loop is use to repeat a code or a program statement and in this for loop we know the start and terminate point.
eg:  for i in range(4): or for _ in range(3):
     ....print('hello')
in this program,hello word is write 4 times and in this,range function is use to start and terminate line.

  end() function is use to end the line 
  break keyword is use to stop a while loop and continue keyword is use to continue the while loop.
while True:
....n=int(input('what is the number'))
....if n>0:
    ....break
for _ in range(n):
....print('hello')

Lists: this data type is use to store multiple values in one variable.
eg: students=['hello','bye','hi']
    for student in students:
    ....print(student)
len(): as above exaample,students is not range() function bacause it is notinteger so we len() function in for loop to terminate equal to lengh to students .
As: for i in range(len(students))
    ....print(i,students[i])

dict: is a type of data which have keys and values.
- eg: students{'harry':'gryf','all':'gryf','gorge':'scylon'}
- print(students['harry'])

