# assignment2
# part1
# take integer from the user.
a=int(input('Enter number'))
# check whether the number is even or odd using an if-else
if a % 2==0:
    print("this is an even number")
else:
    print("this is an odd number")
    print("thank you")
# output
Enter number 57
this is an odd number
thank you

# part2
# give the value of total sum
total_sum=0
# uses a for loop to iterate over numbers from 1 to 50
for number in range(1,51):
    total_sum+=number 
# display the final sum
print("the sum of all integers from 1 to 50 is:",total_sum)

# output
the sum of all integers from 1 to 50 is: 1275

