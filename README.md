
# philosophers

This a training project to multi-threads/multi-process progammation with the use of mutex and semaphore.
There is 3 different programs simulating a twist of the famous Dining Philosophers problem, all with the same basic rules.

```philo_one``` : multi-threads and use of mutex

```philo_two``` : multi-threads and use of semaphore

```philo_three``` : multi-processes and use of semaphore




## Deployment

Each ```philo``` folder contains a ```Makefile```

Let's take ```philo_one``` for example, 

So you can run ```make``` and then execute with the following commands

```bash
    ./philo_one number_of_philosophers time_to_die time_to_eat time_to_sleep [number_of_times_each_philosopher_must_eat]
```

For example :

```bash
    ./philo_one 4 800 200 100
```

You can now see all philosophers eat and sleep indefinitely.


Or, with the command bellow, you can see the program stop after all the philosophers have eaten twice.
```bash
    ./philo_one 4 800 200 100 2
```



## Authors

[@lenphatos](https://www.github.com/lenphatos)

