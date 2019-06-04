# preprocessing-pipeline
---

Code in this repo is for our Lambda Labs 13 project.

# notebooks
---

.ipynb reside here if you would like to see what we've been working on and testing.

# scala
---

All Scala packages and projects live here.

#### reddit-streaming
---

[**Why Reddit?**](https://github.com/lambda-labs-13-stock-price/preprocessing-pipeline/tree/chris-louie/scala/reddit-streaming)


# examples
---

Some examples are written in Python to test `async` and `await`

#### EX:
---
```python
...
async def factorial(name, number):
    f = 1
    for i in range(2, number+1):
        print('Task {}: Compute factorial({})'.format(name, i))
        await custom_sleep()
        f *= i
        print('Task {}: factorial({}) is {}\n'.format(name, number, f))

...
```

Other examples in the future will be written in Scala to test the usage of Apache programs.

