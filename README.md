# chpti
a crash attempt at defining the .chpti filetype and interpretter standards

In the early days of computers, .plan files were used as an alternative to .txt for a very specific user case scenario in unix systems. It finally eneded up being used as a scroll-and-get-an-animation kind of format. You can read about that history here: http://www.catb.org/jargon/html/P/plan-file.html

The reason I mention it is because it's not a new phenomenon to see users wanting to create their own filetypes or to convert generic filetypes to have more specialized use cases just because of a the prevalent usage culture of the era.

Here, we attempt to define a compiler and language standard for a short, comprehensive, extensible multi-derivative langauge, whose source file is saved as `.chpti` and compiled binary as `.chp` ... I understand some people would prefer it the other way around. Feel free to submit an issue under the issues tab.

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

WIP: Work-In-Progress
Deadline: Octobber 2019 [principal release]
Progress Tracking: pending -+state+- 1% ??
