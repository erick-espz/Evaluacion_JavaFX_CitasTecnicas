# Sistema de Gestión de Citas Técnicas - TecnoAsistencia Nicaragua S.A.

Aplicación de escritorio desarrollada en **JavaFX** conectada a una base de datos relacional **PostgreSQL** mediante **JDBC** para la gestión integral de clientes y citas técnicas de mantenimiento y reparación de equipos informáticos.

---

## Integrantes del Equipo y Distribución de Responsabilidades

| Integrante | Usuario GitHub | Rol / Responsabilidades Asignadas |
| :--- | :--- | :--- |
| **Erick Espinosa** | [@erick-espz](https://github.com/erick-espz) | Integración final, arquitectura del proyecto, `ConexionBD` y coordinación. |
| **Javier Berríos** | [@BJavi2106](https://github.com/BJavi2106) | Capa de datos (DAO) y modelo de la entidad `CitaTecnica`. |
| **Josue Reyes / Castillo** | [@castillozzzz](https://github.com/castillozzzz) | Interfaces FXML, vistas y controlador `CitaController`. |
| **Julián Torrez** | [@torrez-julian](https://github.com/torrez-julian) | Validación de datos (`Validador.nombreValido`), pruebas de aceptación y documentación técnica. |

---

##  Requisitos del Sistema
- **Java Development Kit (JDK):** Versión 17 o superior.
- **JavaFX SDK:** Versión 17 o superior.
- **Motor de Base de Datos:** PostgreSQL 14+ (Instalación nativa o Docker).
- **Gestor de Dependencias:** Maven 3.8+.
- **Entorno de Desarrollo (IDE):** IntelliJ IDEA.

---

##  Configuración e Instalación de la Base de Datos PostgreSQL

1. **Creación de la Base de Datos:**
   Abre **pgAdmin 4** (o la consola `psql`) y crea la base de datos:
   ```sql
   CREATE DATABASE gestion_citas;