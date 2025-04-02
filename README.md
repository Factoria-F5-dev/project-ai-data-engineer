# 🚀 PROYECTO DATA ENGINEER: Proceso ETL

![Data Engineer](https://github.com/user-attachments/assets/724b03b7-74f1-4a28-b0da-65484e58e827)

## 📜 Briefing: PROYECTO DATA ENGINEER

### 🔍 Planteamiento  

Bienvenidos al equipo de ingenieros de datos freelance de DataTech Solutions.
Han sido seleccionados para abordar un proyecto crucial para nuestro cliente, una empresa
líder en recursos humanos llamada "HR Pro".
El objetivo del proyecto es diseñar e implementar un sistema de gestión de datos eficiente
para HR Pro, que les permita organizar y analizar grandes volúmenes de datos procedentes
de diversas fuentes, como solicitudes de empleo, registros de nómina, encuestas de
empleados, entre otros. Cada uno de ustedes aporta habilidades únicas en extracción,
transformación y carga de datos (ETL), así como experiencia en el uso de tecnologías como
Apache Kafka, MongoDB y bases de datos SQL.
Deberán diseñar un proceso ETL robusto para integrar datos en un sistema unificado,
organizar y almacenar datos de manera eficiente tanto en una base de datos MongoDB
como en un almacén de datos SQL, implementar el sistema en un entorno Dockerizado
para garantizar la escalabilidad y la portabilidad, y trabajar con una amplia variedad de
datos, desde información personal hasta registros financieros y métricas de rendimiento.
Se espera que entreguen un sistema funcional y bien documentado que permita a HR Pro
gestionar y analizar eficientemente sus datos de recursos humanos.

#### DISCLAIMER
Los datos no son reales, sino que se van generando de manera aleatoria y enviandose a un
servidor de Apache Kafka. Todo el código para lanzar tanto el servidor Kafka como el
generador de datos se encuentra en este repositorio de GitHub, el cuál también está
documentado con instrucciones sobre su uso:
[proyecto](https://github.com/Factoria-F5-dev/data-engineering-educational-project)
Es **ABSOLUTAMENTE FUNDAMENTAL** que **NO** se acceda a leer el código que genera
esos datos.
Hacerlo supondría conocer los detalles de por qué los datos son cómo son y eso estaría
muy alejado de lo que sería un caso real, reduciendo el aspecto pedagógico del proyecto.
---

## 🎯 Objetivos del Proyecto  

* **Implementar proceso ETL.**  
* **Preprocesar los datos.**  
* **Trabajar con colas de mensajes.**  
* **Implementar bases de datos SQL/NoSQL.**   

---

## 📦 Condiciones de Entrega  

Para la fecha de entrega, los equipos deberán presentar:  

✅ **Repositorio en GitHub** con el código fuente documentado.

✅ **Un programa dockerizado** que se conecte al servidor de Kafka, procese los datos que lee y los guarde de manera ordenada en una base de datos MongoDB y una SQL a elegir

✅ **Demo en vivo** mostrando el funcionamiento de la aplicacion.

✅ **Presentación técnica**, explicando los objetivos, desarrollo y tecnologías utilizadas.

✅ **Tablero Kanban** con la gestión del proyecto (Trello, Jira, etc.).  

---

## ⚙️ Tecnologías Recomendadas  

- **Control de versiones:** Git / GitHub  
- **Entorno de ejecución:** Docker  
- **Lenguaje principal:** Python  
- **Librerías útiles:** Kafka, Pandas
- **Bases de Datos:** MongoDB, SQL
- **Gestión del proyecto:** Trello, Jira, Github  

---

## 🏆 Niveles de Entrega  

### 🟢 **Nivel Esencial:**  
✅ Configurar correctamente el consumer de Kafka para consumir los miles de mensajes por segundo del servidor de kafka en tiempo real.

✅ Persistir los mensajes de kafka en una base de datos documental (por ejemplo MongoDB).

✅ Procesar los datos y agrupar los distintos tipos de datos de cada persona (Personal data, Location, Professional data, Bank Data y Net Data) en un único registro.

✅ Persistir los datos procesados y agrupados en una base de datos relacional (MySQL, Postgres…).

✅ Repositorio Git con ramas bien organizadas y commits limpios y descriptivos.

✅ Documentación del código y un README en GitHub.  

### 🟡 **Nivel Medio:**  
✅ Incluir un sistema de logs.

✅ Incluir tests unitarios.

✅ Dockerizar la aplicación utilizando docker y docker compose.


### 🟠 **Nivel Avanzado:**  
✅ Utilizar una base de datos en caché (por ejemplo redis) como base de datos intermedia antes de almacenar los datos en otro tipo de sistema de almacenamiento, para mejorar la captura de datos en tiempo real.

✅ Monitorizar el funcionamiento de la aplicación (cuántos mensajes se consumen, a qué velocidad, cuanto tardan en procesarse, cuanto tardan en persistirse, rendimiento general de la aplicación, etc). Se pueden utilizar herramientas como Prometheus.

✅ Crear una API para conectarse a la base de datos relacional y poder hacer consultas sobre la información final procesada disponible en la base de datos SQL.

### 🔴 **Nivel Experto:**  
✅ Automatizar la carga de datos para que la información de las bases de datos se vaya actualizando de forma continua mientras el servidor de kafka se mantiene ejecutándose y enviando mensajes.

✅ Crear una frontend sencillo (por ejemplo: streamlite, gradio) desde el que poder consultar los datos de los clientes.

---

## 📊 Evaluación  

Se considerarán los siguientes criterios:  

✅ Procesar y almacenar datos de eventos en tiempo real
 

Más detalles en: [roadmap-mad-ai-p4.coderf5.es](https://roadmap-mad-ai-p4.coderf5.es/)  

 

