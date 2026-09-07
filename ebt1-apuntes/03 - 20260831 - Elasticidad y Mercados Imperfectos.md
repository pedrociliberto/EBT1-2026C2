## Clase 3 - Elasticidad y Mercados Imperfectos

### Módulo 1: La Elasticidad — Medición y Sensibilidad del Mercado

- Sensibilidad o grado de respuesta de una **variable económica ante variaciones en otra**. 
- Permite evaluar no solo la dirección del cambio (ej. si el precio sube, la cantidad demandada baja), sino su magnitud exacta.
#### Concepto y Propiedades Generales

- **Adimensionalidad:** Se expresa como un número puro sin unidades de medida. Esto habilita la comparación directa de la sensibilidad entre bienes o servicios heterogéneos (como pasajes de avión, gigabytes de datos o alimentos).
- **Definición matemática:** Es el cociente entre la variación porcentual de una variable dependiente y la variación porcentual de una variable independiente.
#### Elasticidad-Precio de la Demanda ($E_p$)

Mide el porcentaje en que varía la cantidad demandada ($Q$) ante un cambio del 1% en el precio ($P$) del bien.
$$\text{Fórmula general: } E_p = \frac{\%\Delta Q}{\%\Delta P} = \frac{\Delta Q / Q}{\Delta P / P} = \left(\frac{P}{Q}\right) \cdot \left(\frac{\Delta Q}{\Delta P}\right)$$
Debido a la ley de la demanda, este resultado es habitualmente negativo. Por convención analítica, se toma su valor absoluto ($\vert{}E_p\vert{}$).

##### El Problema del Punto de Partida y la Fórmula del Punto Medio

Calcular la elasticidad mediante variaciones porcentuales simples genera el problema de que el resultado depende del sentido del cambio. Por ejemplo, en un tramo donde $P$ varía de $2,00 a $2,50 y $Q$ pasa de 7 a 4 unidades:

- De \$2,00 a \$2,50: $\%\Delta P = +25\%$, $\%\Delta Q = -42,8\% \implies E_p = 1,71$.
- De \$2,50 a \$2,00: $\%\Delta P = -20\%$, $\%\Delta Q = +75\% \implies E_p = 3,75$.

Para evitar esta ambigüedad, se utiliza la **fórmula del punto medio (o elasticidad arco)**, promediando los valores iniciales y finales:

$$E_p = \frac{\frac{\Delta Q}{(Q_1 + Q_2)/2}}{\frac{\Delta P}{(P_1 + P_2)/2}}$$

Aplicando este método al ejemplo, la elasticidad del tramo resulta en **2,45** en ambas direcciones.

##### Los 5 Tipos de Elasticidad de la Demanda

| **Tipo de Elasticidad**      | **Condición (Ep​)** | **Sensibilidad (%ΔQ vs %ΔP)** | **Descripción de la Curva**                                                        | **Ejemplo Comercial**                           |
| ---------------------------- | ------------------- | ----------------------------- | ---------------------------------------------------------------------------------- | ----------------------------------------------- |
| **Perfectamente Inelástica** | $E_p = 0$           | $\%\Delta Q = 0$              | Recta completamente vertical (aunque cambie mucho el precio no varía la cantidad). | Medicamentos esenciales (ej. insulina).         |
| **Inelástica**               | $0 < E_p < 1$       | $\%\Delta Q < \%\Delta P$     | Curva empinada; la cantidad varía menos que el precio.                             | Tarifas eléctricas, servicios SaaS.             |
| **Unitaria**                 | $E_p = 1$           | $\%\Delta Q = \%\Delta P$     | Modificación proporcional entre precio y cantidad.                                 | Frontera teórica donde el gasto total no varía. |
| **Elástica**                 | $E_p > 1$           | $\%\Delta Q > \%\Delta P$     | Curva acostada; la cantidad varía más que el precio.                               | Pasajes de avión, viajes de turismo.            |
| **Perfectamente Elástica**   | $E_p = \infty$      | $\%\Delta P = 0$              | Recta completamente horizontal.                                                    | Commoditites (ej. tonelada de soja).            |

##### Relación entre Elasticidad e Ingreso Total (Facturación)

El Ingreso Total ($IT$) es igual a $P \times Q$. Modificar los precios impacta directamente en los ingresos según la elasticidad:

- **Demanda Inelástica ($E_p < 1$):** Si el precio sube un 10%, $Q$ cae menos de un 10% (ej. 5%). El **Ingreso Total aumenta**.
- **Demanda Unitaria ($E_p = 1$):** Un aumento del 10% en el precio compensa exactamente la caída del 10% en $Q$. El **Ingreso Total no cambia**.
- **Demanda Elástica ($E_p > 1$):** Si el precio sube un 10%, $Q$ disminuye en mayor proporción (ej. 20%). El **Ingreso Total disminuye**.

#### Elasticidad-Ingreso y Elasticidad-Cruzada

- **Elasticidad-Ingreso ($E_y$):** Mide la variación porcentual de la cantidad demandada ante cambios en el ingreso ($Y$) de los consumidores ($E_y = \frac{\%\Delta Q}{\%\Delta Y}$).
    - **Bien de Lujo ($E_y > 1$):** El consumo crece más que proporcionalmente al incremento del ingreso.
    - **Bien Normal ($0 \le E_y \le 1$):** El consumo crece en menor proporción que el ingreso.
    - **Bien Inferior ($E_y < 0$):** El consumo disminuye cuando aumenta el ingreso.
- **Elasticidad-Cruzada ($E_{xy}$):** Mide la respuesta de la demanda del bien $X$ ante variaciones en el precio del bien $Y$ ($E_{xy} = \frac{\%\Delta Q_x}{\%\Delta P_y}$).
    - **Sustitutos ($E_{xy} > 0$):** Al aumentar el precio de $Y$, sube la demanda de $X$ (ej. Coca-Cola y Pepsi).
    - **Complementarios ($E_{xy} < 0$):** Al aumentar el precio de $Y$, cae la demanda de $X$ (ej. impresoras y cartuchos).
    - **Independientes ($E_{xy} \approx 0$):** El precio de $Y$ no afecta la demanda de $X$ (ej. pan y bicicletas).
#### Elasticidad-Precio de la Oferta ($E_o$)

Mide la respuesta porcentual de la cantidad ofertada ante variaciones porcentuales del precio ($E_o = \frac{\%\Delta Q_s}{\%\Delta P}$).

- **Signo Positivo:** Debido a la ley de la oferta, su valor es positivo.
- **El Factor Tiempo:** A corto plazo, la oferta tiende a ser inelástica por restricciones operativas o productivas; a largo plazo, la flexibilidad aumenta y la oferta se vuelve más elástica.
- **Tipos de Elasticidad de la Oferta:** Sigue la misma clasificación técnica ($E_o = 0$, $E_o < 1$, $E_o = 1$, $E_o > 1$, $E_o = \infty$) con pendiente positiva.

#### Determinantes de la Elasticidad

- **Determinantes de la Demanda:**
    - Existencia de sustitutos cercanos.
    - Grado de necesidad del bien era necesidad vs. lujo).
    - Peso del bien dentro del presupuesto del consumidor.
    - Horizonte temporal de evaluación.
    - Definición del mercado (estrecha o amplia).
- **Determinantes de la Oferta:**
    - Disponibilidad de capacidad ociosa en planta.
    - Facilidad de acceso y contratación de insumos o personal.
    - Capacidad de almacenamiento o invencibilidad del producto.
    - Tiempo del vendedor para ajustar procesos.
### Módulo 2: Competencia Perfecta vs. Realidad del Mercado

El modelo básico de oferta y demanda asume un escenario ideal denominado **Competencia Perfecta**.

#### Las 5 Condiciones de la Competencia Perfecta

- **Muchos Oferentes:** Atomización del mercado; ninguna firma influye individualmente.
- **Información Perfecta:** Transparencia total de costos, precios y tecnología.
- **Bien Homogéneo:** Productos idénticos e indistinguibles entre competidores.
- **Sin Barreras de Entrada o Salida:** Cero costos para ingresar o abandonar la industria.
- **Nadie Fija el Precio (Tomadores de Precios):** Ninguna empresa posee poder para alterar las condiciones del mercado.
#### La Brecha con la Realidad

En la práctica económica, estas condiciones no suelen cumplirse simultáneamente. El incumplimiento de al menos una de las condiciones genera las **imperfecciones de mercado**.

### Módulo 3: Estructuras de Mercado Imperfecto

Las estructuras imperfectas se definen según el nivel de concentración de la oferta (o la demanda) y la capacidad de fijación de precios.

#### 1. Monopolio

- **Estructura:** Un único vendedor abastece a todo el mercado.
- **Información y Producto:** Información perfecta; existe un solo bien sin sustitutos cercanos.
- **Barreras y Fijación:** Barreras insuperables de entrada. La empresa posee control total del precio (es fijadora de precios).
- **Análisis de Eficiencia e Ingreso Marginal ($I_{mg}$):**
    - Para vender una unidad adicional, el monopolista debe reducir el precio de _todas_ las unidades vendidas, por lo que el $I_{mg}$ cae más rápido que la curva de Demanda.
    - Produce una cantidad menor ($Q_m$) y a un precio mayor ($P_m$) en comparación con el equilibrio competitivo ($Q_c, P_c$).
    - **Pérdida Irrecuperable de Eficiencia:** Genera una pérdida de bienestar social (representada geométricamente por un triángulo de eficiencia perdida), correspondiente a transacciones donde la valoración del cliente superaba el costo marginal pero no se concretaron por el elevado precio.
#### 2. Oligopolio

- **Estructura:** Pocas empresas domina el mercado.
- **Interdependencia Estratégica:** Cada decisión comercial de una firma (precio, volumen, innovación) impacta directamente en las decisiones de sus competidoras.
- **Información y Producto:** Información imperfecta; el bien puede ser homogéneo o diferenciado.
- **Barreras:** Elevadas por necesidades de inversión de capital y economías de escala.
#### 3. Competencia Monopólica

- **Estructura:** Gran cantidad de oferentes.
- **Diferenciación del Producto:** Cada empresa vende un producto ligeramente distinto, lo que le otorga un pequeño margen de poder para fijar precios sobre su nicho (posee una curva de demanda con pendiente negativa local).
- **Barreras e Información:** Bajas barreras de entrada e información imperfecta. Este es el modelo representativo de la mayoría de las soluciones de software y productos de consumo.
#### Cuadro Comparativo de Estructuras de Mercado

|**Característica**|**Competencia Perfecta**|**Monopolio**|**Oligopolio**|**Competencia Monopólica**|
|---|---|---|---|---|
|**N° de Empresas**|Muchas|Una|Pocas|Muchas|
|**Información**|Perfecta|Perfecta|Imperfecta|Imperfecta|
|**Tipo de Bien**|Homogéneo|Producto Único|Homogéneo o Diferenciado|Diferenciado|
|**Barreras de Entrada**|Inexistentes|Monopolio natural, patentes, tecnología|Fuertes inversiones, escala|Bajas|
|**Poder sobre el Precio**|Nulo (Tomador)|Absoluto|Alto|Bajo pero existente|

#### Imperfecciones del Lado de la Demanda

- **Monopsonio:** Mercado con un **único comprador** frente a múltiples vendedores. El comprador ejerce poder de mercado imponiendo el precio de compra (ej. contratista único estatal o procesador regional de un insumo).
- **Oligopsonio:** Mercado concentrado en **pocos compradores** que absorben la oferta de múltiples vendedores dispersos (ej. grandes cadenas supermercadas frente a productores agrícolas).

### Módulo 4: Barreras de Entrada y Aplicación en Empresas de Base Tecnológica (EBT)

Las barreras de entrada definen y sostienen la imperfección del mercado a lo largo del tiempo.
#### Tipos de Barreras a la Entrada

- **Monopolio Natural:** Surge por elevadas economías de escala donde una sola empresa cubre la demanda total a costos unitarios más bajos que si compitieran varias.
- **Control de Factores Productivos:** Dominio exclusivo de un recurso o insumo crítico (ej. yacimientos de litio, espectro radioeléctrico).
- **Patentes y Regulaciones:** Concesiones legales de exclusividad otorgadas por el Estado para incentivar la investigación y desarrollo.
- **Tecnología y Efectos de Red:** Mercados donde el valor del producto para un usuario aumenta a medida que crece la base total de usuarios (ej. redes sociales, plataformas multipartes).

#### Estrategia Económica para Empresas de Base Tecnológica (EBT)

- **Estrategias de Precios e Inelasticidad:** La conversión de clientes hacia contratos anuales o la integración profunda en procesos clave reduce la sensibilidad al precio, permitiendo ajustes sin pérdidas masivas de volumen.
- **Diferenciación:** En entornos de competencia monopólica como el desarrollo de software, la ventaja competitiva proviene de la diferenciación funcional más que de competir por costo.
- **Construcción de Fosas Competitivas (Moats):** Desarrollo de activos intangibles como propiedad intelectual (patentes), acumulación de datos propietarios y generación de altos costos de cambio para el cliente.