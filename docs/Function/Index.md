# Function
A: pre-2020-06-X
- **see**: [Class](../Class/Index.md)
- **similar**: [Class Method](../Class/Method.md)

## Define

### Preview
```do
WithoutParam ->
  do
    + 5 20
  return
```

```do
WithParam ->
  param
    One<String> 5..600
    Two<Integer> 18..?
  do
    One, + Two 10
  return
end
```

## Use

### Preview
```do
WithoutParam call print
```
**Output**: 25

```do
print call 'Hello' 13 WithParam
```
**Output**: Hello 23
