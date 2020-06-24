# Namespace
A: pre-2020-06-X

## List
- [Custom](Namespace/Custom.md)
- [Built-in](Namespace/Built-in/Index.md)

## Define
### Preview
```do
def user.db.query
// do something
```
```do
def user.db.utils as private, allow higher
```

## Use
### Preview
```do
from user.db.query call <ClassName>
```
```do
from user.db call FunctionName
```

```do
use from user.db.query <ClassName>
call <ClassName>
```
```do
use from user.db FunctionName
call FunctionName
```
