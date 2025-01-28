# Aplicación de Auditorías

## Descripción
Esta aplicación de auditorías está diseñada para optimizar y digitalizar el proceso de auditorías dentro de una organización. Desarrollada utilizando **Power Apps**, **Power Automate** y **Dataverse**, permite gestionar auditorías de manera eficiente, desde la recolección de datos hasta la generación de reportes y el seguimiento de acciones correctivas.

## Tecnologías Utilizadas
- **Power Apps**: Para la creación de interfaces de usuario interactivas y adaptables.
- **Power Automate**: Para la automatización de flujos de trabajo, notificaciones y procesos asociados.
- **Dataverse**: Como base de datos centralizada para almacenar y gestionar la información.
- **Microsoft 365**: Integración con servicios como SharePoint, Outlook y Teams para colaboración.

## Funcionalidades Principales
1. **Gestión de Auditorías**:
   - Crear, editar y eliminar auditorías.
   - Asignar auditores y áreas responsables.
2. **Registro de Observaciones**:
   - Captura de hallazgos con fotografías y notas.
   - Clasificación por nivel de criticidad.
3. **Automatización de Flujos**:
   - Notificaciones automáticas para auditores y responsables.
   - Generación de tareas de seguimiento en Microsoft Teams o Planner.
4. **Reportes Dinámicos**:
   - Tableros de análisis con métricas clave.
   - Exportación de informes en formatos como Excel o PDF.
5. **Historial y Trazabilidad**:
   - Seguimiento de auditorías anteriores.
   - Registro de acciones correctivas implementadas.

## Arquitectura
La aplicación sigue un enfoque modular y escalable:

- **Power Apps**: Interfaz principal para la interacción del usuario.
- **Dataverse**: Base de datos que centraliza:
  - Auditorías.
  - Preguntas.
  - Acciones correctivas.
- **Power Automate**: Flujos que conectan:
  - Notificaciones por correo.
  - Sincronización de datos con SharePoint o Teams.

## Requisitos
Para desplegar y usar la aplicación, se necesitan los siguientes recursos:
- Licencia de Microsoft Power Platform (Power Apps y Power Automate).
- Permisos de administrador para configurar Dataverse.
- Acceso a Microsoft 365 para la integración con otros servicios.

## Instalación y Configuración
1. **Clonar o descargar el repositorio**.
2. **Importar el archivo Power Apps** en el entorno deseado.
3. **Configurar conexiones en Power Automate**:
   - Vincular los flujos con los conectores necesarios (Dataverse, Outlook, Teams, etc.).
4. **Cargar datos iniciales en Dataverse** (opcional).
5. **Probar la aplicación** y ajustar configuraciones según sea necesario.

## Uso
1. Accede a la aplicación desde Power Apps.
2. Inicia sesión con tu cuenta de Microsoft 365.
3. Navega por las secciones para:
   - Crear auditorías.
   - Crear preguntas.
   - Consultar reportes.

## Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

### Contacto
Si tienes dudas o sugerencias, puedes contactarnos en:
- **Correo**: [arielaparicio100@gmail.com](mailto:arielaparicio100@gmail.com)
- **LinkedIn**: [Linkedin](https://www.linkedin.com/in/arielaparicio/)

---
¡Gracias por usar nuestra aplicación de auditorías!
