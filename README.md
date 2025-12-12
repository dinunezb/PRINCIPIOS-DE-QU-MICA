# PRINCIPIOS DE QUÍMICA: Taller #2 Entropía y segunda ley de la termodinámica

-*Diego Alejandro Núñez Bernal* 

-*Salome Gutierrez Granada* 

-*Maria Claudia Colmenares Beltran*

- ## Definiciones de entropía
- 1 Definición historica
  
  La entropía es un concepto de la termodinámica que surgió en el siglo XIX con el estudio de los motores de calor y la eficiencia energética. Los primeros motores impulsados por combustión eran altamente ineficientes ya que gran parte de la energía liberada se “perdía” y no se transformaba en trabajo útil, lo que llevó a los físicos a buscar una forma de cuantificar esa energía no aprovechable.

  En respuesta a este problema en la década de 1850 el físico Alemán Rudolf Clausius introdujo el concepto de entropía como una medida de cómo se reparte el calor cuando pasa de un cuerpo a otro. Para él el aumento de entropía indica la parte del calor que se dispersa de forma irreversible al moverse hacia zonas más frías, y que ya no puede transformarse en trabajo.
  Su formula principal:

  $$
  dS = dQ / T
  $$

<div align="center">
    
| Símbolo | Significado |
|----------|-----------|
| dS  | Diferencial de entropía    | 
| dQ   | Diferencial del calor   |
| T  | Temperatura absoluta del cuerpo al momento de suministrar calor    |

</div>


  Expresa la relación entre la cantidad de calor que se intercambia y la temperatura a la que se reparte esa energía. Así que la entropía mide qué tanto se “esparce” el calor. Cuanto más uniforme es esa distribución, mayor es la entropía. Un proceso irreversible, como cuando el calor pasa espontáneamente de un objeto caliente a uno frío, muestra cómo esta dispersión de energía crece de manera inevitable.



  En términos generales la entropía es una medida de qué tan dispersa está la energía dentro de un sistema y de lo difícil que es volver a concentrarla por completo para obtener trabajo útil.[^1]


  ---
- 2 Definición bajo la termodinámica estadística:

  Para entender la entropía bajo este paradigma primero debemos definir que son los micro y macro estados.
  
  Definamos a modo de ilustración un sistema, un mol de gas confinado cuya concentración, presión y temperatura son constantes, al observar recordamos que cada una de las partículas confinadas está en movimiento, por lo que en cada instante todas y cada una de ellas van a tener una posición y energía cinética partículas.

  El estado en el cual las propiedades macroscópicas han sido definidas (nuestro gas confinado) es un macro estado, los microestados van a ser todas las posibilidades dentro de ese macro estado, es decir todas las posibles combinaciones de energía cinética y ubicación de cada una de las partículas dentro del macro estado.

  Por consiguiente cada macro estado o estado termodinámico contiene dentro de si un número de microestados posibles (W) .

$$
S = k\ ln W
$$

<div align="center">
    
| Símbolo | Significado |
|----------|-----------|
| S  | Entropía    | 
| k   | Constante de Bolztmann   |
| W  | Numero de microestados posibles    |

</div>

  Por lo que vemos la entropía como la medida de la cantidad de microestados posibles dentro de un estado macroscópico determinado.[^2][^3]

  ---

- 3 Definición bajo la gestión de información:

    La entropía, en el contexto de la gestión de la información, es una medida matemática que describe el estado de desorganización o desorden de un sistema. Este concepto se define por una relación inversa con la información estructural Is, partiendo de la premisa de que toda estructura organizada contiene información. En consecuencia, un aumento de entropía se traduce en una pérdida de organización y, por lo tanto, una pérdida de información estructural. Como indicador de la calidad de la información, la baja entropía es deseable, pues refleja un alto grado de organización y estructura del sistema, mientras que los valores elevados de entropía indican un mayor desorden.
  

$$
H = -K \sum_{i=1}^{n} p_i \ln(p_i)
$$

 <div align="center">
    
| Símbolo | Significado |
|----------|-----------|
| H  | Entropía del sistema    | 
| k   | Constante de proporcionalidad   |
| $p_i$  | Probabilidad del evento i    |

</div>

 [^4][^5]

  --- 
- 4 Entropía de entrelazamiento
  
  La entropía de entrelazamiento se define como la medida cuantitativa fundamental utilizada para cuantificar el grado de entrelazamiento cuántico (o correlaciones estadísticas) que existe entre un subsistema (por ejemplo, una región del espacio V) y su complemento ($\bar{V}$). Cuando el estado global del sistema es puro (es decir, sobre el cual se tiene el máximo conocimiento posible), la Entropía de Entrelazamiento se corresponde con la Entropía de von Neumann del subsistema, calculada a partir de su matriz densidad reducida ($\rho$). Esta magnitud, que permite medir la incertidumbre inherente al subsistema local, se expresa formalmente mediante la ecuación:

$$
S(\rho) = -Tr \rho (\ln\rho)
$$

<div align="center">
    
| Símbolo | Significado |
|----------|-----------|
| S($\rho$)  |Entropía de Von Neymann     | 
| $\rho$   | Matriz de densidad reducida   |
| Tr  | Traza    |

</div>

[^6] [^7]

  ---
- 5 Entropía holográfica

  La entropía, en el contexto de la dimensionalidad de la información, se fundamenta en el Principio Holográfico. Este principio, el cual se apoya de la Termodinámica de Agujeros Negros (donde la entropía S mide la información inaccesible de la materia que cayó en el agujero), postula que los sistemas físicos son inherentemente bidimensionales en el sentido de la información requerida para describirlos.

  El núcleo de esta idea es que la entropía o información máxima que puede contener una región del espacio-tiempo tridimensional está ligada al área de su frontera, y no a su volumen, sugiriendo que el mundo es un "holograma". Esta conceptualización se cuantifica mediante el Límite Holográfico, que sugiere que el número de grados de libertad se corresponde con el área superficial. Esta limitación general se expresa formalmente a través del Límite de Entropía Covariante, cuya expresión es: [^8][^9][^10]

$$
S[L(B)] \leq \frac{A(B)}{4}
$$

<div align="center">
    
| Símbolo | Significado |
|----------|-----------|
| S[L(B)]  | Entropía total de la materia, o la incertidumbre, contenida en una capa de luz   | 
| L   | Hipersuperficie nula adyacente a la superficie B    |
| A[B]  | Área superficial de la frontera espacial bidoimensional B que limita la región    |
| 1/4 |Factor que indica la capacidad máxima de información (aproximandamente un bit por cada área de Planck al cuadrado) |

</div>


---
- ## Segunda Ley de la termodinámica
  
  La segunda ley de la termodinámica dice que en cualquier proceso real la entropía total del universo nunca disminuye. Esto quiere decir que los procesos naturales tienen una dirección preferida y que cada transformación irreversible genera más entropía.

  Generalmente esta ley se ha explicado de varias maneras similares. Por ejemplo, Clausius dijo que el calor no puede pasar por sí solo de un cuerpo frío a uno caliente. Kelvin–Planck afirmó que no es posible convertir todo el calor absorbido en trabajo útil sin que ocurran otros cambios. Y Carathéodory señaló que cerca de cualquier estado existen otros estados que no se pueden alcanzar mediante procesos adiabáticos (procesos sin intercambio de calor)

  En una definición más moderna propuesta por Lieb y Yngvason, existe una función llamada entropía que ordena los estados según si se pueden transformar adiabáticamente unos en otros. Es decir, si un estado X puede convertirse en un estado Y mediante un proceso adiabático, entonces la entropía cumple que S(X) ≤ S(Y). Y en los procesos irreversibles, esta desigualdad se cumple de manera estricta S(X) < S(Y).[^11] [^12]

  *Ecuación fundamental de la segunda ley*

  Para un proceso cualquiera, la ecuación expresada en términos del universo es:

$$
ΔSuniverso = ΔSsistema + ΔSentorno ≥ 0
$$
 <div align="center">
   
| Valor de ΔS | Significado |
|----------|-----------|
| Si ΔSuniverso = 0  | Es un proceso reversible   | 
| Si ΔSuniverso > 0   | Es un proceso irreversible   |
|Si ΔSuniverso < 0  | Es imposible por la segunda ley    |

</div>

  El enunciado de la segunda ley es aplicable a las definiciones de entropía anteriormente escritas, la entropía del universo siempre aumenta, por ejemplo, bajo la definición de los microestados todo sistema va a tender al estado más probable (las moleculas de los gases distribuidas en lugar de unidas en un unico punto), o bajo el paradigma de la información, todo sistema va a evolucionar a un estado con mayor información perdida. La ley es universal, los diferentes paradigmas son herramientas.
  

---
## Bibliografía
[^1]: Clausius, R. (1879). The mechanical theory of heat: With its applications to the steam-engine and to the physical properties of bodies (W. R. Browne, Trad.). Macmillan and Co.
[^2]: Çengel, Y. A., & Boles, M. A. (with Martínez Bautista, A. L.). (2015). Termodinámica. McGraw-Hill.
[^3]: Brown, T. L., LeMay, H. E., Bursten, B. E., Murphy, C. J., & Woodward, P. M. (with García Hernández, A. E.). (2014). Química: La ciencia central (12a ed.). Pearson Educación.
[^4]: Tarragó, J. C. P., Ávila, R. M. Á., Gallardo, M. D. C. E., & Gálvez, D. L. D. (2020). La gestión de la información en un enfoque a partir de la entropía. Revista Científica Sinapsis, 1(16).
[^5]: Stonier, T. (1989). Towards a general theory of information II: Information and entropy. Aslib Proceedings, 41(2), 41-55. https://doi.org/10.1108/eb051124

[^6]: Benedetti, V. (2019). Entropía de entrelazamiento de gravitones linealizados (Bachelor's thesis).
[^7]: Siegel, R. T., & Tapia, R. M. (2011). Información, entrelazamiento y relatividad. Revista Española de Física, 19(1).
[^8]: García López, L. A. (2007). Termodinámica de agujeros negros y teoría de información.
[^9]: Naz, S. M. (2003). El principio holográfico. Isagogé, 9.
[^10]: Bousso, R. (2002). The holographic principle. arXiv.
[^11]: Lieb, E. H., & Yngvason, J. (1998). A Guide to Entropy and the Second Law. Physics Report
[^12]: Callen, H. B. (1985). Thermodynamics and an Introduction to Thermostatistics. Wiley.

