# Class
A: pre-2020-06-X

## Define
### Preview
```do
def <Name>
  create
    main
  export
    say
  method
    main ->
      ...
    end
    say ->
      param
        YourName<String>, 1..?
      do
        + 'Hello' YourName + '!'
    return
    lol ->
      // private method
    end
end
```

## Use
### Preview
```do
  print call<Name> 'Dooda' say
```
**Output**: Hello Dooda!
