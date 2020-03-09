## Comments

Comments start anywhere outside a string or character literal with the hash character #. Documentation comments start with ##:
```nim
# A comment
var myVariable: int ## a documentation comment
```

Documentation comments are tokens; they are only allowed at certain places in the input file as they belong to the syntax tree! This feature enables simpler documentation generators.

Multiline comments are started with #[ and terminated with ]#. Multiline comments can also be nested.

```nim
#[
You can have any Nim code text commented
out inside this with no indentation restrictions.
      yes("May I ask a pointless question?")
  #[
     Note: these can be nested!!
  ]#
]#
```
