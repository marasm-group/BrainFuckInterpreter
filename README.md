# BrainFuckInterpreter
BrainFuck Interpreter, written in marASM.

It can interpret any BrainFuck program, but you need to append to its end the '!' symbol

# HelloWorld
```
++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.
```
must turn into
```
++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.!
```

# Usage
1) Interactive (!-terminated program from mvm console):

in your system shell:
```
mvm brainfuck.marasm
```
remember, that it will run program only when it finds the exclamation mark (!) symbol.

2) Builtin (embedded in your program)
Not currently available

## Lisence ##

This software is licensed under [WTFPL](http://www.wtfpl.net/about/). So you can do with it whatever you want!

![wtfpl.svg](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl.svg)
