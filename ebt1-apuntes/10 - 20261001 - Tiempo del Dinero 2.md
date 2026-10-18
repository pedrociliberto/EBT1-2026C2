## Clase 10 - Tiempo del Dinero 2
### Conversión entre Tasas Equivalentes

Al transformar una Tasa Nominal a una Tasa Equivalente, el procedimiento se realiza dividiendo la Tasa Nominal por la cantidad de capitalizaciones anuales ($m$). Sin embargo, este criterio es conceptualmente erróneo al convertir una Tasa Equivalente subperiódica a otra Tasa Equivalente de diferente período.

Debido a la existencia de capitalizaciones compuestas dentro del período total, la conversión entre tasas equivalentes debe responder a la siguiente igualdad fundamental:

$$(1 + \text{TEA})^1 = (1 + \text{TEM})^{12} = (1 + \text{TEX})^Y$$

- $\text{TEX}$ representa la Tasa Equivalente para un período determinado
- $Y$ indica la cantidad de veces que dicho período entra en un año.
### Flujos de Efectivo Múltiples

Ocurren cuando se requiere determinar el valor presente o futuro de una serie de flujos de dinero que presentan montos variables e incluso signos contrapuestos (entradas y salidas de caja). La resolución analítica consiste en llevar cada flujo individual a la fecha focal deseada mediante descuento o capitalización y realizar la suma algebraica de los mismos.
### Anualidades

Una anualidad es un flujo múltiple de dinero que cumple estrictamente con cuatro condiciones simultáneas:
- Cuotas de montos iguales.
- Intervalos de tiempo constantes entre cuotas.
- Cuotas con el mismo signo operacional (todas ingresos o todas egresos).
- Tasa de interés constante para todo el horizonte.

El Valor Presente ($VP$) de una anualidad se calcula según la fórmula:
$$VP = C \cdot f_i^n = C \cdot \frac{(1 + i)^n - 1}{(1 + i)^n \cdot i}$$
Donde $C$ representa la cuota periódica, $i$ la tasa de interés del período, $n$ la cantidad de períodos, y $f_i^n$ es el **Factor de Anualidad**, cuyo valor numérico resulta siempre estrictamente menor al número total de períodos ($n$).
### Perpetuidades

Una perpetuidad es un caso límite de anualidad donde el número de períodos tiende a infinito ($n \to \infty$). Su Valor Presente ($VP$) se simplifica mediante el cociente entre el flujo constante y la tasa de interés:
$$VP = \frac{C}{i}$$
### Devolución de Préstamos: Estructura General

Un préstamo es una operación financiera donde un acreedor entrega un capital inicial ($P$) a un deudor, fijando por contrato cuotas, intereses, plazos y condiciones por mora. La cuota periódica ($C$) se compone de dos elementos clave:
$$C = A + I$$
- **Amortización ($A$):** Porción de la cuota destinada a la cancelación del capital adeudado. 
- **Interés ($I$):** Costo financiero sobre el saldo prestado pendiente de pago.
### Sistemas de Amortización de Préstamos

#### 1. Sistema Francés (Cuota Constante)

- **Características:** Cuota constante ($C$) con intereses calculados sobre saldos de capital adeudado.
- **Composición:** Las primeras cuotas tienen una alta carga de interés y baja amortización de capital. Con el transcurso del tiempo, la porción de interés decrece y la de amortización aumenta.
- **Impacto en refinanciación:** Ante un incumplimiento imprevisto, la refinanciación resulta desfavorable para el deudor ya que se habrá amortizado una proporción reducida del capital original.
- **Fórmulas principales:**
    - $\text{Cuota} = \frac{P}{f_i^n}$
    - $I_t = \text{Saldo Pendiente}_{t-1} \cdot i$
    - $A_t = C - I_t$

#### 2. Sistema Alemán (Amortización Constante)

- **Características:** Amortización de capital fija en cada período ($A = P/n$) y cuota decreciente ($C_t$).
- **Composición:** Los intereses se calculan sobre el saldo adeudado y van disminuyendo en cada período, lo que genera una cuota total decreciente.
- **Impacto en refinanciación:** A diferencia del Sistema Francés, en caso de refinanciar, el deudor habrá cancelado una mayor porción del capital para un mismo número de períodos transcurridos.
- **Fórmulas principales:**
    - $A = \frac{P}{n}$
    - $I_t = \left(P - (t - 1) \cdot A\right) \cdot i$
    - $C_t = A + I_t$
#### 3. Sistema Bullet (Pago al Vencimiento)

- **Características:** Durante la vida del préstamo, la cuota periódica se compone únicamente del pago de intereses ($C_t = I_t$), mientras que el total del capital ($P$) se amortiza íntegramente en la última cuota junto a su interés correspondiente.
- **Uso habitual:** Proyectos comerciales o corporativos con flujos de caja diferidos concentrados al final del período.
- **Impacto en refinanciación:** La refinanciación en caso de incumplimiento es sustancialmente costosa, dado que el saldo de capital se mantiene intacto durante toda la vigencia del contrato.
#### 4. Sistema Directo (Interés sobre Capital Inicial)

- **Características:** Los intereses se calculan directamente sobre la totalidad del capital prestado original ($P$) y no sobre saldos deudores remanentes. La amortización y los intereses permanecen constantes, generando cuotas fijas.
- **Riesgo comercial:** Este método es utilizado por financieras de crédito rápido para publicar tasas nominales aparentemente reducidas pero que derivan en un costo financiero total más alto.
- **Impacto en refinanciación:** Representa la alternativa de refinanciación más desfavorable debido a la sobrecarga constante de intereses abonados sobre la deuda inicial.
- **Fórmulas principales:**
    - $I = P \cdot i$
    - $A = \frac{P}{n}$
    - $C = \frac{P}{n} + P \cdot i$
### Refinanciación de Préstamos

Frente a una interrupción de pagos (default), el saldo deudor se determina calculando el Valor Presente a la fecha de incumplimiento de la totalidad de las cuotas remanentes pactadas contractualmente hasta el vencimiento original. El monto resultante se consolida como un nuevo capital de préstamo, el cual se reestructura bajo nuevas condiciones de tasa, plazo e incluso sistema de amortización.

### Tasas de Interés, Inflación y Tipo de Cambio

- **Ajuste por Inflación (Tasa Real vs. Tasa Efectiva):** La Tasa Efectiva pactada opera como una tasa nominal en términos de inflación. Para medir la ganancia o pérdida real del poder adquisitivo, debe calcularse la **Tasa Real**.
    - _Error habitual:_ Restar linealmente la inflación a la tasa efectiva ($\text{TEA} - \text{Inflación}$) solo otorga una aproximación válida en contextos macroeconómicos con inflación cercana al 1%-2% anual.
    - **Ecuación de Fisher (Cálculo Exacto):**        $$1 + \text{Tasa Real} = \frac{1 + \text{Tasa Efectiva}}{1 + \text{Tasa de Inflación}}$$
- **Efecto del Tipo de Cambio en Inversiones:** Operar en inversiones en moneda local con altas tasas de interés nominales conlleva riesgo cambiario. Una devaluación o apreciación del tipo de cambio por encima del rendimiento en moneda local puede generar una pérdida de capital al reconvertir los fondos a moneda extranjera al finalizar el período de inversión.