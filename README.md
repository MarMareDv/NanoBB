# NanoBB
Lisp and scratch inspired esolang, with a javascript interpreter for ease of use for web applications, meant to be simple to pick up and learn.

# Examples

## Hello World 
```
[print, "Hello World!"]
```

## Truth Machine
```
[Str, "inp", [ask, ""]]

[if, inp = "1",{
  [goto, Loop]
}]
[end, inp]

:Loop
[print, inp]
[goto, Loop]
```
