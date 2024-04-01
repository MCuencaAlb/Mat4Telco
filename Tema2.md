## TEMA 2 - Variables aleatórias.
Las variables aleatórias pueden ser discretas y continuas.
### Variables aleatórias discretas.  


Las más utilizadas son:  
- Bernuilli: Es el más sencillo. La variable aleatoria solo puede tomar dos valores 0 o 1. El parámetro que define la distribución de p,
    que es la probabilidad que tiene de salir 1. La probabilidad de que sea 0 es 1-p.
- Binomial: Nos da la probabilidad de que en un conjunto de experimentos aleatorios de Bernulli haya un determinado número de aciertos. El numero de valores posible
    Si realizamos el exmperimento n veces, el numero de valores posibles que puede tomar la variables serán {0,1, 2 ....n} La ecuación es:

  $$P(X=x)=\binom{n}{k}p^{k}(1-p)^{n-k}$$  
- Geometrica: Número de veces que hay que repetir la experiencia para tener el primer éxito:
 $$P(X=x)=(1-p)^{k-1}$$  
- Poisson: número de veces que sucede en un intervalo dado.
   $$P(X=x)=\frac{a^{k}}{k!}e^{-\alpha }$$  
### Variables aleatorias continuas
Función de densidad, se denota con la f minuscula:
$$f_{x}(x)=\frac{d F_{x}(x)}{dx}$$
Función de distribución, se denota con la F mayuscula:
$$F_{x}(x)=P(X\leq x)=\int_{-inf}^{x}f(x)dt$$
