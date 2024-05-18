## Límites y continuidad de funciones vectoriales

### Definición

Sea $r(t): D \subset R \rightarrow R^n$ una función vectorial tal que $r(t) = (r_1(t), \ldots, r_n(t))$.

Entonces:

$$\lim_{t \to a} r(t) = \lim_{t \to a} (r_1(t), \ldots, r_n(t)) = (\lim_{t \to a} r_1(t), \ldots, \lim_{t \to a} r_n(t))$$

Por lo tanto, el límite existe si y solo si todos los límites $\lim_{t \to a} r_i(t)$ con $i=1, \ldots, n$ existen. 

#### Ejemplo

Hallar $$\lim_{t \to 0} r(t)$$ donde $$r(t) = \left( ln{(1+t)}, ~ \frac{sen{(t)}}{t}, ~ cos{(t) - 2} \right)$$

### Definición

Una función vectorial es contínua en su dominio $D$, si cada una de sus componentes en contínua en $D$.

La función vectorial r(t) es contínua en a si $$\lim_{t \to a} r(t) = r(a)$$

#### Ejemplo

La función vectorial

$$r(t) = \begin{cases}
(t,t^2) &\text{ si } t \geq 0 \\
(-1,t) &\text{ si } t < 0  
\end{cases}$$

tiene dominio $R$ pero no es continua en $R$ porque su primera componente

$$r_1(t) = \begin{cases}
t &\text{ si } t \geq 0 \\
-1 &\text{ si } t < 0  
\end{cases}$$

no es contínua aún cuando su segunda componente

$$r_2(t) = \begin{cases}
t^2 &\text{ si } t \geq 0 \\
t &\text{ si } t < 0  
\end{cases}$$

si es contínua.

**Nota:** Hacer las gráficas de las componentes. 

