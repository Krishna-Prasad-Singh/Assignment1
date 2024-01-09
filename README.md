<h2>Assignment1</h2>
<p>Q1. Write a program to iterate the first 10 numbers, and in each iteration, print the sum of the current and previous number.</p>
<br>
<br>
<p>
Sol 1:-
i = 0
while i != 10:
    pre_num = (i-1)
    print(f"current number {i}", "previous number is", {pre_num+i})
    i += 1
Sol 2:-
previous_number = 0
for i in range(1,11):
    print(f"current number {i}", "previous number is", {previous_number+i})
    previous_number = i
</p>
<br>
<br>
Q2. Write a program to accept a string from the user and display characters that are present at even index number.
Sol :-
str = input("Write a string here:- ")
even_index = ""
for i in range(len(str)):
    if i % 2 == 0:
        even_index += str[i]
print("charaters present at even index are", even_index)
<br>
<br>
Q3. Write a program to remove characters from a string starting from zeeo up to n and and return a new string.
Sol :-
str = input("Write a string here:- ")
n = int(input("What's n? "))
new_str = str[n:]
print("new string:- ", new_str)



Q4. Write a function to return True if the first and last number of a given list is same. If numbers are different then return False.
Sol :-
def check(list):
    if list[0] == list[-1]:
        return True
    else:
        False



Q5. Given two list of numbers, write a program to create a new list such that the new list should contain odd numbers from the first list and even numbers from the second list.
Sol :- 
Couldn't understant the question.



Q6. Print multiplication table from 5 to 10.
Sol :-
for number in range(5, 11):
    print(f"Multiplication table for {number}:")
    for multiplier in range(1, 11):
        product = number * multiplier
        print(f"{number} times {multiplier} equals {product}")
    print()



Q7. Write a program to create a new string made of an input string's first, middle, and last character.
Sol :-
str = input("Write a string here:- ")
new_str = []
if len(str) == 1:
    print(str)
else:
    new_str.append(str[0])
    new_str.append(str[len(str)//2])
    new_str.append(str[-1])
print(''.join(new_str))



Q8. Write a program to reverse a given string.
Sol :-
str = input("Write a string here:- ")
count = {}
for characters in str:
    if characters in count:
        count[characters] += 1
    else:
        count[characters] = 1
print(count)



Q9. Write a program to reverse a given string.
Sol :-
previous_number = 0
for i in range(1,11):
    print(f"current number {i}", "previous number is", {previous_number+i})
    previous_number = i



Q10. Write a program to split a given string on hyphens and display each substring. {ex- Rahul-is-a-doctor.}
Sol :-
Couldn't understand the question.
