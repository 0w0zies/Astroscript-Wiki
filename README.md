# Astroscript Wiki
A wiki for modding Astrofactory, using the programming language I made.

# What is Astroscript?
Astroscript is a language made for safe modding that is turned back into python at runtime, it was made to be a lua look-alike because its a language people very familiar with.
It uses mostly lua terms for easy and understandable programming. 

# How do I program in Astroscript?
Astroscript has many things from lua, including the endless amount of `end`'s (ironic considering end is supposed to stop stuff)

# Onto the functions!

`The basics`
`local` defines a local variable

`local test = 0`

`global` calls a local variable from outside of the function you are in, a python function if you couldn't tell

```
local test = "testing yay"

function testfunction()
  global test --grabs the 'test' variable from outside the function
  return test
end
```

`end` and `break` a lua function that quits out of the current loop or statement it is in, thank `end` for allowing you not to have to indent *angy python noises*

`if` the second most important part of any programming language
```
local a = "a"
if a == "a":
  local a = "b"
```
this will turn a from "a" to "b"

`function` a lua function, that creates well, a function, shown in the previous example

```
function test() -- inside the parenthesis there can be arguments
  --code here
end
test() --running the function
```
