# Tarea 9 - Creación y Normalización de Base de Datos

## 📌 Descripción
Esta tarea consiste en **diseñar, normalizar y crear la base de datos** en **SQL** para una plataforma de empleos. 

### 📊 Base de Datos
La base de datos sigue **buenas prácticas de normalización hasta la 3FN** para garantizar eficiencia y evitar redundancia de datos.

### 📌 Tablas principales:
1. **Empresas**: Registro de empresas con información de contacto.
2. **Candidatos**: Almacena datos de los candidatos y su CV digital.
3. **OfertasEmpleo**: Contiene las ofertas laborales publicadas por las empresas.
4. **Aplicaciones**: Registra las postulaciones de los candidatos a las ofertas.

### 📂 Archivo SQL
El script para generar la base de datos en **SQL** se encuentra en el archivo [`job_portal_db.sql`](./job_portal_db.sql). 

## 🚀 Instalación
### 1️⃣ Requisitos previos
- **XAMPP** o cualquier servidor que soporte **MySQL**.
- Un cliente MySQL (phpMyAdmin, MySQL Workbench, etc.).

### 2️⃣ Pasos
1. Clonar el repositorio:
   ```sh
   git clone https://github.com/tu-repo/tarea9-db.git
   ```
2. Importar la base de datos en MySQL:
   - Abrir phpMyAdmin o un cliente MySQL.
   - Crear una base de datos llamada **JobPortal**.
   - Ejecutar el script `job_portal_db.sql`.

## 📜 Integrantes
- **Luis Ángel Sánchez** - Matrícula: *2023-1681*
- **Luis Elier Pujol** - Matrícula: *2023-1667*

## 📌 Notas
- **Índices** han sido agregados a las tablas para optimizar consultas.
- Se implementaron **claves foráneas** con restricciones **ON DELETE CASCADE**.

---
📌 **Este repositorio contiene únicamente el diseño y creación de la base de datos como parte de la Tarea 9.**
