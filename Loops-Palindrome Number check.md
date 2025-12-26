## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
n=int(input())
n1=n
pal=n
rev=0
while n>0:
    r=n%10
    rev=rev*10+r
    n=n//10
if pal==rev:
    print("The given number",n1,"is a Palindrome")
else:
    print("The given number",n1,"is not a palindrome")
```
## Output
<img width="916" height="861" alt="529734046-fda85eb9-f740-4a4b-ad80-7bae48885907" src="https://github.com/user-attachments/assets/368c90e9-eff0-4bb9-81c0-961bde7cb992" />

## Result
Thus, the given python program has been executed successfully.
