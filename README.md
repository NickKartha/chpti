# chpti
A crash attempt at defining the `.chpti` filetype and interpretter standards.

In the early days of computers, `.plan` files were used as an alternative to `.txt` for a specific use case in unix systems. 
It ended up being used as a scroll-and-get-an-animation kind of format in its later years of usage.
You can read about that history here: http://www.catb.org/jargon/html/P/plan-file.html

The reason it is mentioned is because it's not a new phenomenon to see users wanting to create their own filetypes or to convert generic filetypes to have more specialized use cases just because of a the prevalent usage culture of the era. In extension (pun intended), languages can be defined and 

Here, we attempt to define a compiler and language standard for a short, comprehensive, extensible multi-derivative language, whose source file is saved as `.chpti` and compiled binary as `.chp` 

Feel free to submit an issue under the issues tab inorder to make a contribution.

## Chapathi: A Short Programming Language 

## Syntactic

```
o("hello world") == o"hello world"
==> True

true === True
==> True

n : i("enter a number")
>>> enter a number: ...

m : i"enter the dragon".inpdef('y':'entered','n':'leave now', *:'invalid')
>>> enter the dragon: y
entered

```

### Features

#### Print, Returns and Boolean Are Superpowered

`o(True):` is the same as `True:` block, which  

#### Quick Execution And Pipelining
commands are quick to execute, everything is pre-packaged

#### Extended String Functions 
strings have all operations handled, including file in/out methods.

### Use Cases

- Text Adventure RPGs
- Decision Making Systems (Operations Tool)
- Simple Automation

### Paradigm

List based, Object Oriented, Data as Object model

WIP: Work-In-Progress  
Deadline: Octobber 2019 [principal release]  
Progress Tracking: pending -+state+- 1% ??  
