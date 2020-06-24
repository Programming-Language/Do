# Function
A: pre-2020-06-X
- [Back](../Index.md)
- **see**: [Built-in](Built-in/Index.md)
- **similar** [Lambda](Lambda.md)
- **similar**: [Class Method](../Class/Method.md)
  - **see**: [Class](../Class/Index.md)
  

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
    Two<Integer> 10..?
  do
    One, + Two 10
  return
end
```

## Use

### Preview
```do
print call WithoutParam
```
**Output**: 25

```do
print call 'Hello' 13 WithParam
```
**Output**: Hello 23
