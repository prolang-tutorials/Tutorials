## Conditional Statements

### if...else statement

```nim
var name = readline(stdin)
if name == "":
  echo "You don't have a name?"
else:
  echo "Hello, ", name
```

### case statement

```nim
var name = readline(stdin)
case name:
  of "":
    echo "whut?"
  of "name":
    echo "very funny -_-"
```

### while statement

```nim
echo "What's you name dude?"
var name = readline(stdin)

while name == "":
  echo "Give me a name man!"
  name = readline(stdin) # no var token needed.
```
