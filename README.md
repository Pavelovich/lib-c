lib-c
=====

Library of C functions for various uses.  This can be added to the source code
of programs, in the directory with the main file or under `lib` or something
similar.

Function documentation
----------------------

**intro()**

Users will need to change the source code of this function to relect their own
name or company that they are developing for.

```C
intro("Program", 2014, "License");
```

**askInt()**

```C
int var = askInt("Enter a number: ");
```

**askDouble()**

```C
double var = askDouble("Enter a number: ");
```

**askChar()**

```C
char *var = askChar("Enter a sentence: ");
```

**ranGen()**

```C
int number = ranGen();
```

**busyRun()**

Use this to count and pointlessly waste time.  Set it to something large for
any amount of noticeable latency.

```C
busyRun(10000000);
```

**printOut()**

Print out a string one character at a time.  A larger number gives more time
between characters.

```C
printOut(9, "Enter a number below:");
```

**bash()**

Run a shell command and store the output.

```C
char *var = bash("ls -l ~");
```

**mVol()**

Sets the volume on an Apple computer.  Uses the values 0-10.

```C
mVol(7);
```

**istr()**

Convert and interger to a string.

```C
istr(2345);
```

**dstr()**

Convert a double to a string.

```C
dstr(42.54);
```
