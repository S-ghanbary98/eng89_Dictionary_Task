# Dict Project

- In this project, a dictionary known as story1 is created with key values of `middle`, `start`, `end`.

```python
story1 = {
    "start" : "There was once a hare who was friends with a tortoise. One day, he challenged the tortoise to a race. Seeing how slow the tortoise was going, the hare thought he’ll win this easily.",
    "middle" : "So he took a nap while the tortoise kept on going. When the hare woke up, he saw that the tortoise was already at the finish line.",
    "end" : "Much to his chagrin, the tortoise won the race while he was busy sleeping."
}
```

- The dictionary is printed.
`print(story1)`
  
- The type is revealed.

`print(type(story1))`

- The `KEY` values are revealed.

`print(story1.keys())`
  
- The `Value` values are revealed.

`print(story1.values())`

- The indivdual values are printed using the keys
```
print(story1["start"])
print(story1["middle"])
print(story1["end"])
```

- New `KEY-VALUE` pair added
```
story1['hero'] = "Superman"
print(story1)
```