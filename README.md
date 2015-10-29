# C---Learning

This is my C-learning repo. I am currently using Learning C The Hard Way book.

**printf** escape sequences:
#\a#  : this one is soooo cool.
        Makes a "beng" sound when you indlude it.
#\b#  : delete the character/space right before the location "\b" was placed.
#\f#  : print the folowing line in the same location of the next line. It is like a line break.
#\r#  : erase the line and print whatever follows as the beginning of the line. It is easy to vision "\f" and "\r" used together for a line break even thought I have not idea why do not they use "\n".
#\v#  : a new line like "\f".
#\t#  : a tab space in the line.
#\\, \', \", \?#  : just print whatever follows the first "\".
#\nnn, \xhh ...#  : tricky, learn it when needed.

##printf## format specifiers:
#%i or %d#   : integer; adding a number (n) after "%" means the whole thing should take n space, it will space from the front. If there is a number "a" in front of "n", then add a in front of whatever will be printed to fill the space requirement.
#%f#         : float (with a dot 0.000). If there is a "a.b" after "%", then "b" is the digits after "dot", and "a" means the whole thing needs to be at least "a" space wide. Adding a "ca.b", fill "c" when the wide is shorter than "a". (It is kinda tricky, but I love it).
#%c#         : char, hold only one space thing, like "h", "A", "0"...
#%s#         : string, hold whatever you want.
There are other trickes at http://www.codingunit.com/printf-format-specifiers-format-conversions-and-formatted-output
