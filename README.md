# 🔌Fusión de fibra optica
## Autor: Felipe Díaz

## 1. ¿Qué es la fusión de la fibra optica?
* **La fusión de fibra optica tambien llamada empalme por fusión o simplemente empalme es un metodo que permite unir dos fibras de un extremo a otro por medio de calor o electricidad, se hace con el fin de darle continuidad a la luz que pasa a través de las fibras para evitar su dispersión o reflexión. Normalmente este metodo se utiliza para enlazar redes y asi extender la señal o para reparar la fibra cuando esta presente daños.**

## 2. ⚠️ Seguridad y EPP
* **Antiparras:** Protegen los ojos y alrededores de fragmentos microscopicos de la fibra.
  
* **Guantes de nitrilo:** Protegen las manos de las fibras microscopicas y evitan que la fibra se ensucie con la grasa de la piel al manipularla.
  
* **Zapatos de seguridad con puntera de proteccion y dielectricos:** Al trabajar en una zona donde se trabaja con equipos energizados son necesarios para mitigar el riesgo electrico.
  
* **Chaqueta de seguridad (o chaleco tipo geólogo):** Utilizada para optimizar el orden en el puesto de trabajo, permitiendo portar de forma accesible los manguitos de fusión y consumibles menores en sus bolsillos, además de proteger la ropa de geles y residuos.

>[!warning]
Si no se usan los epp correctamente, o se omite su uso se pueden sufrir daños sin darse cuenta ya que la fibra es dificil de visibilizar en la mayoria de los casos. Sin olvidar que primero esta la seguridad de uno.



## 3. 🛠️ Equipamiento y herramientas
* **Peladora de fibra (Strippers):** Su funcion basicamente es pelar la cobertura del cable para dejar descubierta la capa interior y poder cortarla despues.
  
* **Cleaver:** Corta físicamente la fibra óptica con una cuchilla de alta precisión para que la cara final de la fibra quede plana y asi facilitar la conexion de esta.
  
* **Alcohol isopropilico de alta pureza y paños libres de pelusas:** Para limpiar la fibra y que no queden rastros de suciedad ni pelusas que puedan entorpecer el resultado final.

  <img src=assets/img/IMG_20261112_154532.jpg alt=1 width=250>
  
* **Fusionadora de fibra optica (Splicer):** Une las fibras fundiendolas con un arco eléctrico de alta precisión formando una unica fibra continua.

  <img src=assets/img/d9783a9d-8291-40cc-9898-7113218e4624.jfif alt=0 width=250>
  
* **manguito termocontraible:** Protege, refuerza y sella el punto exacto donde se unen dos fibras mediante una fusion.
  
* **Contenedor para residuos:** Almacena los restos y residuos para dejar limpia la zona de trabajo
  

## 4. Paso a paso
* Primero se debe sacar la primera capa de proteccion (normalmente es de color negro) para poder liberar su interior, esto lo podemos hacer con un caiman, cutter o una peladora con cuidado para no dañar la fibra o cortarla.

<img src=assets/img/IMG_20261112_154527.jpg alt=imagen representativa del que se utilizo en la practica  width=250>

* Seguido a esto debemos separar los cables trenzados que normalmente tiene vaselina haciendo incomodo de manejar, por lo que se deberia limpiar con un paño u papel con alcohol para quitar el exceso de esta.

* Ya con los filamentos separados se debe quitar la capa protectora que tiene para dejar el nucleo expuesto, al dejarlo expuesto se debe limpiar con alcohol isopropilico para eliminar asi las impurezas que puedan haber, una vez los filamentos de la fibra estan con el nucleo expuesto se debe colocar con cuidado en la cleaver ya que se necesita hacer un corte de 90° exactos para poder hacer la fusion de la fibra, despues de hacer el corte se debe limpiar para eliminar las impurezas.

<img src=assets/img/4febd963-3de9-452e-bf23-19d4195bc458.jfif alt=0 width=250>

>[!note]
Si no se usa el alcohol con los paños libres de pelusas los filamentos pueden quedar con impurezas y afectar a la union de estos, por eso es tan importante el uso de destos elementos.

* Para finalizar, una vez con los filamentos cortados, con el nucleo expuesto y limpiados se pasa a la fusionadora donde se tiene que alinear de la mejor manera posible en los extremos los filamentos para que la fusion se haga correctamente sin olvidar de colocar el manguito termocontraible el cual se puede colocar una vez fusionada la fibra, este debe quedar en donde se une la fibra para poder proteger la fusion, luego de unir la fibra y colocar el protector se debe pasar al "horno" donde se coloca el filamento el cual se calentara el protector y se "adherira" al filamento protegiendolo, concluyendo con esto.

<image src=assets/img/fusionadora7.jpg alt=9 width=250>
  
>[!warning]
>Como se puede observar en la imagen, la importancia de un buen corte no es solamente para uso tecnico ya que si el corte no es precisamente de 90° la fusionadora no hara la fusion correctamente y fallara el proceso.


## 5. Valores de perdida estimados

### Registro y Análisis de Pérdida en Empalmes de Fibra Óptica

Para evaluar y registrar la calidad de un empalme en fibra óptica utilizando los datos de la fusionadora, es necesario contrastar el valor de pérdida estimada (en decibelios, **dB**) con los estándares internacionales (como **TIA-568** o **ITU-T**).

### 1. Tabla de Referencia: Análisis de Calidad por Pérdida Estimada

| Pérdida Estimada (dB) | Clasificación / Calidad | Diagnóstico Técnico y Acción Recomendada |
| :--- | :--- | :--- |
| **0.00 dB – 0.02 dB** | **Excelente (Óptimo)** | Alineación de núcleos perfecta. **Aprobar** y colocar manguito termocontraíble. |
| **0.03 dB – 0.05 dB** | **Bueno (Aceptable)** | Dentro del estándar para enlaces monomodo de larga distancia. **Aprobar**. |
| **0.06 dB – 0.10 dB** | **Regular (Marginal)** | Aceptable solo en redes de corta distancia (FTTH/LAN) si el presupuesto óptico lo permite. Evaluar rehacer. |
| **Mayor a 0.10 dB** | **Deficiente (Rechazado)** | Posible suciedad, mal corte (ángulo > 1°), burbujas o desalineación. **Cortar y repetir fusión**. |

>[!note]
Para fibras **Multimodo**, el límite máximo aceptable por normativa suele extenderse hasta **0.10 dB – 0.15 dB**, aunque una buena fusionadora moderna logra valores menores a **0.03 dB**).

### 2. Plantilla de Registro de Empalmes

* **Identificación del Enlace / Tramo:** (Ej. *Nodo Central – Caja NAP 04*)
* **Número de Hilo / Código de Color:** (Ej. *Hilo 1 - Azul*)
* **Tipo de Fibra:** (Ej. *Monomodo G.652.D / Multimodo OM3*)
* **Ángulo de Corte (Izq. / Der.):** Debe ser idealmente **menor a 0.5°** (máximo tolerado 1.0°).
* **Pérdida Estimada (dB):** Valor arrojado por la máquina tras el arco eléctrico.
* **Estado Visual en Pantalla:** Verificar ausencia de burbujas, engrosamientos o adelgazamientos en el núcleo.
* **Dictamen:** *Aprobado / Rechazado*.

### Tener en cuenta que
* **Limitación de la fusionadora:** El valor que muestra la fusionadora es una **estimación óptica basada en imagen**, no una medición real de potencia.

* **Validación final:** Para certificar la calidad real del enlace completo (incluyendo manguitos, conectores y atenuación por kilómetro), siempre se debe complementar este registro con una prueba de **OTDR** o un **medidor de potencia (Power Meter)**.

## 7. Presupuesto optico

Para garantizar la viabilidad operativa de una red **GPON** (Gigabit Passive Optical Network), se debe calcular la atenuación total teórica del enlace desde la **OLT** hasta la **ONT** y verificar que no supere el presupuesto de potencia de la clase óptica utilizada (generalmente **Clase B+** o **Clase C+**).

### 1. Fórmula General de Atenuación Total

$$\text{Pérdida Total (dB)} = (L \times \alpha_{\text{fibra}}) + (N_e \times \alpha_{\text{empalme}}) + (N_c \times \alpha_{\text{conector}}) + \alpha_{\text{splitters}} + M_{\text{seguridad}}$$

Donde:
* **$L$**: Longitud total del enlace en kilómetros ($\text{km}$).
* **$\alpha_{\text{fibra}}$**: Atenuación por kilómetro según longitud de onda.
* **$N_e$**: Cantidad total de empalmes por fusión.
* **$\alpha_{\text{empalme}}$**: Pérdida máxima teórica por empalme.
* **$N_c$**: Cantidad de pares de conectores acoplados.
* **$\alpha_{\text{conector}}$**: Pérdida teórica por conector.
* **$\alpha_{\text{splitters}}$**: Atenuación acumulada de los divisores ópticos.
* **$M_{\text{seguridad}}$**: Margen de reserva para mantenimiento, envejecimiento y temperatura.

### 2. Valores Estándar de Diseño (Normativa ITU-T)

| Componente / Parámetro | Valor Teórico Estándar | Observaciones Técnicas |
| :--- | :--- | :--- |
| **Fibra Monomodo (1310 nm - Upstream)** | **0.35 dB/km** | Longitud de onda de subida (ONT $\rightarrow$ OLT). Es la más crítica por tener mayor atenuación. |
| **Fibra Monomodo (1490 nm - Downstream)** | **0.25 dB/km** | Longitud de onda de bajada (OLT $\rightarrow$ ONT). |
| **Empalme por Fusión** | **0.05 dB – 0.10 dB** | En diseño teórico conservador se calcula con **0.10 dB** por fusión. |
| **Conector Óptico (SC/APC o LC/APC)** | **0.25 dB – 0.50 dB** | Estándar TIA-568 permite hasta **0.50 dB** por par acoplado. |
| **Splitter 1:2 / 1:4 / 1:8** | **3.5 dB / 7.2 dB / 10.5 dB** | Valores típicos de inserción (sin considerar pérdidas por conectorización). |
| **Splitter 1:16 / 1:32 / 1:64** | **13.5 dB / 17.0 dB / 20.5 dB** | En redes GPON estándar, el splitteo total máximo suele ser **1:64** o **1:128**. |
| **Margen de Seguridad GPON** | **3.00 dB** | Reserva obligatoria para futuras reparaciones (nuevos empalmes) y degradación del láser. |

### 3. Presupuesto Óptico según Clase GPON (ITU-T G.984.2)

El cálculo de pérdidas teóricas más el margen de seguridad debe ser **menor o igual** al presupuesto máximo permitido por el módulo SFP de la OLT:

* **Clase B+ (Más común):** Presupuesto máximo de **28.0 dB** *(Potencia Tx OLT: +1.5 a +5 dBm | Sensibilidad Rx ONT: -27 dBm)*.
* **Clase C+ (Alta potencia):** Presupuesto máximo de **32.0 dB** *(Potencia Tx OLT: +3.0 a +7 dBm | Sensibilidad Rx ONT: -30 dBm)*.

### 4. Ejemplo Práctico de Cálculo (Enlace de 5 km)

Supongamos un enlace FTTH con las siguientes características:
* **Distancia ($L$):** $5\text{ km}$
* **Empalmes ($N_e$):** $6\text{ fusiones}$
* **Conectores ($N_c$):** $4\text{ conectores}$ (ODF, Mufa, NAP, Roseta)
* **División (Splitteo):** 1 Splitter de **1:8** + 1 Splitter de **1:8** (Equivalente a 1:64)
* **Margen de Seguridad:** $3.0\text{ dB}$

#### Desglose del Cálculo (Peor Caso: 1310 nm - Upstream):
1. **Atenuación por Fibra:** $5\text{ km} \times 0.35\text{ dB/km} = \mathbf{1.75\text{ dB}}$
2. **Atenuación por Empalmes:** $6 \times 0.10\text{ dB} = \mathbf{0.60\text{ dB}}$
3. **Atenuación por Conectores:** $4 \times 0.50\text{ dB} = \mathbf{2.00\text{ dB}}$
4. **Atenuación por Splitters:** $10.5\text{ dB} + 10.5\text{ dB} = \mathbf{21.00\text{ dB}}$
5. **Margen de Seguridad GPON:** $\mathbf{3.00\text{ dB}}$
6. $$\text{Pérdida Total Teórica (1310 nm)} = 1.75 + 0.60 + 2.00 + 21.00 + 3.00 = \mathbf{28.35\text{ dB}}$$

>[!note]
>En bajada a **1490 nm** con $0.25\text{ dB/km}$, la pérdida total sería de **27.85 dB**.

## 7. Glosario-técnico
* **Núcleo (Core):** Filamento central hecho a partir de vidrio o plastico que recibe las señales de luz con el fin de transmitirlo en datos.
  
* **Revestimiento (Cladding):** Confina la luz dentro del núcleo garantizando que la transmisión sea eficiente y con baja pérdida.
  
* **Recubrimiento (Coating):** Capa que protege al núcleo y al revestimiento de arañazos, humedad y microplegamiento que podrían provocar la rotura de la fibra.
  
* **Atenuacion:** Es la perdida de potencia que sufre la señal luminosa a medida que viaja a lo largo del cable.

* **Manguito termocontraible:** es un elemento de protección indispensable que se utiliza para blindar y reforzar los empalmes por fusión entre dos hilos de fibra óptica.

<img src=assets/img/IMG_20261112_154518.jpg alr=9 width=250>



