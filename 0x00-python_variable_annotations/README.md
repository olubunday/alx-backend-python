<h1>0x00-python_variable_annotations</h1>

<h2>Task 0</h2>

<p>Write a type-annotated function add that takes a float a and a float b as arguments and returns their sum as a float.</p>
<code>
bob@dylan:~$ cat 0-main.py
#!/usr/bin/env python3
add = __import__('0-add').add

print(add(1.11, 2.22) == 1.11 + 2.22)
print(add.__annotations__)

bob@dylan:~$ ./0-main.py
True
{'a':  <class 'float'>, 'b': <class 'float'>, 'return': <class 'float'>}
</code>

