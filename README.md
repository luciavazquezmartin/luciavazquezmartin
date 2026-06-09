# Lucía Vázquez Martín
### Data Engineer | Database Specialist & Business Intelligence

Estudiante de último curso de **Ingeniería Informática en la Universidad de Zaragoza**. Mi enfoque profesional está completamente orientado al **ciclo de vida completo del dato**: desde el despliegue de infraestructuras críticas y administración avanzada de SGBD, hasta la automatización de flujos ETL/ELT, el análisis predictivo (ciencia de datos) y la explotación mediante Business Intelligence.

Concibo la ingeniería como una herramienta para generar valor real. Por ello, complemento mi perfil técnico con una sólida base en **viabilidad y rentabilidad económica de producto (SaaS/IoT)** y metodologías avanzadas de **User Research**, asegurando que las arquitecturas de datos den soporte a decisiones de negocio eficientes y orientadas al usuario.

---

## Ingeniería de datos, automatización y Big Data

### Automatización del flujo de datos de Montgomery
Diseño y despliegue de una arquitectura backend automatizada para la extracción, procesamiento y carga incremental de datos de criminalidad en la nube.
* **Tecnologías:** KNIME (Pro Cloud), MongoDB Atlas (NoSQL), Random Forest.
* **Hitos técnicos:**
  * **Extracción e ingesta:** Conexión directa vía API mediante nodos `CSV Reader`, eliminando scripts locales y descargas manuales.
  * **Carga incremental eficiente:** Lógica de comparación con históricos locales (`crimenes_ya_subidos.csv`) para subir exclusivamente registros estrictamente nuevos a MongoDB Atlas.
  * **Modelado predictivo:** Entrenamiento en paralelo de tres modelos Random Forest para el cálculo diario del índice de criminalidad (IC).
  * **Automatización serverless:** Despliegue operativo mediante *schedules* diarios automáticos en KNIME Community Hub (Plan Pro), garantizando la actualización autónoma del sistema.

### Arquitectura y administración de bases de datos avanzadas
Repositorio enfocado en la infraestructura, rendimiento y seguridad de sistemas de almacenamiento relacionales, federados y NoSQL distribuidos.
* **Tecnologías:** Docker, PostgreSQL, Oracle XE, PL/SQL, Hibernate/JPA, Apache Cassandra, Apache Spark.
* **Hitos técnicos:**
  * **Infraestructura y seguridad:** Despliegue en contenedores Docker implementando control de accesos estricto (RBAC) y políticas automatizadas de copias de seguridad (*backups*).
  * **Extensiones del modelo:** Creación de lógica de negocio en el motor mediante tipos de datos abstractos (UDTs), herencia y programación de *Triggers* complejos en Oracle.
  * **Sistemas federados:** Interconexión de bases de datos independientes y heterogéneas mediante DB Links, realizando auditorías de integridad referencial y resolución de entidades aisladas.
  * **Persistencia avanzada & Big Data:** Análisis comparativo de trazas de ejecución ORM (JPQL vs SQL Nativo) y modelado masivo tolerante a fallos orientado a consultas en Cassandra explotado con Spark.

---

## Business Intelligence y ciencia de datos

### Inteligencia de negocio y minería de datos
Portafolio que consolida el diseño analítico y la extracción de conocimiento predictivo, combinando modelado relacional-dimensional con ciencia de datos aplicada.
* **Tecnologías:** Lenguaje R, KNIME, Power BI, SQL Avanzado (CUBE, ROLLUP, MDX).
* **Hitos técnicos:**
  * **Estudio analítico COVID-19 (R):** Segmentación avanzada de países mediante K-Means (K=5), optimizado con el método del codo y validado con dendrogramas jerárquicos. Aplicación de regresión lineal múltiple para aislar variables macroeconómicas.
  * **Diseño de Data Marts:** Modelado dimensional bajo esquema en estrella para entornos de aviación y gestión hospitalaria.
  * **Explotación BI:** Construcción de flujos ETL complejos para el procesamiento de históricos de vuelos y diseño de cuadros de mando funcionales combinados con consultas multidimensionales avanzadas.

---

## Estrategia de producto, viabilidad financiera y UX

### Funny Bowling & Piezo InEar — Modelado de negocio y rentabilidad
Especialización en la capa estratégica y económica que define la viabilidad de una solución de software o hardware IoT antes de su desarrollo.
* **Habilidades:** Modelado Canvas, análisis financiero proyectivo a 3 años (*Unit Economics*), investigación cualitativa de mercado y definición de KPIs analíticos (Google Analytics 4).
* **Enfoque:** Evaluación estricta de la monetización de plataformas SaaS B2B/B2C, control presupuestario de despliegues y diseño de directrices de usabilidad orientadas a la conversión.

### Vitalia — User Research y arquitectura de la información
Fase completa de investigación de usuario aplicada al entorno de la robótica social asistencial (interacción Persona-Robot), asegurando la usabilidad del sistema sin comprometer su arquitectura.
* **Metodologías:** Diseño Centrado en el Usuario (DCU), matrices de priorización de requisitos (impacto/esfuerzo), mapas de empatía, definición de arquetipos de persona y *User Journey Maps*.

---

## Stack tecnológico consolidado

* **Motores de bases de datos:** PostgreSQL, Oracle XE, MongoDB Atlas, Apache Cassandra.
* **Ingeniería de Datos / ETL:** KNIME, Apache Spark, Docker, SQL (DDL/DML), CQL.
* **Ciencia de datos y análisis:** Lenguaje R (K-Means, Regresión), WEKA, Power BI.
* **Estrategia y metodología:** Modelado Canvas, proyecciones financieras, metodologías de UX (User Research / DCU).
