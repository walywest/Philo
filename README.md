# Concurrent Programming.

  Eat, Sleep, Spaghetti, repeat. This project is about learning how threads work by precisely timing a group of philosophers on when to pick up forks and eat spaghetti without dying from hunger.
  
## Objectives

Philosophers aims to showcase a correct synchronization of threads ([C threads](https://www.geeksforgeeks.org/multithreading-in-c/))
using [mutex_lock](https://pubs.opengroup.org/onlinepubs/009695399/functions/pthread_mutex_lock.html) to prevent data races, while also preventing the [deadlock](https://en.wikipedia.org/wiki/Deadlock).

## Usage :
Provide the simulation parameters respectively as follows :
> ./philo "number of philosophers" "maximum time wihtout eating to die" "time each philosopher will spend sleeping".

> ![alt text](https://github.com/walywest/Philo/blob/master/arguments.png)

## For more informations
This project is a simulation of a problem known as [Dining Philosophers problem](https://en.wikipedia.org/wiki/Dining_philosophers_problem).

Take a look at this (https://dotnettutorials.net/lesson/atomic-operations-in-c/)

