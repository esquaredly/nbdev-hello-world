---
title: Hello
---




> First notebook for nbdev



::: {#cell-3 .cell 0='h' 1='i' 2='d' 3='e'}
``` {.python .cell-code}
from nbdev.showdoc import *
```
:::


::: {#cell-4 .cell 0='e' 1='x' 2='p' 3='o' 4='r' 5='t'}
``` {.python .cell-code}
def foo(): pass
```
:::


::: {#cell-5 .cell 0='e' 1='x' 2='p' 3='o' 4='r' 5='t'}
``` {.python .cell-code}
def say_hello(to):
    return f'Hello {to}!'
```
:::


::: {#cell-6 .cell}
``` {.python .cell-code}
say_hello("Isaac")
```

::: {.cell-output .cell-output-display}
```
'Hello Isaac!'
```
:::
:::


::: {#cell-7 .cell}
``` {.python .cell-code}
assert say_hello("Hamel") == "Hello Hamel!"
```
:::


::: {#cell-8 .cell 0='h' 1='i' 2='d' 3='e'}
``` {.python .cell-code}
import nbdev; nbdev.nbdev_export()
```
:::


::: {#cell-9 .cell}
``` {.python .cell-code}
from IPython.display import display,SVG
display(SVG('<svg height="100" xmlns="http://www.w3.org/2000/svg"><circle cx="50" cy="50" r="40"/></svg>'))
```

::: {.cell-output .cell-output-display}
![](00_core_files/figure-html/cell-9-output-1.svg){}
:::
:::



