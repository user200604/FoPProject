# FoPProject
Check if a Number is Palindrome 
 n = 121
 original = n
 reversed = 0
 while n > 0
     digit = n % 10
     reversed = reversed * 10 + digit
     n = n / 10
 end
 if original == reversed
     puts 1
 else
     puts 0
 end
 exit
/////////////////////////////////
Find the Largest Digit in a Number

 n = 3947
 largest = 0
 while n > 0
 digit = n % 10
 largest = Math.max(largest, digit)
 n = n / 10
 end
 puts largest
 exit
//////////////////////////////////
Reverse a number
 n = 1234
 original = n 
 reversed = 0
 while n != 0
     digit = n % 10
     reversed = reversed * 10 + digit
     n = n / 10
 end
 puts reversed
exit
///////////////////////////
sum of first n numbers
n = 10
sum = 0
i = 1
while i <= n
  sum = sum + i
  i = i + 1
end
puts sum  
//////////////////////////
Factorial of N
n = 5
factorial = 1
i = 1
while i <= n
  fact *= i
  i = i + 1
end
puts factorial
exit
////////////////////////
GCD of two numbers
 = 48
b = 18
while b != 0
  temp = b
  b = a % b
  a = temp
end
puts a
exit
///////////////////////
Check if a Number is Prime 
n = 13
is_prime = true
if n <= 1
  is_prime = false
else
  i = 2
  while i * i <= n  # This checks up to the square root of n
    if n % i == 0
      is_prime = false
      break
    end
    i = i + 1
  end
end
puts is_prime  
exit

///////////////////////////
Sum of Digits
n = 1234
sum = 0
while n > 0
  sum = sum + n % 10
  n = n / 10
end
puts sum  # Output will be 10
exit
/////////////////////////////
 Multiplication Table
 n = 5
 i = 1
 while i <= 10
 puts n * i 
 i = i + 1
 end
 exit
/////////////////////////////
Nth Fibonacci number
n = 10
a = 0
b = 1
i = 1
while i <= n 
  puts a
  temp = a
  a = b
  b = temp + b
  i = i + 1
end
exit
