## sys module:
````sh
import sys

num1 = float (sys.argv[1])
operator = sys.argv[2]
num2 = float (sys.argv[3])

if operator == "add":
   total = num1 + num2
   print (total)

input: file_name.py 2 add 3
output: 5
````
