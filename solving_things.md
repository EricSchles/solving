#Never do math again

In school they teach us how to solve mathematical equations.  In the real world, you get computers to do it for you.  With the power of python and a little bit of magic (tm), you'll be able solve anything mathematical equation just as well as any of the greats! 

##Getting started

You'll need [sympy](http://certik.github.io/scipy-2013-tutorial/html/install.html) an awesome little library that does all the math for you!

###A first example:

Setting up expressions
```
from sympy import symbols
x,y = symbols('x y')
expr = x + 2*y
print expr + x
print expr + 2*y
print expr + 14
expr += x
print expr
```

###A second example:

```
from sympy import *
x,y = symbols('x y')
expr = x + 2*y
print solve(expr,x)
print roots(expr,x)
```

