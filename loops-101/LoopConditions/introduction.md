```ngMeta
name: Introduction to Loops
completion_method: manual
```

# Understanding Loop Conditions

Yeh code dekhte hain

```python
i = 1
while i < 100:
  print(i)
  i = i + 1
```

Yeh code 1 se leke 99 tak numbers ko print kar dega. Lekin agar iss code ko ache se samajhne ke liye har line mein kya ho raha hai woh samajhte hain.

1. `i = 1` yahan pe humne `i` naam ka variable define kiya aur usme `1` value daali.
2. `while i < 100` yahan humne ek loop define kara. Hindi mein iska matlab hai ki jab tak `i` ki value 100 se kam hai tab tak is while ke andar likha hua kaam karte raho. Toh yeh kaam tab tak hota rahega jab i ki value 100 se kam hai.
3. `print(i)` waali line loop ke andar likhi hui hai. Toh jab tak i ki value 100 se kam hai tab tak har baar loop chalega toh har baar yeh line chalegi.
4. `i = i + 1` Yeh waali line humare counter ko badayegi. Ek tareeke se yeh waali line determine karti hai ki humara loop kitni baar chalega.

Yahan pe `i = i + 1` aur `while i < 100` sabse important statements mein se hai. Yeh video dekh ke hum samjhenge ki inn lines ka exact matlab kya hai aur computer inko kaise samajhta hai. Isse hum better tareeke se loops likh payenge.

## Contents of Video
1. What does it mean to write the `i < 100` in the following loop?
```python
i = 1
while i <= 10:
  print(i)
  i = i + 1
```
2. How does the loop run? Every time the code within the loop block is executed the condition is evaluated once again and until the condition is true the loop keeps on running. Basically the condition results into a boolean and if the boolean is True then the loop is run otherwise it is not run.
3. Apart from this we can also put the statement like this.
```python
i = 1
while i != 10:
  print(i)
  i = i + 1
```
4.
