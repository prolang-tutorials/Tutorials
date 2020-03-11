## Hello World in Nim

```nim
echo "Hello, World!"
```
Isn't it easy?

```nim
var input:string = readline(stdin)
echo input
```
This code will read input from the stdin and print it!
Note: you can statically define varibale type using the `:` token

## Running the code

```bash
nim c hello.nim
```
This will create an executable `hello` in the current directory.

Now, you can simple type `./hello` to run it.
