# Tim
Class to log timeing of block or function

Can be used as decorator or as context.

## Usage

Usage as decorator:
```python
@Tim("My Timer", "timeout")
def foo():
    do_stuff
```

Usage as context:
```python
def foo():
with Tim("My Timer", "timeout"):
   do_stuff
```

