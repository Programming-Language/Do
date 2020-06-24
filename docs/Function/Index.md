# Function
A: pre-2020-06-X
- **similar** [Lambda](Lambda.md)
- **see**: [Class](../Class/Index.md)
  - **similar**: [Class Method](../Class/Method.md)

## Define

### Preview
```do
def WithoutParam ->
  do
    + 5 20
  return
```

```do
def WithParam ->
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
