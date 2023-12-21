# Identificación de requisitos de rendimiento 🚀

La "Identificación de requisitos de rendimiento" es importante en la planificación de pruebas de rendimiento. Aquí se definen los estándares y expectativas para el comportamiento del sistema bajo diferentes condiciones.

La identificación eficaz de requisitos de rendimiento es importante para garantizar que las pruebas de rendimiento sean relevantes, adecuadas y proporcionen resultados significativos que ayuden a mejorar la calidad del software.

Esta etapa incluye:

1. **Entender los Objetivos del Negocio**: Comprender qué es lo más importante para los usuarios y el negocio. Esto podría ser la velocidad de respuesta, la capacidad para manejar altos volúmenes de tráfico, o la estabilidad bajo carga pesada.

2. **Establecer Criterios de Rendimiento**: Definir métricas específicas como tiempo de respuesta, throughput (cantidad de trabajo realizado por unidad de tiempo), y límites de capacidad. Estos criterios deben estar alineados con las expectativas y necesidades del negocio.

3. **Análisis de Usuarios y Carga**: Determinar patrones de uso del sistema, como el número de usuarios concurrentes y las operaciones típicas que realizan. Esto ayuda a modelar escenarios de prueba realistas.

4. **Requisitos Técnicos y de Infraestructura**: Evaluar la infraestructura actual y las capacidades tecnológicas para identificar posibles limitaciones y requerimientos para las pruebas.

5. **Benchmarking y Estándares de la Industria**: Referir a benchmarks o estándares de la industria para establecer objetivos de rendimiento. Esto puede incluir comparar el rendimiento con sistemas similares o competidores.

## Practica

Veamos un ejemplo ficticio:

1. **Entender los Objetivos del Negocio**:
   - La empresa "StreamFast", una plataforma de streaming de video, quiere asegurarse de que sus usuarios puedan ver videos sin interrupciones ni retrasos, especialmente durante los lanzamientos de episodios populares.

2. **Establecer Criterios de Rendimiento**:
   - Para "StreamFast", un criterio de rendimiento podría ser que el tiempo de inicio de un video no debe exceder los 2 segundos, y el sistema debe soportar 100,000 usuarios concurrentes durante los estrenos de series populares.

3. **Análisis de Usuarios y Carga**:
   - Se observa que la mayoría de los usuarios de "StreamFast" ven contenido en horas pico (8-10 PM), con un patrón común de cambio rápido entre diferentes videos antes de seleccionar uno para ver completamente.

4. **Requisitos Técnicos y de Infraestructura**:
   - La infraestructura actual de "StreamFast" se basa en servidores en la nube con autoescalado, pero se necesita evaluar si esta configuración puede manejar picos repentinos de tráfico durante los estrenos.

5. **Benchmarking y Estándares de la Industria**:
   - "StreamFast" podría establecer un benchmark comparando su tiempo de carga de video con el de competidores líderes en el mercado, asegurándose de estar al menos 10% por encima del promedio de la industria para ofrecer una experiencia superior al usuario.

Basándonos en los ejemplos ficticios para "StreamFast", los estándares de rendimiento podrían ser:

1. **Tiempo de Inicio de Video**: El video debe comenzar a reproducirse en no más de 2 segundos después de que el usuario lo seleccione.

2. **Capacidad de Usuarios Concurrentes**: El sistema debe ser capaz de soportar al menos 100,000 usuarios concurrentes, especialmente durante los lanzamientos de nuevos episodios o series.

3. **Rendimiento en Horas Pico**: El sistema debe mantener su rendimiento óptimo durante las horas pico (8-10 PM), donde se observa un mayor tráfico de usuarios.

4. **Manejo de Picos de Tráfico**: La infraestructura en la nube con autoescalado debe ser capaz de manejar aumentos repentinos en el tráfico sin degradar la calidad del servicio.

5. **Benchmarking con Competidores**: El tiempo de carga de video de "StreamFast" debe ser al menos un 10% más rápido que el promedio de sus principales competidores, estableciendo un alto estándar en la industria de streaming.

Estos estándares son específicos y mensurables, proporcionando objetivos claros para las pruebas de rendimiento y asegurando que el sistema cumpla con las expectativas tanto del negocio como de los usuarios.

---

## Referencias 🌐

- [TechTarget - Prerequisites for Performance Testing](https://www.techtarget.com/searchsoftwarequality/answer/Software-performance-testing-requirements-and-prerequisites)
- [Stackify - Performance Testing Types, Steps, Best Practices, and Metrics](https://stackify.com/performance-testing/)
- [Foulk Consulting - What Are the Requirements of Performance Testing?](https://foulkconsulting.com/what-are-the-requirements-of-performance-testing/)

---

### [Ir al cuestionario 📝](../../cuestionario/03.planificacion_pruebas_de_rendimiento/identificacion.md)

### [Ir al temario 🔍](../../readme.md)
