Ultima parte de la tarea 1: 

8. Lanzamiento de moneda, segunda parte. Supon que tienes una moneda trucada que da una mayor probabilidad $p$ de caer sol que águila. 
  * En promedio ¿Cuántos tiros tienes que hacer para que caiga el primer sol?
  * En promedio ¿Cuántos tiros tienes que hacer hasta que te salgan 2 soles seguidos?
  * En promedio ¿Cuántos tiros tienes que hacer para que te salgan N soles seguidos? 
9. Supón que estás en la cola para comprar un boleto de cine. Hay N personas en la cola antes que tú (tú tienes un billete de 100). No hay nadie aún en la ventanilla y cuando llega el encargado advierte que no tiene cambio. El boleto cuesta 50 pesos. Cuando alguien llega a la ventanilla y el empleado no tiene cambio, le pide que espere a un lado, para atender al siguiente cliente con la esperanza de conseguir cambio. Supón que la mitad (si es $N$ es non, entonces $(N-1)/2$) de los que están en la fila tienen el cambio exacto, mientras que la otra mitad tiene billetes de 100 pesos. 
  * ¿Cuál es la probabilidad de que la persona en la ventanilla haga esperar a $n$ personas para darles su cambio?
  * Ahora supón que cada persona es igualmente probable que tenga un billete de 50 o de 100. ¿Cuál es la probabilidad de que cuando llegues a la ventanilla la persona encargada no tenga cambio?
  * Supón que para cada persona que tiene cambio, el empleado tarda 1minuto, en atenderlo, pero cada persona que no tiene cambio tarda minuto y medio además del tiempo que tarde en conseguir el cambio ¿Cuál es el tiempo promedio que esperarás en la cola antes de ser atendido? ¿Cuánto tiempo pasará en promedio hasta que te entregue el cambio? (supón que detrás de ti, la cola es infinita).
10. Caminante Aleatorio en una red cuadrada 2D. Demuestra que: un caminante aleatorio sobre una red cuadrada tiene un desplazamiento cuadrático medio de la forma $\langle (x(n)-x_0)^2\rangle \sim n$ donde $n$ es el número de pasos $x(n)$ es su posición en el paso $n$ y $x_0$ es su posición inicial. 
11. Caminante aleatorio con pasos variables. Supón ahora que el caminante tiene pasos de tamaño variable. Cada paso puede, con igual probabilidad, moverse una distancia $x$ contenida en un intervalo dado $[a,b]$. Calcula su desplazamiento cuadrático medio. 
  * ¿Qué sucede si en vez de una distribución uniforme sobre el intervalo se tiene otro tipo de distribución? 
  * Usa el resultado anterior para calcular el desplazamiento cuadrático medio de un caminante aleatorio de paso variable en el intervalo $[0,\infty)$ con una distribución exponencial
12. Supón que tienes una distribución, de la cual conoces su desviación estandar, pero no conoces su valor esperado (de un experimento, por ejemplo). Para calcular el valor esperado, puedes producir N variables aleaotrias con esa distribución y obtener su promedio. Con qué probabilidad tu medición distará menos que un $\epsilon$ dado del valor real del valor esperado? (utiliza el teorema del límite central) 
13. Una forma de definir entropía (no la más adecuada para nosotros), es medir "de alguna forma" cuán rápido se pierde la información. La definición más famosa de esto es la entropía de Shannon, donde se usa la función de masa de probabilidad $\mathrm{P}(x_i)$ de una variable aleatoria discreta $X$, con $n$ posibles valores $\Eta(X) = -\sum_{i=1}^n {\mathrm{P}(x_i) \log_b \mathrm{P}(x_i)}$. Calcula la entropía de Shannon como función de la probabilidad $p$ de sacar sol, para un tiro.  
  * ¿Para qué valores de $p$ la entropía de Shannon es máxima?
  * ¿Cuál es la entropía de Shannon de $n$ tiros?
14. Considera una caja subdividida en 2. Supon que metes n moléculas dentro. ¿Cuál es la entropía de Shannon si las subdiviciones son de volumenes iguales? 
  * ¿Como cambia la entropía si las subidiviciones tienen volúmenes diferentes?
15. Pensemos que la energía de un determinado cristal está dada por alguna propiedad de sus átomos. Estos pueden tener la propiedad 1 o la 2. Si el átomo tiene la propiedad 2, entonces aporta un poco más de energía que si tiene la propiedad 1. Llamemos $\epsilon$ la diferencia entre las energías. 
  * ¿Cuál será la energía total del sistema, con respecto a la energía del estado base (propiedad 1) si hay $n$ átomos del tipo 2 y $N-n$ del tipo 1?
  * Si hay $n$ átomos del tipo 2, ¿Cuántos estados posibles tiene el cristal? 
  * Si la entropía del sistema es $S = k log(\Omega)$ donde $\Omega$ es el número de estados y $k$ la constante de Boltzmann ¿Cuál es la entropía del sistema como función del número de átomos del tipo 1 y el número total de átomos?
  * Utiliza la fórmula de Stirling para hacer una aproximación de $S$ cuando $N$ es un número grande. 
  * Recordemos que $\frac{1}{T} = \frac{\partial S}{\partial E}$. Utiliza esto para escribir el número de átomos del tipo 1, como función de la temperatura y de N.   
