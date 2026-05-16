# File-handing-error
Python program to read a file and handle errors using exception handling.
try:
    with open("sample.txt ", "rt") as fh:
        data = fh.read()
except FileNotFoundError:
    print("Error: The file 'sample.txt' was not found.' ")
else:
    print(data)
