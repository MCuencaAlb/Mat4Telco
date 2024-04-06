## TEMA 1- Introducción a la probabilidad
|   | Con repeticion | Sin repetición|
|---|----------|---------|
|Orden| $VR_{n,m}=n^{m}$|$V_{n,m}=n!-(n-m)!$|
|Sin Orden|$CR_{n,m}=\binom{n-1+m}{n-1}$|$C_{n,m}=\binom{n}{m}=\frac{n!}{m!(n-m)!}$|

$$P(A^{c})=1-P(A)$$

$$P(A\cup B)=P(A)+P(B)-P(A\cap B )$$  

Ley de Laplace para espacios equiprobables:
$P(A)=\frac {casos Favorables}{total casos}$  

Si no son independiente:
$$P(A \cap B)= P(A|B) P(B)$$

Para sucesos independientes: $P(A \cap B)= P(A)P(B)$


Teoremas de la probabilidad total y Teorema de Bayes:
$$P(B)=P(B|A_{1})P(A_{1}+P(B|A_{2})P(A_{2}+P(B|A_{3})P(A_{3}+....+P(B|A_{n})P(A_{n}$$
$$P(A_{i}|B)=\frac{P(B|A-{i})P(A_{i}}{P(B|A_{1})P(A_{1}+P(B|A_{2})P(A_{2}+P(B|A_{3})P(A_{3}+....+P(B|A_{n})P(A_{n}}$$
