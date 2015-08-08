# python
## Python for System Admins

### Installation python 3 on Ubuntu 14:04

* `sudo apt-get install python3` --- install python3
* `python3` --- for enter the interctive shell

### Some basic of python
* `>>>"Hello World"` --- hit enter it shows the result in the screen we dont need to type print
    * `'Hello world'`
* `>>> message = "Hello World"` --- our first variable name is message and value of the variable is Hello world
* `>>> message ` -- Now type the variable it show result hit enter
   * `'Hello world'`
* `>>>message[5:]` --- list of the variable store inside
    * ` world`
* `>>>message[0:4]` -- another example hit enter
    * ` hello`
* `>>>message [:5] + " " +  message` --- concatenate example 
    * ` hello hello world`
* `>>>help()` --- help is very powerfull we can view the modules of python
    * `help>modules` --- list down all the modules
    * `os`
    * `chown`

Now write a python script
* `vi hello.py` -- open a file hello.py it import the sys module
```
    import sys
    message = "Hello World"
    print (message)
    print (sys.argv[0])
    print ("hi, " + sys.argv[1])
```
* `python3 hello.py Abaid` --- run the first python script
```
    Hello World
    hello.py
    hi, Abaid
```

### Comments in python

* `#` single line comment with # sign
* `... ...` --- Multiline commands with the three dots
