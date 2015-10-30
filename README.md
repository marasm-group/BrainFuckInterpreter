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
  1. (optional) copy brainfuck into modules
  2. add it to your program header ("dependencies" section)
  3. store brainfuck program somewhere in memory
  4. write some code:
  
  ```
  push <desired memory address>    ;; setup brainfuck starting memory address
  push <brainfuck program address> ;; setup brainfuck program address
  call $brainfuck_interpret        ;; call the interpreter function
  ```
  5. ?????
  6. PROFIT

## Lisence ##

This software is licensed under [WTFPL](http://www.wtfpl.net/about/). So you can do with it whatever you want!

![wtfpl.svg](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl.svg)
