# stack
Stack data structure created with Go

Creating a concrete stack data structure
You can use this generic implemenation to generate type-specific stacks, using

```
//generate a `IntStack` stack of `int` values
genny -in stack.go -out stack-int.go gen "Item=int"

//generate a `StringStack` stack of `string` values
genny -in stack.go -out stack-string.go gen "Item=string"
```
