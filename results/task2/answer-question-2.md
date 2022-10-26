# Answer question 2:

-- **Una vez realizado el survey en la parte de arriba debería observarse un warning, ¿Qué es lo que indica este aviso? ¿Como solucionarías este problema de modo que el warning desaparezca?**

We can see these warnings:

![](/home/ubuntu/Desktop/PrácticasArco/higherisa.png)

That warning appears cause by the way we compile the program which is the following one:

 `g++ -g -fopenmp -o matmul matmul.cpp`

Therefore, the main problem is that we compile our program with an instruction set that is lower than the recommended by intel. Advisor-Gui recommend us to use a higher GNU compiler version  or use a higher intel compiler. We think that easiest way to fix that problem is with this syntax in the command line that is provided by intel:

`{icx|icpx} [options] file1 [file2...]  ` 

Moreover, it appears this warning which is caused by the version of intel:

![](/home/ubuntu/Desktop/PrácticasArco/otroproblema.png)

We can fix that using a higher version of intel compiler.