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

* Para finalizar, una vez con los filamentos cortados, con el nucleo expuesto y limpiados se pasa a la fusionadora donde se tiene que alinear de la mejor manera posible en los extremos los filamentos para que la fusion se haga correctamente sin olvidar de colocar el manguito termocontraible el cual se puede colocar una vez fusionada la fibra, este debe quedar en donde se une la fibra para poder proteger la fusion, luego de unir la fibra y colocar el protector se debe pasar al "horno" donde se coloca el filamento el cual se calentara el protector y se "adherira" al filamento protegiendolo, concluyendo con esto.

>[!note]
Si no se usa el alcohol con los paños libres de pelusas los filamentos pueden quedar con impurezas y afectar a la union de estos, por eso es tan importante el uso de destos elementos.

## 5. Glosario-técnico
* **Núcleo (Core):** Filamento central hecho a partir de vidrio o plastico que recibe las señales de luz con el fin de transmitirlo en datos.
  
* **Revestimiento (Cladding):** Confina la luz dentro del núcleo garantizando que la transmisión sea eficiente y con baja pérdida.
  
* **Recubrimiento (Coating):** Capa que protege al núcleo y al revestimiento de arañazos, humedad y microplegamiento que podrían provocar la rotura de la fibra.
  
* **Atenuacion:** Es la perdida de potencia que sufre la señal luminosa a medida que viaja a lo largo del cable.

* **Manguito termocontraible:** es un elemento de protección indispensable que se utiliza para blindar y reforzar los empalmes por fusión entre dos hilos de fibra óptica.

<img src=assets/img/IMG_20261112_154518.jpg alr=9 width=250>

## 6. Valores de perdida estimados

### Registro y Análisis de Pérdida en Empalmes de Fibra Óptica

Para evaluar y registrar la calidad de un empalme en fibra óptica utilizando los datos de la fusionadora, es necesario contrastar el valor de pérdida estimada (en decibelios, **dB**) con los estándares internacionales (como **TIA-568** o **ITU-T**).

### 1. Tabla de Referencia: Análisis de Calidad por Pérdida Estimada

| Pérdida Estimada (dB) | Clasificación / Calidad | Diagnóstico Técnico y Acción Recomendada |
| :--- | :--- | :--- |
| **0.00 dB – 0.02 dB** | **Excelente (Óptimo)** | Alineación de núcleos perfecta. **Aprobar** y colocar manguito termocontraíble. |
| **0.03 dB – 0.05 dB** | **Bueno (Aceptable)** | Dentro del estándar para enlaces monomodo de larga distancia. **Aprobar**. |
| **0.06 dB – 0.10 dB** | **Regular (Marginal)** | Aceptable solo en redes de corta distancia (FTTH/LAN) si el presupuesto óptico lo permite. Evaluar rehacer. |
| **Mayor a 0.10 dB** | **Deficiente (Rechazado)** | Posible suciedad, mal corte (ángulo > 1°), burbujas o desalineación. **Cortar y repetir fusión**. |

>[note]
Para fibras **Multimodo**, el límite máximo aceptable por normativa suele extenderse hasta **0.10 dB – 0.15 dB**, aunque una buena fusionadora moderna logra valores menores a **0.03 dB**).

### 2. Plantilla de Registro de Empalmes

* **Identificación del Enlace / Tramo:** (Ej. *Nodo Central – Caja NAP 04*)
* **Número de Hilo / Código de Color:** (Ej. *Hilo 1 - Azul*)
* **Tipo de Fibra:** (Ej. *Monomodo G.652.D / Multimodo OM3*)
* **Ángulo de Corte (Izq. / Der.):** Debe ser idealmente **menor a 0.5°** (máximo tolerado 1.0°).
* **Pérdida Estimada (dB):** Valor arrojado por la máquina tras el arco eléctrico.
* **Estado Visual en Pantalla:** Verificar ausencia de burbujas, engrosamientos o adelgazamientos en el núcleo.
* **Dictamen:** *Aprobado / Rechazado*.

>[note]
Limitación de la fusionadora:** El valor que muestra la fusionadora es una **estimación óptica basada en imagen**, no una medición real de potencia.
Validación final: Para certificar la calidad real del enlace completo (incluyendo manguitos, conectores y atenuación por kilómetro), siempre se debe complementar este registro con una prueba de **OTDR** o un **medidor de potencia (Power Meter)**.
