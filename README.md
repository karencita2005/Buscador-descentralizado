# Buscador-descentralizado

# 1. Problema
¿Qué situación, necesidad o problema quieren atender?\n
El problema central es que aunque los buscadores de internet tradicionales son funcionales,
tienen limitaciones estructurales como falta de transparencia, resultados basura y
dependencia a infraestructura centralizada. Estas características pueden restringir la
diversidad de resultados y generar vulnerabilidades informativas a futuro, evidenciando la
necesidad de explorar modelos alternativos más distribuidos, resilientes y controlados por
los propios usuarios.

# 2. Objetivo general y objetivos particulares 
¿Qué resultado concreto quieren conseguir con el proyecto? 
El objetivo principal de este proyecto es desarrollar un buscador descentralizado basado en
una red nodos P2P que permita a los usuarios acceder a información de forma transparente, equitativa y sin depender de una entidad central.

Objetivos particulares
* Diseñar una arquitectura de red distribuida en múltiples nodos para garantizar la resiliencia del sistema y eliminar los riesgos asociados a la centralización, como la censura o manipulación de información.

* Implementar mecanismos de control y privacidad que permitan a los usuarios definir sus propios criterios de búsqueda, asegurando una recolección de datos personales significativamente menor a la de los buscadores tradicionales.

* Analizar el rendimiento y la escalabilidad del sistema evaluando la relación entre el número de nodos activos, el tiempo de latencia y la desviación estándar de la carga de búsquedas por nodo.

* Evaluar la eficacia y relevancia del buscador mediante la medición continua del porcentaje de precisión (resultados relevantes frente a totales) y la tasa de éxito de las consultas completadas correctamente.


# 3. Alcance
¿Qué sí contempla el proyecto?
El alcance del proyecto modular contempla el diseño e implementación de un motor de búsqueda distribuido con arquitectura peer-to-peer (P2P), limitando su operación exclusivamente a una red controlada como los dominios de la UDG. Para lograrlo, se construirá una red de nodos autónomos que funcionarán de manera simultánea como clientes y servidores, encargándose cada uno de rastrear, indexar y almacenar información localmente a través de la creación de índices invertidos. Toda la comunicación de esta infraestructura se gestionará mediante sockets TCP/UDP, integrando mecanismos P2P que permitirán el descubrimiento de nodos, el enrutamiento en la red, la propagación de las consultas y la agregación ordenada de los resultados locales.

# 4. Fuera de alcance
¿Qué cosas deliberadamente no realizará el proyecto?
Deliberadamente no indexará todo internet, debido a que resulta imposible para los fines de escalabilidad del proyecto; se restringirá únicamente a dominios específicos o universitarios, al igual que no dependerá de una infraestructura o entidad central (modelo cliente-servidor tradicional) para alojar, indexar o gestionar la información y no implementará algoritmos de ranking opacos ni utilizará publicidad pagada o posicionamiento optimizado que pueda sesgar la visibilidad y relevancia real de los resultados para el usuario. 

# 5. MVP (Minimum Viable Product)
¿Cuál es la versión mínima del proyecto que permitiría demostrar que la propuesta funciona?


