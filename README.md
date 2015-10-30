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
2) Builtin (embedded in your program)
Not currently available
