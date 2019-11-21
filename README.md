# Parallelize Function

Note that ```QFuture``` is a value. You can store it very efficiently in any vector container that will manage the memory for you. You can iterate such a container using range-for etc.

Six appraoches are considered in this project to show to Parallelize a Function.

The time taken by those six approaches:

```
sum: 4999995000000.000000 took 0.015778 ms/item
sum: 4999995000000.000000 took 0.003631 ms/item
sum: 4999995000000.000000 took 0.003610 ms/item
sum: 4999995000000.000000 took 0.005414 ms/item
sum: 4999995000000.000000 took 0.000011 ms/item
sum: 4999995000000.000000 took 0.000008 ms/item
```

Original Repository: https://github.com/KubaO/stackoverflown/tree/master/questions/future-ranges-49107082
Article on StackOverflow: https://stackoverflow.com/questions/49107082/qfuture-memoryleak
 
 
