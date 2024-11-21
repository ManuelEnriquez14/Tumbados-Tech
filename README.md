# Tumbados Tech Company - Gestión de Productos

**Tumbados Tech Company** es una aplicación web desarrollada para la gestión eficiente de productos en una tienda de componentes para computadoras. Este proyecto incluye funciones como agregar, modificar, eliminar, listar productos y exportar información a Excel, todo en un entorno responsivo y amigable para el usuario.

## Tecnologías Utilizadas

- **Lenguaje:** Java
- **Frameworks:** Spring Boot, Thymeleaf
- **Frontend:** HTML5, CSS3, Bootstrap 5
- **Base de Datos:** PostgreSQL
- **ORM:** Hibernate (JPA)
- **Herramientas de Desarrollo:**
  - IntelliJ IDEA Ultimate
  - SQL Workbench
- **Gestión de dependencias:** Maven

---

## Funcionalidades

1. **Gestión de Productos:**
   - Listar productos disponibles en una tabla.
   - Agregar nuevos productos con campos obligatorios como nombre, precio y descripción.
   - Modificar productos existentes, manteniendo campos no editables como el ID y la fecha de registro.
   - Eliminar productos con confirmación previa.

2. **Exportación:**
   - Descarga de la lista de productos en formato Excel con un solo clic.

3. **Validaciones:**
   - Validaciones dinámicas en el formulario de registro y modificación de productos.
   - Mensajes de error para campos vacíos o valores inválidos.

---

## Instalación y Configuración

### **Requisitos previos:**
1. Java 17 o superior instalado.
2. Mysql configurado con la base de datos `unison_almecen`.
3. Maven instalado o integrado en tu IDE.

### **Pasos de instalación:**

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/ManuelEnriquez14/Tumbados-Tech.git
   cd tumbados-tech
