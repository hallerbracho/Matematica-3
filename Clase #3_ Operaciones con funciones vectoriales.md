## Funciones vectoriales

### Definición de función vectorial

Una **función vectorial** de variable real es una función $f: D \subset R \rightarrow R^n$, donde $D$ se llama dominio de $f$.

Denotaremos la función vectorial $r(t)$ como $$r(t) = (r_1(t), r_2(t), \ldots, r_n(t))$$

donde $r_i(t)$ son funciones escalares (funciones reales de variable real) llamadas componentes o coordenadas de la función. 

Geométricamente una función vectorial $r(t)$ es una trayectoria de un punto móvil en $R^n$. Para cada valor del parámetro $t$ obtenemos el vector de posición $r(t)$ asociado al valor $t$.

El **dominio** $D$ de una función vectorial $r(t) = (r_1(t), r_2(t), \ldots, r_n(t))$ es la intersección de los dominios de las funciones $r_i(t)$. 

#### Ejemplos

Hallar el dominio de 

1. $r(t) = (t,t^2)$
2. $r(t) = (\frac{1}{\sqrt{1-t}},t^2)$

### Operaciones con funciones vectoriales

Las operaciones entre funciones vectoriales se definen, si las funciones toman valores en el mismo espacio vectorial $R^n$.

Sean $r(t) = (r_1(t), r_2(t), \ldots, r_n(t))$ y $s(t) = (s_1(t), s_2(t), \ldots, s_n(t))$ dos funciones vectoriales en $R^n$ y $c$ un número real. Entonces:

1. $c \cdot r(t) = (c \cdot r_1(t), c \cdot r_2(t), \ldots, c \cdot r_n(t))$
2. $r(t) + s(t) = (r_1(t) + s_1(t), \ldots, r_n(t) + s_n(t))$
3. $r(t) - s(t) = (r_1(t) - s_1(t), \ldots, r_n(t) - s_n(t))$
4. $r(t) \cdot s(t) = (r_1(t) \cdot s_1(t) + \cdots + r_n(t)s_n(t))$

El producto vectorial, o producto cruz, de dos funciones vectoriales se define de forma análoga. 

Si tienen valores en $R^2$:

$$r(t) \times s(t) = \begin{vmatrix} r_1(t) & r_2(t) \\ s_1(t) & s_2(t) \end{vmatrix} = r_1(t) s_2(t) - s_1(t) r_2(t)$$

Si tienen valores en $R^3$:

$$r(t) \times s(t) = \begin{vmatrix} i & j & k \\ r_1(t) & r_2(t) & r_3(t) \\ s_1(t) & s_2(t) & s_3(t) \end{vmatrix}$$







