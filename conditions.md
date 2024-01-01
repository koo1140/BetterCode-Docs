# Conditions

They are very usefull.
```
if value validator value then
  % your code here %
end
```

But lets learn what are the posibilities.
- first value can be any of those: string, number, bool, variable_value etc.
- second value is same as first value
- here are some validators: =, <, >
- validators can also be negative: !=, !<, !>

Here are some examples, i will let you see the patterns first:
1.
```
if user_name = "Alice" then
  console("Welcome, Alice!")
end
```
Output:
```
Welcome, Alice!
```
2.
```
if user_age > 18 then
  console("You're an adult!")
elseif user_age < 13 do
  console("You're a kid!")
else do
  console("You're a teenager!")
end
```
Output:
```
You're a teenager!
```
3.
```
if is_raining != true then
  console("It's not raining, enjoy your day!")
end
```
Output:
```
It's not raining, enjoy your day!
```
As you probably saw or not.. `user_name`, `user_age` and `is_raining` are variables.

# You completed this lesson! Congrats! 🎉
[back to docs](https://github.com/koo1140/BetterCode-Docs/blob/main/README.md)
