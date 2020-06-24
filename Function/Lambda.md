# Λ Lamda
- **see**: [Named Functions](Index.md)

## Use and Define
### Preview
```do
myLambda <- do 'I said moo.' return
call myLambda
```
**Value**: I said moo.

```do
myLambdaWithParams <- param X<Integer>; do X return
call 10 myLambdaWithParams
```
**Value**: 10
