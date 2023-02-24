# Adding Numbers

Create a function that takes two number strings and returns their sum as a string.

Examples
> `add("111", "111")` ➞ `"222"`
>
> `add("10", "80")` ➞ `"90"`
>
> `add("", "20")` ➞ `"Invalid Operation"`


*Notes*:
If any input is `""` or `None`, return `"Invalid Operation"`.

def add(x, y):
    if x == "" or  y == "":
        return "Invalid Operation" 
        
    result = int(x) + int(y)
    result = str(result)
    return result    

[Start Problem](https://replit.com/team/whs-spring-2023/Adding-Numbers)
