# Report task 4

**4- Compara y analiza los resultados haciendo énfasis en las medidas de tiempo, rendimiento y memoria:** 

We obtain **similar results** for both snapshots if we run the code in our local computer or using devcloud. As we can see in both of them we are not only limited by the software, but also by the hardware to reach the peak.

-- For the **time measures**,  the program *elapsed time* when we execute the program in devcloud is 0,1 seconds whereas if we run the program locally the time elapsed is 0,21 seconds. As consecuence,  according to the time elapsed it will be better to run the program in devcloud. 

-- Taking in to account that the **performance** *= 1/CPU time*, CPU time locally = 0,2 s and  CPU time remote = 0,09s: 

- <u>Performance in our computer:</u> 1/0,2 = 5 

- <u>Performance in our remote/devcloud:</u>   1/0,09 = 11,1 

- <u>Performance in our devcloud/our computer:</u>  11,1/5 = 2,2  

Then, we can conclude that the performance when running the code in devcloud is **2,2 times	better. **

Moreover, if we compare the GFLOPS (number of floating point operations per  second), which are also a performance measure, are **higher** using devcloud.

-- In terms of **memory** : the results are very similar  being a bit better the ones of our computers. The use of the memory is  6,12% in remote and 6,51% in our local device. In addition, we have to  take into account that our computer has cache memories. 