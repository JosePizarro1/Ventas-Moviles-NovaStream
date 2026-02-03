# 📊 Sistema de Gestión de Ventas - NovaStream

## 📝 Descripción del Proyecto
Este repositorio contiene el esquema de control de versiones para el seguimiento de ventas de equipos móviles de la organización **NovaStream**. El objetivo es centralizar y auditar los reportes de ventas correspondientes al periodo **202401**, asegurando la integridad de los datos de ingresos, costos y márgenes por canal de venta.

## 🗂️ Estructura de los Datos
El archivo principal `reporte_ventas.csv` gestiona la siguiente información basada en la operación real:
* **Periodo:** Mes de registro (Ej. 202401).
* **Marca/Gama:** Clasificación de equipos (Samsung, Apple / Premium, High).
* **Finanzas:** Ingreso, Costo y Margen calculado.
* **Geografía:** Sedes de operación (Lima, Ucayali, San Martín).

## 🚀 Flujo de Trabajo (Git Flow)
Para mantener el orden, el equipo utiliza el siguiente esquema de ramas:
1. `main`: Contiene el reporte consolidado y validado.
2. `feature-canal-[nombre]`: Ramas temporales para cargar datos de canales específicos (Retail, Tiendas Propias).
3. `fix-errores`: Para correcciones inmediatas en fórmulas de márgenes.

## 🛠️ Comandos Básicos Utilizados
- `git checkout -b nombre-rama`: Crear una nueva rama de análisis.
- `git commit -m "mensaje"`: Registrar cambios en el reporte.
- `git tag -a v1.0`: Etiquetar cierres mensuales de ventas.

---
**Organización:** NovaStream Tech  
**Estado:** En Desarrollo - Q1 2024
