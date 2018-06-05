---
  title: "Test"
  description: "Test"
  v2: false

---
## Sample exercise

```yaml
type: NormalExercise
lang: python
xp: 100
skills: 2
key: 4dfc16f67b



```

Like we store numbers and text, we can also store lists. We will work with lists a lot in Python, and there will be more extensive chapters on working with lists. In this section we focus on storing lists.

Storing in principle works like storing numbers and strings, we use a name followed by an equal sign:

`three_primes = `

After that, something special happens, we need to use an square bracket to enclose the list in:

`three_primes = [2, 3, 5]`

The items are separated with comma's. A space is not needed, but advised!


`@instructions`
Change the value of five_primes such that it contains the values 2, 3, 5, 7, 11.

Note that again, line 2 prints the list. There is no special syntax for printing lists.

`@hint`


`@pre_exercise_code`
```{python}
__ = "change \"__\" such that you get the right output"
```
`@sample_code`
```{python}
five_primes = [__] 
print(five_primes)
```

`@sct`
```{python}
Ex().has_output(r"[2, 3, 5, 7, 11]")
success_msg("Well done!")
```





---
## Insert exercise title here

```yaml
type: NormalExercise

xp: 100

key: bf8f4e6ea3



```














---
## Insert exercise title here

```yaml
type: NormalExercise

xp: 100

key: 0d2117c6cb



```

Test

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}
__ = "blank"
def assertEqual(x,y):
    if x == y:
        pass
    else:
        message = str(x) + ' is not ' + str(y)
        raise AssertionError(message)  
```
`@sample_code`
```{python}
cities_set = {'New York', 'Boston', 'Seoul', 'Rotterdam', 'Cape Town', 'New York', 'Rotterdam'}
assertEqual(__, cities_set)
```
`@solution`
```{python}
cities_set = {'New York', 'Boston', 'Seoul', 'Rotterdam', 'Cape Town', 'New York', 'Rotterdam'}
assertEqual({'New York', 'Boston', 'Seoul', 'Rotterdam', 'Cape Town', 'New York', 'Rotterdam'}, cities_set)

```




