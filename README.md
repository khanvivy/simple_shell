### 0x16. C - Simple Shell
A Unix shell is a command-line interpreter or shell that provides a command line user interface for Unix-like operating systems. The shell is both an interactive command language and a scripting language, and is used by the operating system to control the execution of the system using shell scripts.[



### Resources
Read or watch:

- Unix  -> https://alx-intranet.hbtn.io/rltoken/f0YU9TAhniMXWlSXtb64Yw
- Thompson shell -> https://alx-intranet.hbtn.io/rltoken/7LJOp2qP7qHUcsOK2-F3qA
- Ken Thompson -> https://alx-intranet.hbtn.io/rltoken/wTSu31ZP1f7fFTJFgRQC7w
- Everything you need to know to start coding your own shell concept page
man or help:

`sh` (Run `sh` as well)


## More Info
# Output
Unless specified otherwise, your program must have the exact same output as sh `(/bin/sh)` as well as the exact same error output.
The only difference is when you print an error, the name of the program must be equivalent to your `argv[0]` (See below)

## Example of error with sh:

`$ echo "qwerty" | /bin/sh
/bin/sh: 1: qwerty: not found
$ echo "qwerty" | /bin/../bin/sh
/bin/../bin/sh: 1: qwerty: not found
$
`
Same error with your program hsh:

`$ echo "qwerty" | ./hsh
./hsh: 1: qwerty: not found
$ echo "qwerty" | ./././hsh
./././hsh: 1: qwerty: not found
$
`