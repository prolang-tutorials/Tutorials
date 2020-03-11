## Procedure

Procedures are used to define a particular part of code that can be executed on demand (Some languages call them methods or functions.) In Nim new procedures are defined with the proc keyword:

```nim
# define the procedure
proc sayHello() =
 echo "Hi!"

sayHello() # calls the procedure
```

It also excepts arguments and return type too!

```nim
proc ask(msg: string): bool =
  if msg == "I love Nim": return true
  else: return false

echo ask("I love Nim") # return true
```

Procedures are main components of any application, these will help you write your dream code ;)
