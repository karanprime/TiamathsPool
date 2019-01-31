# TiamathsPool
Predicting Chaos using Reservoir Computing

> *"Chaos: When the present determines the future, but the approximate present does not approximately determine the future."* - Edward Lorrez


Chaotic processes are systems that are highly sensitive to initial conditions. A famous example of a chaotic process in the butterfly effect: a tornado in Georgia is the result of a butterfly flapping its wings in China. The only way to predict chaotic system is analytically. For systems of many variables, eg weather, chemical reactions etc, running an analytically calculating the state of the system at each time step would require a prohibitive amount of computation. In this project, I use a technique called Reservoir Computing with a reservoir being a class of Recurrent Neural Networks called Echo State Networks to predict the two chaotic systems: Mackey-Glass, consiting of only one time-varying variable and Chua's Circuit, consisting of three time varying variables. While my learner is effective at learning Mackey-Glass, predicting Chua's circuit works well only for short amounts of time.

This is very much a work in progress.

Current ToDos:
* Explain Chua's Circuit 
* Discuss/Conclude results
* Clean code and open source it
* References
