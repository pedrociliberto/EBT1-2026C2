## Clase 9 - Tiempo del Dinero 1
### Fundamentos de Finanzas y Objetivo de la Empresa

Las finanzas representan el área de la economía dedicada al estudio de la obtención y administración del capital (dinero), abarcando decisiones de inversión, financiamiento, ahorro y la gestión del riesgo.

- **Enfoque en Flujos Netos de Efectivo (_Cash Flow_):** Las finanzas trabajan directamente con entradas ($+$) y salidas ($-$) efectivas de dinero en lugar de registros contables devengados. La determinación precisa de los flujos netos de efectivo resulta esencial para medir y calcular el valor real de una firma.
- **Objetivo Financiero de la Empresa:** El objetivo central de la empresa es **maximizar su valor corporativo**, criterio bajo el cual deben alinearse todas las decisiones estratégicas. La meta tradicional de maximizar utilidades ($\text{monto}/\text{período}$) resulta inadecuada debido a la ambigüedad del período de referencia, la omisión del riesgo asociado y la falta de consideración de los negocios e inversiones futuras.
- **Valuación de la Empresa por Flujos Descontados:** El valor de la empresa ($V$) se calcula mediante la suma descontada de sus flujos futuros de efectivo ($FF_t$):
$$V = \sum_{t=1}^{\infty} \frac{FF_t}{(1 + \text{Costo del Dinero})^t}$$
El costo del dinero representa el costo de oportunidad de los recursos invertidos; es decir, el rendimiento exigido por no colocar dicho capital en un proyecto alternativo de equivalente riesgo.
### El Valor Tiempo del Dinero

El principio fundamental del valor tiempo establece que un peso disponible en el presente posee un valor mayor que un peso recibido en el futuro.

- **Razones Económicas del Valor Tiempo:**
    - **Costo de Oportunidad / Rendimiento:** El dinero actual puede invertirse inmediatamente para generar rendimientos adicionales y acrecentar su saldo futuro.
    - **Protección contra Inflación y Riesgo:** El dinero disponible hoy está exento de la incertidumbre, la volatilidad y la pérdida del poder adquisitivo causadas por la inflación futura.
    - **Preferencia por Consumo Presente:** Permite satisfacer necesidades o deseos en el momento actual sin diferir la utilidad.
- **Valor Nominal vs. Valor Tiempo:**
    - **Valor Nominal:** Es la denominación explícita o valor facial del dinero en un instante dado, prescindiendo del impacto de tasas de interés, inflación o tipo de cambio.
    - **Valor Tiempo:** Es la cuantitativa real del dinero que incorpora la capacidad generadora de intereses en el transcurso del tiempo.
### Tasa de Interés y Capitalización (Simple vs. Compuesto)

La tasa de interés mide el costo del capital en un período determinado y actúa como un indicador del riesgo asumido en la inversión ($\text{A mayor riesgo} \implies \text{mayor tasa requerida}$).

- **Interés Simple:** Los intereses generados no se acumulan al capital original; el cálculo de rendimientos se aplica siempre sobre la inversión inicial.
    - **Fórmula de Valor Futuro ($VF$):** $VF = VP \cdot (1 + n \cdot i)$
    - **Interés Total ($I$):** $I = \sum_{t=1}^{n} I_n$
- **Interés Compuesto:** Los intereses devengados en cada período se capitalizan (se adicionan al capital principal), generando a su vez nuevos intereses en los períodos subsecuentes.    
    - **Fórmula de Valor Futuro ($VF$):** $VF = VP \cdot (1 + i)^n$
    - **Interés Total ($I$):** $I = VF - VP$
- **Impacto del Tiempo en la Comparación:** A corto plazo la diferencia es acotada; sin embargo, en horizontes temporales prolongados, el interés compuesto exhibe una trayectoria de crecimiento exponencial superior al crecimiento lineal del interés simple.
### Estructura de Tasas (TNA, TEA y Tasas Equivalentes)

Las operaciones financieras requieren distinguir entre la tasa expresada contractualmente y la tasa real ganada o pagada según la frecuencia de capitalización.

- **Tasa Nominal Anual (TNA):** Tasa de referencia legal y comercial declarada en los contratos financieros. Presenta información incompleta debido a que no explicita la cantidad de liquidaciones o capitalizaciones que suceden dentro del año ($m$).
- **Tasa Efectiva Anual (TEA):** Tasa real percibida o abonada que incorpora explícitamente el efecto de la acumulación de intereses según la frecuencia de capitalización ($m$).
    - **Fórmula de Capitalización Subperiódica:**
$$VF = VP \cdot \left(1 + \frac{\text{TNA}}{m}\right)^m$$

donde $m$ es el número de períodos de capitalización en un año (ej. $m=12$ para mensual, $m=4$ para trimestral).

- **Relación analítica entre TNA y TEA:**
$$(1 + \text{TEA})^1 = \left(1 + \frac{\text{TNA}}{m}\right)^m \implies \text{TEA} = \left(1 + \frac{\text{TNA}}{m}\right)^m - 1$$
- **Tasas Equivalentes:** Dos o más tasas nominales con distintas frecuencias de capitalización son **equivalentes** si, al transformarse a tasas efectivas para un mismo período de tiempo, producen exactamente la misma TEA y rendimiento final.    
### Resoluciones y Ejemplos de Cátedra

1. **Cálculo de TEA con TNA del 16% y capitalización trimestral ($m=4$):**
    - **Planteo:** $\left(1 + \frac{0,16}{4}\right)^4 = (1 + \text{TEA})^1 \implies (1 + 0,04)^4 = 1,16985$.
    - **Resultado:** $\text{TEA} \approx 17\%$.
2. **Cálculo de TEA con TNA del 15,8% y capitalización mensual ($m=12$):**
    - **Planteo:** $\left(1 + \frac{0,158}{12}\right)^{12} = (1 + \text{TEA})^1 \implies (1 + 0,013166)^{12} = 1,1700$.
    - **Resultado:** $\text{TEA} \approx 17\%$.
3. **Conclusión de Equivalencia:** Ambos instrumentos ofrecen el mismo rendimiento efectivo anual ($\text{TEA} = 17\%$), demostrando que la TNA del $16\%$ trimestral y la TNA del $15,8\%$ mensual operan como tasas equivalentes.