# Tarea2-
Investigacion


# 💻 Computación Cuántica

La **computación cuántica** es un paradigma de procesamiento de información que utiliza los principios de la **mecánica cuántica**.  
A diferencia de la computación clásica, que utiliza **bits** (`0` o `1`), la computación cuántica utiliza **qubits** o **cúbits**, que pueden estar en **superposición de estados**: `0`, `1` o ambos simultáneamente.

---

## 🎯 Ilustración: Representación de un Qubit en la Esfera de Bloch
![Esfera de Bloch](https://upload.wikimedia.org/wikipedia/commons/6/6b/Bloch_sphere.svg)

---

## 🏗️ Arquitectura de un Computador Cuántico

| **Componente** | **Función** |
|----------------|-------------|
| Qubits | Unidad básica de información cuántica |
| Puertas cuánticas | Operaciones lógicas sobre qubits |
| Unidad de Procesamiento Cuántico (QPU) | Equivalente a la CPU clásica |
| Memoria cuántica | Almacena estados cuánticos sin colapsarlos |
| Refrigerador de dilución | Mantiene temperaturas cercanas al 0 absoluto |
| Planificador dinámico | Gestiona la ejecución de algoritmos cuánticos |


## 🎯 Ilustración: Arquitectura de computador cuantico
![Image Alt](https://github.com/Lau-raCrz/Tarea2-/blob/6469df6ff8228afd9a93f744a562dfd96a331c96/202211100000001.jpg)
---

## 📜 Historia, Ventajas y Desventajas

### ⏳ Historia resumida
| **Año** | **Evento clave** |
|---------|------------------|
| 1981 | Richard Feynman propone la idea de una computadora cuántica |
| 1994 | Algoritmo de Shor para factorización |
| 1996 | Algoritmo de Grover para búsqueda |
| 2019 | Google logra la *supremacía cuántica* |
| 2023 | IBM lanza el procesador cuántico de **433 qubits** |

---

### ✅ Ventajas
- ⚡ Velocidad exponencial en ciertos problemas  
- 🧪 Simulación de sistemas cuánticos  
- 🚚 Optimización de rutas y logística  
- 🤖 Avances en IA y aprendizaje automático  
- 🔒 Criptografía cuántica segura  

### ❌ Desventajas
- 💰 Altísimo costo  
- ❄️ Requiere temperaturas extremadamente bajas (-240 °C)  
- 🌀 Decoherencia y errores cuánticos  
- 📚 Algoritmos complejos y específicos  
- 🚫 No disponible para uso comercial masivo  

---

## 🔍 Principios Fundamentales

1. **Superposición** →En la física clásica, un bit es 0 o 1. En la cuántica, un qubit puede estar en un estado combinado de 0 y 1 al mismo tiempo (como una moneda girando en el aire). Esto permite realizar múltiples cálculos simultáneamente.
Ejemplo: Un qubit en superposición es como un interruptor que está encendido y apagado a la vez hasta que lo mides.  
2. **Entrelazamiento (Entanglement)** →Cuando dos qubits están entrelazados, sus estados se vinculan: si mides uno, el otro instantáneamente colapsa a un estado relacionado, sin importar la distancia. Es una conexión más fuerte que cualquier cosa en la física clásica.
Ejemplo: Imagina dos dados mágicos: si uno sale "3", el otro siempre mostrará "4", incluso si están en galaxias distintas.  
3. **Interferencia cuántica** →Las ondas de probabilidad de los qubits pueden sumarse o cancelarse (como olas en el mar). En computación cuántica, usamos esto para amplificar resultados correctos y reducir los incorrectos.
Ejemplo: En el algoritmo de búsqueda de Grover, la interferencia destaca la solución correcta entre millones de posibilidades.  
4. **Medición probabilística** →Al medir un qubit en superposición, colapsa a 0 o 1 con cierta probabilidad. No puedes predecir el resultado exacto, solo las probabilidades basadas en su estado anterior.
Ejemplo: Si un qubit tiene un 70% de probabilidad de ser 0, al medirlo 100 veces, ~70 veces será 0..  
5. **Decoherencia** → Los qubits son frágiles: cualquier interacción con el entorno (calor, luz, vibraciones) destruye su superposición y entrelazamiento. Esto causa errores y es el mayor obstáculo para construir computadoras cuánticas prácticas.
Solución: Usar corrección de errores cuánticos y enfriar los qubits casi al cero absoluto (-273°C)..  

---

## 📡 Comunicación y Compuertas Cuánticas

### Tipos de comunicación cuántica
| **Tipo** | **Descripción** |
|----------|-----------------|
| Teletransportación cuántica |Transfiere el estado de un qubit a otro distante usando entrelazamiento. No mueve materia, solo información. |
| Criptografía cuántica | Seguridad basada en principios cuánticos, usa entrelazamiento para crear claves indescifrables. Si un espía intenta interceptarlas, altera el estado y es detectado. |
| Distribución de claves cuánticas (QKD) | Protocolo BB84, invulnerable a la interceptación |

### Compuertas cuánticas más comunes
| **Compuerta** | **Símbolo** | **Función** |
|---------------|-------------|-------------|
| Hadamard (H) | H | Crea superposición |
| Pauli-X | X | Equivalente a NOT clásico |
| CNOT | ⊕ | Entrelaza dos qubits |
| Toffoli (CCNOT) | ◎ | Puerta de 3 qubits |


# 🧠 Computadores Neuromórficos

Un **computador neuromórfico** es un sistema de hardware diseñado para **imitar la estructura y el funcionamiento del cerebro biológico**.  
Se basa en **redes neuronales de impulsos** (*Spiking Neural Networks - SNN*) y **arquitecturas de procesamiento distribuidas** para procesar información de manera **altamente eficiente, adaptativa y paralela**.

A diferencia de los **ordenadores clásicos**, que separan la memoria y el procesamiento (arquitectura de *Von Neumann*), los sistemas neuromórficos integran ambos en la misma unidad, como ocurre en las **neuronas biológicas**.

---

## 🧬 Arquitectura y Funcionamiento

### Componentes principales
| **Componente** | **Función** |
|----------------|-------------|
| **Neuronas artificiales** | Unidades básicas que reciben, procesan y transmiten señales eléctricas |
| **Sinapsis programables** | Conexiones entre neuronas cuya fuerza (peso) puede cambiar para aprender |
| **Memristores** | Dispositivos de memoria no volátil que almacenan pesos sinápticos |
| **Redes de impulsos (SNN)** | Modelo de red neuronal que utiliza eventos discretos (*spikes*) para procesar |

---

### Modo de funcionamiento
1. **Event-driven** → Solo las neuronas activas consumen energía.  
2. **Procesamiento paralelo** → Millones de neuronas operan simultáneamente.  
3. **Aprendizaje local** → Las sinapsis se ajustan según la actividad local, sin un control centralizado.  
4. **Plasticidad sináptica** → El sistema se adapta en tiempo real sin reprogramación.  

📷 **Ilustración**: Comparación entre arquitectura *Von Neumann* y neuromórfica  
![Comparativa](https://upload.wikimedia.org/wikipedia/commons/3/3d/Neuro_computing_vs_von_Neumann.png)

---

## 🔌 Hardware Utilizado

| **Tecnología** | **Descripción** | **Ejemplos** |
|----------------|-----------------|--------------|
| **CMOS** | Transistores estándar para neuronas y sinapsis | IBM TrueNorth, Intel Loihi |
| **Memristores** | Resistencias con memoria para almacenar pesos sinápticos | Dispositivos de cambio de fase, HP Labs |
| **Neurogrid** | Plataforma académica con 16 chips *NeuroCore* | Stanford University |
| **SpiNNaker** | Sistema digital con 1 millón de núcleos | Proyecto europeo Human Brain |
| **BrainScaleS** | Sistema analógico acelerado | Heidelberg University |

📷 **Ejemplo**: *Intel Loihi 2 – Chip neuromórfico de segunda generación*  
![Intel Loihi 2](https://newsroom.intel.com/wp-content/uploads/sites/11/2021/09/Intel-Loihi-2-chip.jpg)

---

## 🔢 Tipos de Computación Neuromórfica

| **Tipo** | **Características** | **Ejemplos** |
|----------|---------------------|--------------|
| **Digital neuromórfica** | Emula neuronas con circuitos digitales (alta precisión, consumo moderado) | Intel Loihi, SpiNNaker |
| **Analógica neuromórfica** | Usa propiedades físicas de materiales (rápido, bajo consumo, menos preciso) | Chips con memristores |
| **Híbrida** | Combina elementos analógicos y digitales | IBM TrueNorth |
| **SpiNNaker-like** | Red basada en paquetes para eventos asincrónicos | SpiNNaker |
| **Neurogrid-like** | Emulación analógica de neuronas con alta eficiencia energética | Neurogrid |

---

## ✅ Ventajas y ❌ Desventajas

### ✅ Ventajas
- ⚡ **Eficiencia energética** → Hasta 1000 veces menos consumo que CPUs tradicionales.  
- ⏱ **Procesamiento en tiempo real** → Ideal para IoT, robótica y vehículos autónomos.  
- 🔄 **Adaptabilidad** → Aprendizaje continuo sin intervención externa.  
- 🧮 **Procesamiento paralelo masivo** → Millones de operaciones simultáneas.  
- 📉 **Baja latencia** → Sin cuellos de botella entre memoria y procesador.  

### ❌ Desventajas
| **Desafío** | **Descripción** |
|-------------|-----------------|
| **Precisión reducida** | Errores por variaciones en memristores y componentes analógicos |
| **Falta de estándares** | No existen benchmarks ni APIs universales |
| **Software limitado** | Herramientas de programación en desarrollo |
| **Escalabilidad** | Difícil replicar cerebros humanos a gran escala |
| **Complejidad** | Requiere conocimientos en electrónica, neurociencia e IA |

---

# 🧬 Ordenadores Biológicos

Un **ordenador biológico** es un sistema que utiliza **componentes vivos** o derivados de organismos (como **ADN, ARN, proteínas o neuronas**) para **almacenar, procesar y transmitir información**.  
A diferencia de los **ordenadores convencionales**, que ejecutan instrucciones binarias en base a transistores de silicio, los ordenadores biológicos operan mediante **reacciones bioquímicas** y **procesos celulares**, como la **expresión génica** o la **comunicación sináptica**.

Estos sistemas tienen un enorme potencial en áreas como la medicina personalizada, la biotecnología y la inteligencia artificial híbrida.

---

## 🏗️ Arquitectura de un ordenador biológico

| **Componente** | **Función** |
|----------------|-------------|
| **Entrada** | Moléculas químicas, impulsos eléctricos o señales lumínicas |
| **Unidad de procesamiento** | Células vivas (bacterias, neuronas), ribosomas, enzimas |
| **Almacenamiento** | ADN, ARN, proteínas o estados celulares |
| **Salida** | Producción de proteínas, fluorescencia, impulsos eléctricos |
| **Control** | *Biosoftware* o sistemas de soporte vital (temperatura, nutrientes, pH) |

📷 **Ejemplo**: Esquema de un sistema basado en bacterias modificadas genéticamente  
![Computación biológica](https://upload.wikimedia.org/wikipedia/commons/4/49/Synthetic_biology_circuit.png)

---

## 🧬 Tipos de ordenadores biológicos

| **Tipo** | **Descripción** | **Ejemplo** |
|----------|-----------------|-------------|
| **Computadoras de ADN** | Utilizan cadenas de ADN para realizar operaciones lógicas y resolver problemas complejos | Resolución del *problema del viajante* con ADN (Adleman, 1994) |
| **Computadoras ARN-Proteína** | Usan ribosomas y ARN mensajero como puertas lógicas | Circuitos biológicos en *E. coli* |
| **Computadoras neuronales** | Integran neuronas humanas en chips de silicio para procesamiento híbrido | CL1 de *Cortical Labs* |
| **Computadoras celulares** | Usan bacterias o levaduras modificadas como procesadores biológicos | Células que detectan metales pesados |
| **Híbridos bio-silicio** | Combinan hardware tradicional con componentes biológicos | Neurogrid + neuronas humanas |

💡 *Nota:* Estos sistemas pueden operar en ambientes donde los chips de silicio no serían viables, como dentro de organismos vivos.

---

## 🚀 Principales hitos y cronología

| **Año** | **Hito** | **Descripción** |
|---------|----------|-----------------|
| **1994** | ADN computing | Leonard Adleman resuelve el *problema del camino hamiltoniano* usando ADN |
| **2013** | CRISPR-Cas9 | Herramienta de edición genética que permite construir circuitos biológicos precisos |
| **2020** | Circuito lógico complejo | Se crean 12 puertas lógicas (AND, OR, NOT) en bacterias vivas |
| **2025** | CL1 comercial | Cortical Labs lanza el primer ordenador biológico comercial con neuronas humanas |
| **2025** | Bio-AI | CL1 demuestra aprendizaje adaptativo en tareas de robótica e inteligencia artificial |

---

## 📊 Comparación rápida: Biológico vs Tradicional

| **Característica** | **Biológico** | **Tradicional** |
|--------------------|---------------|-----------------|
| **Material** | Células, ADN, proteínas | Silicio |
| **Energía** | Microvatios | Vatios |
| **Velocidad** | Lenta por operación, pero masivamente paralela | Rápida por operación |
| **Tamaño** | Nanométrico | Micrométrico |
| **Reprogramación** | Evolutiva (cambios genéticos) | Reescritura de software |

---

## 🌟 Potenciales aplicaciones

- **Medicina personalizada** → Diagnóstico y tratamiento adaptado a cada paciente.  
- **Biosensores avanzados** → Detectar contaminantes, toxinas o patógenos en tiempo real.  
- **Bio-IA** → Procesamiento híbrido biológico-digital para tareas cognitivas complejas.  
- **Nanorobots médicos** → Sistemas biológicos que circulen por el cuerpo reparando tejidos.  

---

## 📚 Referencias


# 🧩 Computación Heterogénea

La **computación heterogénea** es un paradigma que combina en un mismo sistema **varios tipos de unidades de procesamiento con arquitecturas diferentes** para **optimizar el rendimiento y/o la eficiencia energética**.  
En lugar de usar solo CPUs idénticas, se integran **procesadores especializados** como **GPUs**, **FPGAs**, **DSPs**, **TPUs** o **coprocesadores de IA**, cada uno diseñado para tareas específicas.

📷 **Esquema típico**: CPU + GPU + FPGA en un mismo sistema  
![Computación heterogénea](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0b/Heterogeneous_computing_diagram.svg/800px-Heterogeneous_computing_diagram.svg.png)

---

## 📅 Historia y evolución

| **Año** | **Hito clave** |
|---------|----------------|
| **2000** | IBM lanza el *Cell Broadband Engine* (usado en la PS3), combinando CPU con SPEs especializados |
| **2006** | NVIDIA introduce **CUDA**, permitiendo cálculos generales en GPU |
| **2011** | ARM presenta **big.LITTLE**, mezcla de núcleos rápidos y eficientes |
| **2012** | AMD crea la **HSA Foundation** (*Heterogeneous System Architecture*) |
| **2016** | Google presenta su **TPU (Tensor Processing Unit)** para IA |
| **2023** | Apple lanza el **M2 Ultra** con CPU, GPU y *Neural Engine* en un solo chip |
| **2025** | AMD Ryzen AI 300 integra **NPU + GPU + CPU** en una arquitectura heterogénea avanzada |

💡 *Dato extra:* Hoy en día, la mayoría de smartphones y portátiles de gama alta usan algún tipo de arquitectura heterogénea para equilibrar potencia y eficiencia.

---

## ✅ Ventajas

| **Ventaja** | **Explicación** |
|-------------|-----------------|
| **Rendimiento mejorado** | Cada tarea se ejecuta en la unidad más adecuada (GPU para paralelismo, CPU para control lógico) |
| **Eficiencia energética** | Las unidades especializadas consumen menos energía para su función |
| **Escalabilidad modular** | Se pueden añadir más aceleradores sin rediseñar todo el sistema |
| **Latencia reducida** | Con HSA, CPU y GPU comparten memoria y evitan copias de datos |
| **Flexibilidad** | Se adapta a cargas de trabajo cambiantes (IA, gráficos, cálculo científico) |

---

## ❌ Desventajas

| **Desafío** | **Descripción** |
|-------------|-----------------|
| **Complejidad de programación** | Requiere APIs específicas (*CUDA, OpenCL, SYCL*) y conocimiento de cada arquitectura |
| **Compiladores limitados** | No todos los lenguajes soportan todos los aceleradores |
| **Sincronización de datos** | Mantener coherencia de caché entre CPU y GPU puede ser costoso |
| **Coste de diseño** | Integrar múltiples chips aumenta el precio y complejidad |
| **Fragmentación** | Falta de estándares universales entre fabricantes (NVIDIA, AMD, Intel) |

---

## 📊 Casos de uso actuales

| **Sector** | **Ejemplo de arquitectura heterogénea** |
|------------|-----------------------------------------|
| **Supercomputación** | *Fugaku* (CPU ARM + GPU NVIDIA) |
| **Gaming** | *PlayStation 5* (CPU AMD + GPU RDNA2) |
| **IA móvil** | *Apple A17 Pro* (CPU + GPU + Neural Engine) |
| **Automoción** | *NVIDIA Drive Orin* (CPU + GPU + NPU) |
| **IoT** | *Jetson Nano* (CPU ARM + GPU Maxwell) |

---

## 🔮 Tendencias y futuro

- **Integración en un solo chip** → SoCs con CPU, GPU, NPU y aceleradores de vídeo en la misma oblea.  
- **Memoria unificada** → CPU y GPU compartiendo la misma memoria para evitar cuellos de botella.  
- **Aceleradores de IA especializados** → Chips optimizados para redes neuronales y *deep learning*.  
- **Arquitecturas adaptativas** → Sistemas que reasignan recursos en tiempo real según la carga de trabajo.  
- **Mayor estandarización** → Avances en APIs como *oneAPI* de Intel para unificar programación.  


---

# 🧩 Computación de Borde (Edge Computing)

La **computación de borde** (*edge computing*) es un paradigma de computación distribuida que **procesa los datos lo más cerca posible de su fuente de origen** (dispositivos IoT, sensores, cámaras, wearables, etc.) en lugar de enviarlos a un centro de datos o nube centralizada.  

Este enfoque:
- 🔽 **Reduce la latencia**, ya que evita que los datos viajen grandes distancias.
- 📉 **Ahorra ancho de banda**, enviando solo la información relevante a la nube.
- 🔒 **Mejora la seguridad**, al mantener datos sensibles dentro de la red local.

---

## 🏗️ Arquitectura de la computación de borde

| **Capa** | **Componente** | **Función** |
|----------|---------------|-------------|
| **Dispositivos Edge** | Sensores, cámaras, wearables | Generan datos en tiempo real (temperatura, vídeo, posición, etc.) |
| **Edge Nodes** | Microservidores, gateways locales | Procesan datos en el sitio, aplican filtrado y detección inicial de eventos |
| **Edge Gateways** | Routers inteligentes, hubs de comunicación | Enrutan y transforman datos entre nodos y la nube |
| **Edge Servers** | Mini-data centers locales | Procesamiento intensivo y almacenamiento temporal |
| **Nube Central** | Data centers remotos | Almacenamiento histórico y análisis a gran escala |

📷 **Diagrama de arquitectura**  
![Edge Computing Architecture](https://www.redhat.com/cms/managed-files/styles/wysiwyg_full_width/s3/2022-11/edge-computing-architecture-diagram.svg?itok=h0KZ9H6A)

💡 *Nota:* En entornos industriales, la capa *Edge Gateway* también puede incluir firewalls y sistemas de seguridad perimetral para proteger la infraestructura.

---

## 📅 Historia y evolución

| **Año** | **Hito clave** |
|---------|----------------|
| **1990s** | Surgen las primeras **Content Delivery Networks (CDNs)** para entregar imágenes y vídeo desde servidores cercanos al usuario. |
| **2006** | Amazon Web Services (AWS) populariza la nube; crece la necesidad de reducir latencia para aplicaciones críticas. |
| **2015** | Cisco presenta el concepto de **Fog Computing**, actuando como capa intermedia entre *edge* y nube. |
| **2018** | Nace el término **Edge AI** para describir la inferencia de IA en dispositivos locales. |
| **2020** | El despliegue masivo de **5G** habilita latencias de milisegundos, impulsando el *edge computing*. |
| **2023** | Apple, NVIDIA y otros lanzan **chips con aceleradores integrados** para IA en el borde (Apple M2 Ultra, Jetson Orin). |
| **2025** | El *edge computing* se convierte en estándar en **ciudades inteligentes**, **vehículos autónomos** y **robótica avanzada**. |

---

## ✅ Ventajas

| **Ventaja** | **Descripción** |
|-------------|-----------------|
| **Latencia ultra-baja** | Tiempos de respuesta de milisegundos para aplicaciones críticas (robótica, conducción autónoma). |
| **Ahorro de ancho de banda** | Solo se transmiten datos procesados y relevantes a la nube. |
| **Mayor seguridad** | Los datos sensibles permanecen en redes locales, reduciendo el riesgo de ataques externos. |
| **Fiabilidad en zonas remotas** | Puede operar incluso con conexión intermitente (plataformas petroleras, minas). |
| **Escalabilidad distribuida** | Se añaden nodos *edge* sin saturar la nube central. |

---

## ❌ Desventajas

| **Desafío** | **Descripción** |
|-------------|-----------------|
| **Gestión compleja** | Requiere coordinar miles de nodos con diferentes configuraciones. |
| **Seguridad perimetral** | Cada dispositivo *edge* es un potencial punto de ataque. |
| **Coste inicial** | Inversión en infraestructura local (servidores, gateways, routers inteligentes). |
| **Mantenimiento distribuido** | Las actualizaciones deben aplicarse en múltiples ubicaciones. |
| **Limitaciones de recursos** | Los nodos *edge* no tienen la capacidad de cómputo de un *data center*. |

---

## 📊 Comparativa rápida: Edge vs Fog vs Cloud

| **Característica** | **Edge** | **Fog** | **Cloud** |
|--------------------|----------|---------|-----------|
| **Ubicación del procesamiento** | Dispositivo o nodo cercano | Gateway o servidor local intermedio | Data center remoto |
| **Latencia** | Muy baja (ms) | Media | Alta |
| **Uso de ancho de banda** | Mínimo | Moderado | Alto |
| **Ejemplo** | Cámara de seguridad con IA integrada | Servidor en planta industrial | AWS EC2, Google Cloud |

💡 **Fog computing** actúa como un puente entre *edge* y *cloud*, reduciendo la carga en ambos extremos.

---

## 🔮 Tendencias y futuro

- **IA en el borde (Edge AI)** → Modelos de *machine learning* que se ejecutan directamente en dispositivos IoT.  
- **Integración con 5G y 6G** → Latencias ultra-bajas para vehículos autónomos y telecirugía.  
- **Micro data centers móviles** → Centros de procesamiento que se desplazan donde se necesitan (eventos, emergencias).  
- **Ciberseguridad descentralizada** → Sistemas de defensa distribuidos en todos los nodos.  
- **Energía optimizada** → Uso de energía renovable y sistemas de bajo consumo en nodos *edge*.  



---
📌 **Autor:** *Laura*  
📅 **Última actualización:** 2025

---
## 📚 Referencias

1. H. F. G. Ariza, N. H. Aguilar, y K. V. G. Mogollon. *ORDENADOR CUÁNTICO: ARQUITECTURA E INFORMACIÓN*. Edu.co. [En línea]. Disponible en: [http://wiki.sc3.uis.edu.co/images/5/54/ArtiG3.pdf](http://wiki.sc3.uis.edu.co/images/5/54/ArtiG3.pdf)

2. Team, R. (2024, 4 diciembre). *10 Ventajas y desventajas de la computación cuántica*. Carlos Barraza. Disponible en: [https://barrazacarlos.com/es/10-ventajas-y-desventajas-de-la-computacion-cuantica](https://barrazacarlos.com/es/10-ventajas-y-desventajas-de-la-computacion-cuantica)

3. S. Verde y F. Octubre. *INSTITUTO POLITÉCNICO NACIONAL CENTRO DE INVESTIGACIÓN EN COMPUTACIÓN*. Ipn.mx. [En línea]. Disponible en: [https://repositoriodigital.ipn.mx/bitstream/123456789/8510/1/ARQUITECTURAS%20COMPUTACIONALES%20CUANTICAS.pdf](https://repositoriodigital.ipn.mx/bitstream/123456789/8510/1/ARQUITECTURAS%20COMPUTACIONALES%20CUANTICAS.pdf)

4. S. Nowak. *Computación cuántica: cómo funciona y qué son los ordenadores cuánticos*. Nuclio Digital School, 18-sep-2024. Disponible en: [https://nuclio.school/blog/computacion-cuantica-como-funciona-y-que-son-los-ordenadores-cuanticos](https://nuclio.school/blog/computacion-cuantica-como-funciona-y-que-son-los-ordenadores-cuanticos)

5. 	R. Caballar y C. Stryker, “¿Qué es la computación neuromórfica?”, Ibm.com, 31-ene-2025.
6. 	U. Por, “TECNOLOGÍA NEUROMÓRFICA”, Blogspot.com. [En línea]. Disponible en: https://tecnologianeuromorfica2017.blogspot.com/2017/12/ventajas-y-desventajas-de-la-tecnologia.html.

7.	The Black Box Lab, “Computación neuromórfica: el futuro de la inteligencia artificial eficiente”, The Black Box Lab, 19-feb-2025. [En línea]. Disponible en: https://theblackboxlab.com/computacion-neuromorfica. 

8.	J. C. López, “Computación biológica: qué es y cómo nos está ayudando a resolver algunos de los grandes retos a los que se enfrenta la humanidad”, Xataka.com, 14-abr-2020. [En línea]. Disponible en: https://www.xataka.com/investigacion/computacion-biologica-que-como-nos-esta-ayudando-a-resolver-algunos-grandes-retos-a-que-se-enfrenta-humanidad.
9. D. Orf, “Un ordenador de 35.000 dólares con neuronas humanas abre la era de la computación biológica sin alcanzar aún la consciencia”, Esquire, 25-may-2025. [En línea]. Disponible en: https://www.esquire.com/es/tecnologia/a64859540/celulas-cerebrales-humanas-ordenador. 
10. J. F. S. Garces., “Computación Heterogénea Y su Gran Auge en los Últimas Décadas”, Edu.co. [En línea]. Disponible en: http://wiki.sc3.uis.edu.co/images/2/25/ArtiG8.pdf. 
11. “¿Qué es la informática heterogénea?”, Supermicro.com. [En línea]. Disponible en: https://www.supermicro.com/es/glossary/heterogeneous-computing. 
12. Capterra.es. [En línea]. Disponible en: https://www.capterra.es/glossary/1148/heterogeneous-architecture.
13. “What is edge architecture?”, Redhat.com. [En línea]. Disponible en: https://www.redhat.com/en/topics/edge-computing/what-is-edge-architecture.
14. “What is edge architecture?”, GeeksforGeeks, 24-jun-2024. [En línea]. Disponible en: https://www.geeksforgeeks.org/cloud-computing/what-is-edge-architecture. 
15. Justas, “¿Computación en el borde? Todo lo que necesitas saber y el auge de la inteligencia artificial”, visionplatform, 12-may-2024. [En línea]. Disponible en: https://visionplatform.ai/es/computacion-en-el-borde-todo-lo-que-necesitas-saber-y-el-auge-de-la-inteligencia-artificial. 
16. Daniel, “Edge Computing: ¿Qué es y para qué sirve?”, DataScientest, 09-may-2024. [En línea]. Disponible en: https://datascientest.com/es/edge-computing. 
📅 **Última actualización:** 2025
