# Perfil de los Integrantes
## Jorge Borbolla A01383867
### Fortalezas:

 * Trabajador
 * Buen expositor
 * Siempre al pendiente
 * Buen compañero de equipo
 
 ### Áreas de oportunidad:
 * Trabajo bajo presión
 * Estrés cuando hay mucho trabajo
 * Perfeccionista
 ### Expectativas:
 * Espero que durante estas cinco semanas pueda desarrollarme como ingeniero en tecnologías computacionales al igual que aprender a usar nuevas herramientas que serán de gran ayuda para diversos proyectos en el futuro, al igual que mi equipo y yo estemos satisfechos con el producto final.
 ### Logros esperados:
 * Espero lograr hacer todas las actividades de este curso de la mejor manera posible al igual que poder cumplir todas mis tareas como estudiante y compañero de equipo.
 * Espero obtener el conocimiento adecuado para poder describir y realizar las actividades que se realizan en clase al igual que la situación problema para presentar un trabajo completo y satisfactorio.

## Javier Agostini A00827216
### Fortalezas:

* Comprometido
* Observador
* Organizado
* Aprendizaje rápido
### Áreas de oportunidad:
* Ambicioso
* Procrastinar
### Expectativas:
* Aprender sobre los sistemas multiagentes, gráficas computacionales, así como su importancia y usos.
### Logros esperados:
* Conocer y dominar nuevas tecnologías y herramientas.
* Desarrollar un proyecto exitoso y de valor.

## Omar Pérez A01383853
### Fortalezas:
* Pasión por la programación
* Autodidacta
* Responsable
* Trabajador
* Trabajo bajo presión
### Áreas de oportunidad:
* Dificultad al exponer
* Perfeccionista
* Procrastinar
### Expectativas:
* Aprender el simular situaciones reales con el uso de sistemas multiagentes y gráficas computacionales, donde aparte de crear el sistema, también crearemos las visuales del mismo y al final podremos ver el funcionamiento de todo en conjunto, un bloque que será interesante y que tal vez tenga algo que ver con una introducción a la inteligencia artificial.
### Logros esperados:
* Espero aprender un poco más sobre el uso de Unity en la creación de distintos medios, como puede ser la creación de este mismo sistema multiagente, donde seguramente será todo un reto desarrollar la situación problema del bloque.

## Daniela Garza A00829404
### Fortalezas:
* Manejo de tiempo
* Adaptibilidad
* Curiosidad
* Trabajo bajo presión
* Trabajo en equipo
### Áreas de oportunidad:
* Productividad
* Depuración de errores
* Procrastinar
### Expectativas:
* Obtener las herramientas necesarias para el curso
* Enriquecer mi conocimiento
* Comprender y analizar lo necesario para poder sacar adelante el curso
### Logros esperados:
* Tener más conocimiento sobre Unity y sobre programar en C#, así como hacer las actividades del curso a tiempo y en forma para tener los conocimientos necesarios para poder concluir la clase.

## Nuestro compromiso:
* Siempre estar al pendiente de cualquier tarea, estar en comunicación constante, ser responsable con los trabajos, ayudarnos entre todos para poder sacar adelante el reto, asistir a las clases mediante zoom o presencial y contestar el grupo de whatsapp.

# Descripción del proyecto a desarrollar
La movilidad urbana, se define como la habilidad de transportarse de un lugar a otro <sup>1</sup> y es fundamental 
para el desarrollo económico y social y la calidad de vida de los habitantes de una ciudad. Desde hace 
un tiempo, asociar la movilidad con el uso del automóvil ha sido un signo distintivo de progreso. Sin 
embargo, esta asociación ya no es posible hoy. El crecimiento y uso indiscriminado del automóvil —que 
fomenta políticas públicas erróneamente asociadas con la movilidad sostenible—genera efectos negativos 
enormes en los niveles económico, ambiental y social en México.

Durante las últimas décadas, ha existido una tendencia alarmante de un incremento en el uso de automóviles en México. Los Kilómetros-Auto Recorridos (VKT por sus siglas en Inglés) se han triplicado, de 106 millones en 1990, a 339 millones en 2010. Ésto se correlaciona simultáneamente con un incremento en los impactos negativos asociados a los autos, como el smog, accidentes, enfermedades y congestión vehicular<sup>2</sup>.

El reto consiste en proponer una solución al problema de movilidad urbana en México, mediante un enfoque 
que reduzca la congestión vehicular al simular de manera gráfica el tráfico, representando la salida de 
un sistema multi agentes.

De acuerdo con la Federal Highway Administration del Departamento de Transporte de EEUU<sup>3</sup>, más del 50% los accidentes automovilísticos ocurren cerca de o en alguna intersección. Un estudio publicado por la National Highway Traffic Safety Administration del Departamento de Transporte de EEUU <sup>4</sup> mostró que el 96% de los accidentes que ocurren en las intersecciones son causados por errores de los conductores. Dichos accidentes son comúnmente colisiones laterales, las cuales generan mayores heridas y daños, debido a que los vehículos tienen menos protección en dichas zonas.

*Principales causas de accidentes automovilísticos*
* Falta de atención a la intersección
* Suposiciones erróneas sobre las acciones de otros conductores
* Dar vuelta con una vista obstruida
* Maniobras ilegales
* Distraciones 
* Ignorar señales de tráfico

*Principales heridas causadas por accidentes automovilísticos*
* Cerebrales o en la cabeza
* Hiperextensión cervical u otras heridas de cuello
* Heridas de espalda o de la médula espinal
* Heridas en órganos internos
* Heridas en tejido blando

Debido al alto número de accidentes ocurridos en intersecciones y tomando en cuenta que dichos accidentes ocurren principalmente por errores de los conductores, se considera pertinente desarrollar un sistema multiagente controlado por semáforos inteligentes que controlen el flujo vehicular, esto con el motivo de evitar accidentes y disminuir el margen de error ocasionado por los conductores.

De esta manera, es posible simular un sistema de intersección inteligente, analizar las interacciones y comportamientos de los agentes dentro del sistema y, a partir de los resultados obtenidos, analizar si dicha solución es eficiente, con el objetivo de que, en un futuro, sea posible implementarse en una intersección real.



# Identificación de los agentes involucrados
Para realizar un modelo de simulación de gráfico, es necesario poder definir bien que agentes se ocupan para realizar dicha simulación, por el momento hemos decidio que los agentes principales para este proyecto serán los siguientes:
* Automoviles
* Semaforos
* Transito
* Peatones

Estos agentes se escogieron a partir de las acciones que cada uno de ellos hacen para la situación problema, puesto que cada uno de ellos afectan al otro, condiciones como si un semaforo esta encendido de cierto color puede determinar si hay un trafico fluido o tardado. Esto tendra sentido en el apartado donde mostramos los diagramas de flujo y de procesos de los agentes. 

# Diagramas
En este apartado se pueden encontrar los diagramas principales la cual nos basamos para la creación de los agentes, la cual consiste en los siguientes diagramas:
* Diagrama de Clases
![alt text](https://i.ibb.co/HGy20cq/Diagramas-Clase.png)
* Diagrama de Protocolos de Interacción
![alt text](https://i.ibb.co/GW867bm/Protocolos-Diagrama.png)

# Plan de trabajo
![alt text](https://i.ibb.co/z60c84w/P1-Arranque-de-Proyecto.png "Diagrama Gantt")

# Actividades Pendientes
* P2. Actividad de Semana 2
* P3. Actividad de Semana 3
* P4. Actividad de Semana 4
* P5. Presentación del reto

# Aprendizaje Adquirido
Los aprendizajes que adquirimos al realizar esta actividad fueron: 
* Identificación de los agentes que utilizaremos en el reto.
* El contexto y situación sobre la cual basaremos nuestro proyecto.
* Creación de diagramas de clases y protocolos para la definición de los agentes.

# Presentación
La presentación donde se puede encontrar en un formato más accesible se puede encontrar dandole click a [esta liga.](https://docs.google.com/presentation/d/1z-zLMCN0JRH5F9-vAV_bfeX2HRS1jH5wa5MagnbsXd0/edit?usp=sharing)

# Referencias 
 <sup>1</sup> Handy, Susan. (2002). *Accessibility- Vs. Mobility-Enhancing Strategies for Addressing Automobile Dependence in the U.S. European Conference of Ministers of Transport.* Retrieved on February 21, 2012, from http://www.des.ucdavis.edu/faculty/handy/ECMT_report.pdf.
 
 <sup>2</sup> Medina Ramírez, Salvador. (2012). *Transforming Urban Mobility in Mexico: Towards Accesible Cities Less Reliant on Cars.* Institute for Transportation and Development Policy (ITDP Mexico). Retrieved on August 7, 2019, from http://mexico.itdp.org/wp-content/uploads/Transforming-Urban-Mobility-in-Mexico.pdf
 
 <sup>3</sup> Federal Highway Administration. (Agosto 26, 2021). *Intersection Safety.* Retrieved on September 1, 2021, from https://highways.dot.gov/research/research-programs/safety/intersection-safety
 
 <sup>4</sup> Fowkes & Hasanbasic. (n.d.). *Intersection Accidents.* Retrieved on September 1, 2021, from https://www.fhlawpa.com/tampa-car-accident-lawyer/intersection-accidents/
