# Numbers filtering

## Description
You have two `IntStream`'s. The first stream contains even numbers and the second stream contains odd numbers. Implement a method that returns the third stream that contains _sorted_ numbers from both streams which are divisible by 3 and 5 _without_ the first two numbers.

>You need to return a prepared `IntStream` from a template method, not a list of integers. Pay attention to the method template. Do not change the signature of this method.

## Example
Sample Input 1:
```console
1 2 3 4
```

Sample Output 1:
```console
[]
```

Sample Input 2:
```console
30 75 60 90
```

Sample Output 2:
```console
[75, 90]
```

## Tags
- functional programming
- functional streams
- stream filtering