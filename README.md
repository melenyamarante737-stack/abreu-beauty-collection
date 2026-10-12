# Abreu Beauty & Collection

Tienda en línea de productos de belleza y artículos de colección, desarrollada como proyecto de Ingeniería de Software.



##  Descripción del Proyecto
Plataforma web que permite a los clientes conocer los productos disponibles, consultar sus precios, buscar por categorías y realizar pedidos de manera sencilla desde cualquier dispositivo.

##  Problema que Resuelve
Actualmente, la comercialización de estos productos se realiza de forma presencial o por canales no estructurados, limitando el alcance a clientes cercanos y dificultando la consulta de disponibilidad y precios en cualquier momento. Este sistema centraliza la oferta en un espacio accesible.

## Funcionalidades Principales
- Catálogo de productos con imágenes, precios y descripciones
- Búsqueda y filtros por categoría y rango de precio
- Carrito de compras: agregar, modificar y eliminar productos
- Formulario y proceso de pedidos con datos de entrega
- Sección de administración para gestionar productos y existencias
- Diseño adaptable a teléfonos, tabletas y computadoras

## Arquitectura Seleccionada
Se adoptó una **arquitectura por 3 capas combinada con el estilo Cliente-Servidor**:

| Capa | Responsabilidad |
|---|---|
| **Capa de Presentación** | Interfaz de usuario: páginas, formularios, catálogo y mensajes |
| **Capa de Lógica de Negocio** | Reglas del sistema: validaciones, cálculos, control de permisos y flujos |
| **Capa de Datos** | Almacenamiento y consulta de productos, usuarios y pedidos |

Esta estructura permite que cada componente evolucione de forma independiente, facilita el mantenimiento y protege la información.

##  Organización: Frontend y Backend

###  Frontend (Lo que ve el usuario)
- **Responsabilidad:** Presentar la información de forma clara y atractiva; recibir acciones del usuario y mostrar respuestas.
- **Contiene:** Páginas HTML, estilos, menús, formularios y mensajes de interacción.
- **Funcionamiento:** Se ejecuta en el navegador del usuario. Envía solicitudes al backend y muestra la respuesta sin recargar toda la página.

### Backend (Lo que procesa el sistema)
- **Responsabilidad:** Procesar peticiones, aplicar reglas de negocio, validar datos y gestionar el acceso a la base de datos.
- **Contiene:** Lógica de pedidos, control de sesiones, seguridad y conexiones con la base de datos.
- **Funcionamiento:** Recibe las solicitudes del frontend, las valida, consulta o guarda información y devuelve una respuesta estructurada.

### Comunicación entre ambas partes
El frontend envía peticiones al backend (ej: *"dame la lista de productos"* o *"guarda este pedido"*). El backend procesa la solicitud, interactúa con la base de datos si es necesario y responde con la información solicitada o un mensaje de confirmación. Esta separación permite trabajar en cada parte de forma independiente y facilita las actualizaciones futuras.

## Metodología y Herramientas
- **Metodología:** Enfoque híbrido basado en Kanban
- **Gestión de tareas:** GitHub Projects
- **Control de versiones:** Git + GitHub
- **Modelado:** Visual Paradigm Online
- **Etapas del proyecto:** Requisitos → Diseño → Desarrollo → Documentación

## Estado Actual del Proyecto
- Análisis y especificación de requisitos completado
- Modelado UML y arquitectura definida
- Tablero de trabajo organizado con 10 tareas
-  Documentación técnica en proceso
- En fase de implementación de funcionalidades principales
-  Próximos pasos: finalizar carrito de compras, validar formularios, pruebas móviles y despliegue


## Registro de Cambios

| Nº | Fecha | Avance realizado |
|---|---|---|
| 1 | Septiembre 2026 | Definición de requisitos funcionales y no funcionales con criterios de aceptación |
| 2 | Septiembre 2026 | Elaboración de diagramas UML: Casos de Uso, Clases y Arquitectura |
| 3 | Octubre 2026 | Creación del tablero en GitHub Projects con distribución de tareas por estado |
| 4 | Octubre 2026 | Registro de incidencias y pendientes mediante GitHub Issues |
| 5 | Octubre 2026 | Actualización y ampliación del README con estructura técnica y estado del proyecto |

-

## Seguimiento de Incidencias (GitHub Issues)

| Nº | Título | Tipo | Estado |
|---|---|---|---|
| 1 | Implementar carrito de compras completo | Mejora | Pendiente |
| 2 | Validar formularios de inicio de sesión y registro | Corrección | En progreso |
| 3 | Realizar pruebas de responsividad en dispositivos móviles | Prueba | Pendiente |
| 4 | Crear formulario de pedido con validación de campos | Mejora | En revisión |


##  Autor
**Meleny Lissette Amarante Abreu**
Matrícula: 100075841
Proyecto realizado para la asignatura Ingeniería de Software I
Universidad Abierta Para Adultos — UAPA
