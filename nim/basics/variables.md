## Variables

```nim
var x: string= "string"
```

Similarly,
```nim
var an_array: seq[string] = @["smth", "whatever", "wow"]
# also nested lists:
var nested_array:seq[seq[string]] = @[@["r/hmm"]]
```
Even if we don't don't specify the type, both of them will ultimately return the same thing.

Assigning is also pretty straightforward.

```nim
var x, y = 3  # assigns 3 to the variables `x` and `y`
echo "x ", x  # outputs "x 3"
echo "y ", y  # outputs "y 3"
x = 42        # changes `x` to 42 without changing `y`
echo "x ", x  # outputs "x 42"
echo "y ", y  # outputs "y 3"
```
Next, we learn about various types that we define in Nim.
