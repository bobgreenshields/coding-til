# Dispatch Tables

Dispatch table are usefule for

* organising code
* removing complex nested if else statements
* allowing easy expansion of code

They can be implemented with code like this

```python
table = {}
table["first"] = lambda msg: "first" + msg
```
