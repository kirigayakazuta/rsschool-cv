# Aleksandr Darenkov
![avatar](https://i.pinimg.com/custom_covers/222x/749568000420415111_1615657671.jpg)
## Contacts
* __Location:__ Russia, Moscow
* __Phone:__ +79033795681
* __Email:__ alexdarenkov300@gmail.com
* __Git Hub:__ kirigayakazuta

## About Me
I am an ordinary student who wants to become a front-end developer.
Ready to overcome difficulties and do everything possible to achieve the goal.

## Skils
* Python
* C/C++ (Basic)
* HTML
* CSS
* JS (Basic)

## Code Example
__Valid Parentheses from Cosewars__
_Write a function that takes a string of parentheses, and determines if the order of the parentheses is valid. The function should return true if the string is valid, and false if it's invalid._

```python
def valid_parentheses(string):
    stack = []
    for i in string:
        if i in '()' and not stack:
            stack.append(i)
            f = False
        elif stack:
            if i == ')' and stack[-1] == '(':
                stack.pop()
            elif i in '()':
                stack.append(i)
    if stack:
        return False
    else:
        return True
```

## Experience:
Made a few simple sites here is an example of one of them: [__Genshin Impact Guide__](http://f0784992.xsph.ru/tier-list.php). When creating the site, I learned to work with HTML, CSS, JS.

## Courses:
* _Stepic:_ __"Поколение Python": курс для начинающих__
* _Stepic:_ __"Поколение Python": курс для продвинутых__

## Languages:
* Russian - Native
* English - A2

