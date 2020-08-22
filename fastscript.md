**What?**

An easy package from making python scripts.
Makes __main__, argparse unnecessaary and user input much easier

**How?**

**Install**

Either pip install fastscript or conda install -c fastai fastscript

**Use**

```
from fastscript import *
@call_parse
def main(msg:Param("The message", str),
         upper:Param("Convert to uppercase?", bool_arg)=False):
    print(msg.upper() if upper else msg)
```
    
**Reference**

[FastScript](https://fastscript.fast.ai/)
