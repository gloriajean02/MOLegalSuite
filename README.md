# MOLegalSuite

# Morán&Ortíz Legal Suite
Repositorio destinado a la generación de documentación y seguimiento del desarrollo de la asignatura Proyecto Intermodular de DAW.

## 📅 Cronograma de la asignatura

| Fecha | Hito / Actividad |
| :--- | :--- |
| *12 de septiembre* | Presentación de Asignatura y Proyecto |
| *19 de septiembre* | Creación de Imagen Corporativa de la Empresa |
| *26 de septiembre* | Elaboración de Contrato de Prestación de Servicios y Recogida de Necesidades |
| *03 de octubre* | Definición de Requisitos Funcionales y No Funcionales, y Presentación |
| *10 de octubre* | Desarrollo de las Interfaces Gráficas |
| *17 de octubre* | Desarrollo de la Estructura de la Base de Datos |
| *24 de octubre* | Definición de Modelo Relacional de la Base de Datos |
| *31 de octubre* | Presentación de Interfaces y Base de Datos a la Empresa |
| *07 de noviembre* | Elección de Tecnologías a Utilizar |
| *14 de noviembre* | Estructuración Inicial de Documentación |
| *21 de noviembre* | Definición de Puntos de los Manuales de Usuario y Técnico |
| *05 de diciembre* | Desarrollo Inicial de Manuales de Usuario y Técnico |
| *12 de diciembre* | Opciones de Despliegue de Aplicativos |
| *19 de diciembre* | Pruebas de Despliegue en Entorno Local |
| *09 de enero* | Pruebas de Despliegue en Vercel |
| *16 de enero* | Fase de ajustes finales, corrección de errores (bugs) y optimización de rendimiento |
| *23 de enero* | Cierre definitivo de la documentación y manuales finales |
| *30 de enero* | Empaquetado final del software y preparación de la defensa del proyecto |

# Morán&Ortíz Legal Suite - Plataforma de Gestión Jurídica

## 📝 Resumen del Proyecto
Morán&Ortíz Legal Suite es una plataforma web diseñada para centralizar la gestión jurídica del despacho, permitiendo administrar abogados, clientes, procedimientos, juicios, notificaciones y firma digital. 
Su objetivo es transformar la gestión tradicional del despacho en una solución digital más organizada, segura y accesible, facilitando tanto el trabajo interno del equipo legal como la consulta de información por parte del cliente. 

## 👥 ¿A quién se dirige?
La aplicación está dirigida a despachos jurídicos que necesitan estructurar su operativa interna y mejorar la relación digital con sus clientes. 
Dentro del sistema se contemplan cuatro perfiles principales: superadministrador, administrador, abogados y clientes, cada uno con permisos y responsabilidades diferenciadas. 

## 💡 Justificación
La gestión jurídica suele depender de procesos fragmentados, seguimiento manual de expedientes y una comunicación poco centralizada con el cliente. 
Morán&Ortíz Legal Suite nace para resolver esa necesidad mediante una plataforma que unifica la gestión de procedimientos, juicios, documentación y notificaciones en un único entorno digital. 
El proyecto se justifica especialmente por la necesidad de ofrecer: 

* Un control centralizado de clientes, abogados y procedimientos. 
* Seguimiento estructurado del estado de cada procedimiento y de los juicios asociados. 
* Notificaciones automáticas al cliente cuando se produzcan cambios relevantes. 
* Gestión documental con soporte para firma digital por parte de abogados y clientes. 

---

## 🔐 Matriz de Roles y Permisos

| Acción / Funcionalidad | Superadministrador | Administrador | Abogado | Cliente |
| :--- | :---: | :---: | :---: | :---: |
| Inicio de sesión | ✓  | ✓  | ✓  | ✓ |
| Supervisión técnica y mantenimiento | ✓ |  |  |  |
| Alta y baja de abogados | ✓  | ✓  |  |  |
| Consulta de estadísticas generales | ✓ | ✓ |  |  |
| Registro de clientes |  |  | ✓  |  |
| Gestión de procedimientos (CRUD) |  |  | ✓ |  |
| Gestión de juicios |  |  | ✓  |  |
| Consulta del estado de procedimientos |  |  |  | ✓  |
| Recepción de notificaciones |  |  |  | ✓ |
| Firma digital de documentos |  |  | ✓ | ✓ |

---

## 🛠️ Stack Tecnológico

* **Lenguajes:** TypeScript/JavaScript, SQL (PostgreSQL), HTML5, CSS3 y JSON. 
* **Frameworks y librerías:** 
  * **Frontend:** React (SPA). 
  * **Estilos:** sistema visual propio inspirado en la identidad de la web corporativa del despacho. 
  * **Backend as a Service:** Supabase (Auth, DB, Storage). 
* **Entorno de desarrollo:** 
  * IDE: Visual Studio Code. 
  * Bundler: Vite. 
  * Control de versiones: Git y GitHub. 
* **Despliegue:** Vercel. 
* **Contenerización:** Docker. 
---

## 🧱 Entidades principales

* **Abogado:** identificado por sus datos personales y profesionales, con capacidad para gestionar procedimientos asociados a sus clientes. 
* **Cliente:** usuario final que accede a la plataforma para consultar el estado de sus procedimientos y recibir notificaciones. 
* **Procedimiento:** núcleo funcional del sistema, con estado, tipo, documentación y juicios asociados. 
* **Juicio:** registro vinculado a un procedimiento, con fecha, número de juzgado y posibles respuestas del juzgado. 

---

## 🚀 Objetivo del repositorio
Este repositorio reúne la documentación, evolución técnica y materiales del proyecto intermodular, incluyendo definición funcional, diseño, arquitectura, manual técnico, manual de usuario, despliegue y cierre del proyecto.

---

**Participante:** Gloria Curado García  
**Centro:** IES Albarregas
