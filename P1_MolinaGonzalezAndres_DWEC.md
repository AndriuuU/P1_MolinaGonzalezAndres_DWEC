# Desarrollo web en entorno cliente

## Propuesta
---

### 1. La descripción de la idea de la aplicación y su propósito
El proyecto consiste en desarrollar una página web para la gestión de citas y la presentación de los servicios de una clínica dermatológica. El objetivo es facilitar a los clientes el acceso a la información sobre los diferentes servicios ofrecidos, sin necesidad de llamar. Actualmente, la clínica no cuenta con un sistema de citas en línea ni con una página web para brindar esta información. La idea es que los usuarios puedan gestionar sus citas de manera autónoma y consultar fácilmente los servicios disponibles.

### 2. Audiencia objetivo y la relevancia para dicho público
El público objetivo de este proyecto son los pacientes actuales y potenciales de la clínica dermatológica que buscan una manera más sencilla y eficiente de acceder a los servicios médicos. Este grupo incluye tanto a personas que desean gestionar sus citas de manera autónoma, como a quienes prefieren consultar los servicios antes de decidirse por una cita, todo ello sin necesidad de realizar llamadas telefónicas. La plataforma es relevante para este público porque les ofrece una experiencia cómoda, rápida y flexible para gestionar sus citas y acceder a información detallada sobre los tratamientos y servicios.

### 3. Análisis de mercado y propuesta de valor diferenciadora
**Análisis de mercado:**  
En el sector de las clínicas dermatológicas, la digitalización de servicios como la gestión de citas y la consulta en línea está en crecimiento, pero muchas clínicas aún no ofrecen estas soluciones. Los pacientes valoran cada vez más la conveniencia de gestionar sus citas y acceder a información de manera digital, lo que representa una oportunidad para implementar este proyecto.

**Propuesta de valor diferenciadora:**  
Este proyecto destaca por su simplicidad y personalización. Permitirá a los usuarios gestionar sus citas de manera flexible y consultar los servicios de la clínica de forma clara y accesible. A diferencia de plataformas genéricas, estará adaptada específicamente a las necesidades de la clínica, mejorando la experiencia del paciente y su satisfacción al evitar gestiones telefónicas.

### 4. Funcionalidades clave que ofrecerá la aplicación
1. **Gestión de citas en línea:** Programar, reprogramar y cancelar citas de manera fácil y rápida.
2. **Calendario de disponibilidad:** Muestra fechas y horas disponibles para citas.
3. **Recordatorios automáticos:** Envío de notificaciones por correo electrónico o SMS.
4. **Catálogo de servicios:** Consulta de servicios, descripciones, precios y beneficios.
5. **Perfil del usuario:** Gestión del historial de citas y datos personales.
6. **Consulta de médicos y especialistas:** Información sobre dermatólogos y sus especialidades.

### 5. Modelos de ejecución (c.e. 1a)
En el desarrollo web existen dos modelos de ejecución principales: 
- **Ejecución en cliente:** El código se ejecuta en el navegador del usuario, utilizando lenguajes como JavaScript. Este enfoque es ideal para crear aplicaciones interactivas y dinámicas.
- **Ejecución en servidor:** El código se ejecuta en el servidor antes de enviar los resultados al cliente. Se usa para manejar la lógica de negocio, procesamiento de datos y seguridad, utilizando lenguajes como Java con Spring Boot.

En nuestra aplicación, el frontend se ejecutará en el cliente y el backend en el servidor, ofreciendo así un equilibrio entre rendimiento y seguridad.

### 6. Lenguajes de programación web (c.e. 1c, 1d)
- **JavaScript:** Popular para el desarrollo del lado del cliente por su versatilidad y capacidad de crear experiencias interactivas. Se integra bien con frameworks como React.
- **TypeScript:** Aporta tipado estático a JavaScript, facilitando el mantenimiento y reduciendo errores, lo que es ideal para proyectos a gran escala.

### 7. Tecnologías a utilizar y su justificación
#### Backend: Java con Spring Boot
Un framework que facilita el desarrollo de aplicaciones backend robustas y escalables. Proporciona características como inyección de dependencias y seguridad.

#### Base de datos: MySQL o PostgreSQL
Bases de datos relacionales fiables, ideales para manejar datos estructurados como la gestión de citas y la información de los pacientes.

#### Frontend: HTML5, CSS3 y JavaScript (React o Thymeleaf)
- **React:** Para interfaces modernas y dinámicas, comunicándose con el backend vía API RESTful.
- **Thymeleaf:** Se integra con Spring Boot para un enfoque más tradicional.

#### Autenticación y seguridad: Spring Security con JWT
Ofrece mecanismos integrados para autenticación y autorización, con JWT permitiendo un enfoque sin estado.

#### Notificaciones: Twilio / SendGrid
Permiten la implementación de recordatorios por SMS y correos electrónicos.

#### Diseño responsivo: Bootstrap o Tailwind CSS
Frameworks que aseguran una experiencia de usuario fluida y adaptable a diferentes dispositivos.

#### Gestión de pagos (opcional): Stripe o PayPal
Integración fácil y segura para pagos en línea.

### 8. Evaluación de los mecanismos de integración de lenguajes de marcas con lenguajes de programación de clientes web (c.e. 1e)
HTML5 se integra con JavaScript para crear interfaces interactivas y dinámicas. Cuando usamos React, el HTML se representa de manera declarativa como componentes, permitiendo la integración directa con la lógica de JavaScript. En el caso de Thymeleaf, los lenguajes de marcas se integran en la estructura de plantillas que generan las páginas web.

### 9. Evaluación de herramientas de programación para clientes web (c.e. 1f)
#### Herramientas seleccionadas:
- **VSCode**: Editor de código ligero y extensible, con soporte para Java, JavaScript y React.
- **Node.js**: Ejecuta JavaScript en el entorno de desarrollo y facilita el uso de npm para gestionar paquetes y bibliotecas.
- **Postman**: Para probar APIs REST y asegurar la correcta comunicación entre el frontend y el backend.

Estas herramientas facilitan el desarrollo y permiten un flujo de trabajo eficiente.

### 10. Compatibilidad en navegadores (c.e. 1b)
JavaScript es compatible con la mayoría de los navegadores modernos (Chrome, Firefox, Safari, Edge). Sin embargo, hay diferencias en cómo interpretan ciertas características. React es compatible con los principales navegadores y ofrece polyfills para garantizar la compatibilidad en versiones más antiguas. Para asegurar la integración fluida de HTML y JavaScript, se seguirán buenas prácticas como evitar funciones obsoletas y utilizar herramientas como Babel para asegurar compatibilidad en navegadores menos recientes.

### Conclusión
El uso de Java con Spring Boot, junto con herramientas modernas como React o Thymeleaf, permitirá desarrollar una aplicación robusta, escalable y adaptable. La elección de estas tecnologías asegura un equilibrio entre rendimiento, seguridad y facilidad de mantenimiento, asegurando la capacidad de la aplicación para satisfacer las necesidades de la clínica dermatológica y mejorar la experiencia del paciente.
