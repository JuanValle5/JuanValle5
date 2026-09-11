<div align="center">

# 👋 Hola, soy Juan José Valencia
### **Backend Developer & Software Engineer**
*Construyendo arquitecturas distribuidas de alto rendimiento, microservicios resilientes y aplicaciones móviles modernas.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JuanValle5)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:juanjo.valencia.j@gmail.com)

</div>

---

## 🚀 Sobre Mí

Soy estudiante de **Ingeniería de Sistemas (8vo semestre)** y **Tecnología en Electrónica Industrial (2do semestre)** en la **Universidad del Valle** (Colombia). 

Me especializo en el desarrollo **Backend** y la ingeniería de software orientada a la producción:
* 🏛️ **Arquitectura de Software:** Diseño de sistemas escalables basados en **Microservicios**, comunicación orientada a eventos (**Event-Driven**) y principios de **Clean Architecture** y **Domain-Driven Design (DDD)**.
* ☕ **Ecosistema Java & Spring:** Implementación de APIs robustas con **Java 17/21**, **Spring Boot 3**, **Spring Cloud**, **Spring Security (JWT/RBAC)** y persistencia relacional con **JPA/Hibernate** y **PostgreSQL**.
* 📱 **Desarrollo Móvil:** Creación de aplicaciones nativas en **Android** utilizando **Kotlin**, **Jetpack Compose** y **MVVM**.
* 📊 **Ingeniería de Datos:** Modelado dimensional de bodegas de datos (**Kimball Star Schema**), pipelines **ETL** automatizados en Python y consultas analíticas avanzadas (**OLAP**).

---

## 🛠️ Stack Tecnológico

| Área | Tecnologías & Herramientas |
| :--- | :--- |
| **Lenguajes Principales** | ![Java](https://img.shields.io/badge/Java_17%2F21-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) |
| **Backend & Microservicios** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) |
| **Bases de Datos & Cloud** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![Neon](https://img.shields.io/badge/Neon_Serverless-00E599?style=flat-square&logo=postgresql&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| **Móvil (Android)** | ![Android](https://img.shields.io/badge/Android_SDK-3DDC84?style=flat-square&logo=android&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![Coroutines](https://img.shields.io/badge/Coroutines_%26_Flow-7F52FF?style=flat-square&logo=kotlin&logoColor=white) |
| **Data Engineering & BI** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square) ![Star Schema](https://img.shields.io/badge/Kimball_Star_Schema-brightgreen?style=flat-square) |
| **Herramientas & DevOps** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |

---

## 🌟 Proyectos Destacados

### 🎫 [VivaEventos S.A.S. — Plataforma de Boletería y Eventos](https://github.com/JuanValle5/vivaeventos)
> *Arquitectura de Microservicios distribuida, orientada a eventos y preparada para alta concurrencia.*

* **Stack:** Java 21, Spring Boot 3.3.4, Spring Cloud Gateway, RabbitMQ, PostgreSQL (Multi-DB por servicio), Docker Compose, JWT, Mailpit.
* **Aspectos Destacados:**
  * **Ecosistema de 7 microservicios desacoplados:** `gateway-service`, `auth-service`, `event-service`, `order-service`, `payment-service`, `ticket-service` y `notification-service`.
  * **Reserva Atómica Anti-Sobreventa:** Algoritmo de bloqueo de cupos en base de datos con expiración por TTL para evitar sobreventa en eventos masivos.
  * **Mensajería Asíncrona:** Integración con **RabbitMQ** para desacoplar el procesamiento de pagos, emisión de boletos con códigos QR firmados criptográficamente y despacho de correos electrónicos.
  * **Seguridad:** Control de acceso basado en roles (**RBAC**) y validación centralizada mediante JWT en el Gateway.

---

### 📅 [Turny — Ecosistema Inteligente de Agendamiento de Citas](https://github.com/JuanValle5/turny-app)
> *Solución integral para optimizar reservas y gestión operativa en barberías, salones de belleza y spas.*

* **Móvil ([`turny-app`](https://github.com/JuanValle5/turny-app)):** Aplicación Android nativa desarrollada en **Kotlin** con **Jetpack Compose**, **Material 3**, y arquitectura **Clean Architecture + MVVM + UDF**. Manejo asíncrono con Coroutines y StateFlow.
  * *Modo Cliente:* Descubrimiento de negocios por proximidad/código, catálogo de servicios, selección de turnos en tiempo real y gestión de reservas.
  * *Modo Negocio:* Panel de administración con agenda semanal interactiva, control de estados de citas y configuración de disponibilidad de personal.
* **Backend ([`turny-API`](https://github.com/JuanValle5/turny-API)):** API REST en **Java** + **Spring Boot** + **PostgreSQL** con autenticación JWT y persistencia mediante Spring Data JPA.

---

### 🛒 [Retail Data Warehouse & Executive Business Intelligence](https://github.com/JuanValle5/ProyectoCienciaDeDatos1)
> *Bodega de datos en la nube (Kimball Star Schema), pipeline ETL modular y analítica de retail.*

* **Stack:** Python 3, PostgreSQL (Neon Cloud), SQLAlchemy, Pandas, Matplotlib, Seaborn, SQL Analítico.
* **Aspectos Destacados:**
  * **Modelado Dimensional:** Diseño de un **Modelo Estrella (Star Schema)** con 5 dimensiones (`dim_customer`, `dim_category`, `dim_payment`, `dim_mall`, `dim_date`) y tabla de hechos central `fact_sales` sobre 99,457 transacciones.
  * **Pipeline ETL Idempotente:** Ingesta por lotes, deduplicación y resolución de claves subrogadas enteras para soportar Dimensiones de Cambio Lento (SCD Tipo 2).
  * **Optimización & Analítica:** Aceleración con índices B-Tree, consultas analíticas con funciones de ventana (MoM Growth, Pareto 80/20) y análisis de riesgo operativo por pagos en efectivo.

---

### 📦 [StockWise API — Sistema de Gestión de Inventarios](https://github.com/JuanValle5/StockWiseAPI)
> *API RESTful para administración y control de existencias, productos y movimientos de almacén.*

* **Stack:** Java, Spring Boot, Spring Data JPA, PostgreSQL, Hibernate, Swagger / OpenAPI.
* **Aspectos Destacados:** Modelado relacional para control de stock, gestión de categorías, registro de entradas y salidas, validaciones de negocio y documentación interactiva de endpoints.

---

## 📊 Estadísticas de GitHub

<div align="center">

![JuanValle5's GitHub Stats](https://github-readme-stats.vercel.app/api?username=JuanValle5&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=JuanValle5&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 📫 Conectemos

* 💼 **LinkedIn:** [linkedin.com/in/juan-jose-valencia](https://linkedin.com)
* 📧 **Correo personal:** [juanjo.valencia.j@gmail.com](mailto:juanjo.valencia.j@gmail.com)
* 🎓 **Correo institucional:** [juan.j.valencia@correounivalle.edu.co](mailto:juan.j.valencia@correounivalle.edu.co)
* 📍 **Ubicación:** Colombia

<div align="center">
  <sub>Diseñado con dedicación y buenas prácticas de ingeniería de software.</sub>
</div>
