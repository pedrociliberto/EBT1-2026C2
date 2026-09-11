## Clase 6 - Partida doble y Registración

### Bloque A: La Partida Doble

La partida doble es el método de registración contable mediante el cual todo hecho económico se anota considerando sus dos caras, manteniendo el equilibrio patrimonial.

- **Principio Fundamental:** Todo hecho económico se origina en otro de igual valor y naturaleza contraria.
- **Requisitos del Asiento Contable:**
    - **Al menos dos cuentas:** En cada movimiento interviene un mínimo de dos cuentas (una registra la inversión y la otra el financiamiento).
    - **Igual valor:** Lo que se registra en un lado entra o sale por el mismo importe en el otro.
    - **Naturaleza contraria:** Siempre se debita al menos una cuenta y se acredita otra.
- **Debe y Haber:** Son convenciones de posición en el registro contable y no expresan juicios de valor ni conceptos de deuda/tenencia personal.
    - **Debe:** Columna izquierda. Debitar implica registrar a la izquierda.
    - **Haber:** Columna derecha. Acreditar implica registrar a la derecha.
    - **Conceptos de deudor y acreedor:** El ente que recibe es deudor; el que entrega es acreedor. No existe deudor sin acreedor ni acreedor sin deudor.
- **Fundamentos Reglares:**
    1. El ente que recibe es deudor y el que entrega es acreedor.
    2. No hay deudor sin acreedor, ni acreedor sin deudor.
    3. Todo valor que entra debe ser igual al valor que sale ($\sum \text{Debe} = \sum \text{Haber}$).
    4. El deudor existe porque hay un acreedor y viceversa.
    5. Las pérdidas (egresos) se debitan y las ganancias (ingresos) se acreditan.
- **Regla de Cuentas y Saldos:**

|**Tipo de Cuenta**|**Aumenta por**|**Disminuye por**|**Saldo habitual**|
|---|---|---|---|
|**Activo**|Debe|Haber|Deudor|
|**Pasivo**|Haber|Debe|Acreedor|
|**Patrimonio Neto**|Haber|Debe|Acreedor|
|**Ingresos**|Haber|Debe|Acreedor|
|**Egresos**|Debe|Haber|Deudor|

- **Control de Invariante:** La igualdad $\text{Activo} = \text{Pasivo} + \text{Patrimonio Neto}$ se preserva en cada operación. Si la suma del Debe no coincide con la del Haber, el sistema advierte un error aritmético. Sin embargo, el método no detecta errores conceptuales (como imputar un importe correcto en una cuenta equivocada).
### Bloque B: Devengamiento

El principio de devengamiento establece que los hechos económicos deben registrarse en el momento en que ocurren, independientemente del flujo de efectivo.

- **Diferencia entre Devengamiento y Cobro/Pago:**
    - **Devengado:** Se registra cuando se realiza la transacción (se entrega el bien o se presta el servicio). Determina los resultados e impacta en el Cuadro de Resultados / P&L.
    - **Cobrado/Pagado (Percibido):** Se registra cuando se produce el movimiento del dinero. Impacta únicamente en las Disponibilidades (caja y bancos).
- **Dinámica Temporal:** Entre la fecha de devengamiento (ej. venta) y la fecha de cobro, la empresa financia al cliente mediante un crédito comercial ("Créditos por ventas"). El cobro posterior permuta un activo por otro (reduce créditos y aumenta disponibilidad), sin afectar las cuentas de resultado.
- **Ciclo de Conversión de Efectivo:** Mide la brecha temporal entre el pago de costos y el cobro de ventas ($\text{Días de cobranza} + \text{Días de stock} - \text{Días de pago}$). Una empresa puede reflejar rentabilidad positiva en sus resultados y, simultáneamente, iliquidez en caja si financia su crecimiento con capital propio. En modelos como _SaaS_ con cobro anual adelantado, este ciclo es negativo, permitiendo que los clientes financien a la empresa.
### Bloque C: Los Libros Contables

Estructura de sistematización y registro de los hechos económicos.

- **Plan y Manual de Cuentas:**
    - **Plan de Cuentas:** Listado ordenado, jerárquico y codificado numéricamente de las cuentas de la organización. Los grupos de Activo, Pasivo y Patrimonio Neto componen el Balance, mientras que Ingresos y Egresos arman el Cuadro de Resultados.
    - **Manual de Cuentas:** Documento que especifica las reglas de imputación, criterios y contrapartidas de cada cuenta del plan.
- **Libro Diario:**
    - Registro obligatorio y rubricado donde se anotan las transacciones en orden cronológico mediante asientos contables.
    - Todo asiento debe contener fecha, clasificación de la cuenta, nombre de las cuentas intervinientes e importes en las columnas de Debe y Haber.
- **Libro Mayor:**
    - Registro agrupado por cuenta individual. Proceso de transcripción desde el Diario denominado _mayorizar_.
    - Permite conocer el saldo acumulado (deudor o acreedor) de cada cuenta para la confección del Balance. No es legalmente obligatorio, pero resulta imprescindible operacionalmente.
- **Diferencias Principales:**

| **Característica**        | **Libro Diario**          | **Libro Mayor**                   |
| ------------------------- | ------------------------- | --------------------------------- |
| **Criterio de orden**     | Cronológico (por fecha)   | Sistemático (por cuenta contable) |
| **Unidad de información** | Asiento contable completo | Movimientos y saldo por cuenta    |
| **Obligatoriedad legal**  | Sí                        | No                                |

- **Circuito Contable Integrado:**    
$$\text{Hecho Económico} \longrightarrow \text{Libro Diario} \longrightarrow \text{Mayorización} \longrightarrow \text{Saldos por Cuenta} \longrightarrow \text{Estados Contables}$$
    El Balance de cierre de un período se constituye en el Balance de apertura del siguiente.
### Bloque D: Los Impuestos en la Registración

Impacto contable de los tributos en las compras, ventas y utilidades.

- **Impuesto al Valor Agregado (IVA):**
    - La empresa actúa como agente de retención/recaudación; el IVA no representa un ingreso ni un egreso para el ente.
    - **IVA Crédito Fiscal (C.F.):** Surge en las compras/gastos. Representa un derecho contra el organismo fiscal y se clasifica como **Activo**.
    - **IVA Débito Fiscal (D.F.):** Surge en las ventas. Representa una obligación con el organismo fiscal y se clasifica como **Pasivo**.
    - **Posición de IVA:** Se liquida restando los créditos fiscales de los débitos fiscales ($\text{IVA D.F.} - \text{IVA C.F.}$). Si el Débito supera al Crédito, se genera un pasivo a pagar; si el Crédito supera al Débito, se genera un saldo a favor en el Activo.
- **Impuesto a las Ganancias:**
    - Grava el resultado neto imponible (utilidad). Se registra como un egreso. Posee escalas alícuotas progresivas para personas jurídicas (25%, 30% y 35% según tramos de ganancia acumulada).
- **Impuesto a los Ingresos Brutos (IIBB):**
    - Tributo provincial que grava la facturación bruta independientemente de la existencia de utilidades o pérdidas.
- **Régimen de Economía del Conocimiento (Ley 27.506):**
    - Marco de incentivos aplicable a empresas tecnológicas que cumplan requisitos de facturación en actividades promovidas (mínimo 70%) e inversión/I+D/exportación.
    - **Beneficios fiscales:** Reducción de hasta el 60% en Impuesto a las Ganancias, bono de crédito fiscal del 70% al 80% sobre contribuciones patronales, y exención de derechos de exportación en servicios.