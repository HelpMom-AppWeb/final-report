# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

Durante el desarrollo del mapa "To Be", se llevó a cabo una lluvia de ideas para generar propuestas de mejora. A partir de esta dinámica, se identificaron soluciones viables para abordar los retos y problemas detectados en el mapa "As Is". Luego, se definieron las etapas del proceso como columnas dentro del mapa "To Be", incorporando en cada una las mejoras sugeridas. Entre estas mejoras destacan la incorporación de un sistema de mensajería entre la obstetra y la paciente, un plan semanal para monitorear la evolución del embarazo, y una opción para que la gestante pueda compartir reportes de síntomas directamente con la obstetra.


**Segmento objetivo 1:** Madres:
![To Be scenario mapping Madres](../../assets/chapter-3/ToBeScenario_1.png)


**Segmento objetivo 2:** Doctores
![To Be scenario mapping Madres](../../assets/chapter-3/ToBeScenario_2.png)


## 3.2. User Stories.

Epics de la landing page:



| **Epic ID** | **Título**               | **Descripción**                                                                                                                                                                  | **Relacionado con (User Story ID)**                                                                                                                                                                                                                                         |
|-------------|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| EP01        | Información del Start Up  | <p>**Como** visitante</p><p>**Quiero** gestionar mi perfil</p><p>**Para** acceder a la aplicación de HelpMom</p>                                                                   | <p>- HU01 - Visualización de información de startup</p><p>- HU02 - Visualización de foto de startup</p>                                                                                                                                                                     |
| EP02        | Sobre el Producto         | <p>**Como** visitante</p><p>**Quiero** resguardar mis datos y privacidad</p><p>**Para** poder sentirme seguro al navegar en la aplicación de HelpMom</p>                           | <p>- HU03 - Visualización de información del producto</p><p>- HU04 - Visualización de foto de producto</p><p>- HU05 - Ingreso a la aplicación web</p>                                                                                                                       |
| EP03        | Planes y suscripciones    | <p>**Como** visitante</p><p>**Quiero** conocer los planes y membresías disponibles</p><p>**Para** poder elegir el que mejor se ajuste a mis necesidades dentro de HelpMom</p>                                 | <p>- HU06 - Visualización de información de planes</p>                                                                                                                                                                                                                       |
| EP04        | Preguntas frecuentes      | <p>**Como** visitante</p><p>**Quiero** acceder a una sección de preguntas frecuentes</p><p>**Para** resolver mis dudas rápidamente al usar HelpMom</p> | <p>- HU07 - Visualización de preguntas frecuentes</p><p>- HU08 - Visualización de imágenes de preguntas frecuentes</p>                                                                                                                                                        |
| EP05        | Contacto                  | <p>**Como** visitante</p><p>**Quiero** tener una interfaz intuitiva</p><p>**Para** navegar con comodidad dentro de la aplicación de HelpMom</p>                                    | <p>- HU09 – Ingreso de datos personales y consulta</p>                                                                                                                                                                                                                       |

Epics de la aplicación web:

| **Epic / Story ID** | **Título**                    | **Descripción**                                                                                                                                                             | **Relacionado con (User Story ID)**                                                                                                          |
|---------------------|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| EP06                | Ingreso de datos médicos      | **Como** doctor<br>**Quiero** ingresar información médica relevante<br>**Para** que se mantenga actualizado el historial clínico del embarazo y la salud del bebé.         | HU10 - Ingreso de recetas médicas<br>HU11 - Añadir instrucciones<br>HU12 - Historial de recetas                                             |
| EP07                | Gestionar datos personales    | **Como** usuaria de la plataforma<br>**Quiero** registrar y actualizar mis datos personales<br>**Para** asegurarme de que mi información esté siempre correcta y completa. | HU13 - Ingreso de nombre completo<br>HU14 - Ingreso de correo                                                                                  |
| EP08                | Comunicación personalizada    | **Como** madre gestante<br>**Quiero** comunicarme directamente con un profesional de salud<br>**Para** recibir orientación personalizada y resolver mis dudas.            | HU15 - Registro de certificado médico del doctor<br>HU16 - Registro de número telefónico de doctor<br>HU17 - Envío de mensajes            |
| EP09                | Soporte al usuario            | **Como** usuaria<br>**Quiero** tener acceso a soporte técnico y funcional<br>**Para** resolver problemas relacionados con el uso de la plataforma.                        | HU18 - Ingreso de consulta<br>HU19 - Respuesta del servicio técnico                                                                       |
| EP10                | Monitoreo de bebés            | **Como** madre gestante<br>**Quiero** registrar y visualizar información del desarrollo de mi bebé<br>**Para** llevar un seguimiento de su crecimiento y bienestar.       | HU20 - Seguimiento de signos vitales                                                                                                        |



| **Story ID** | **Título**                                | **Descripción**                                                                                                                                                                         | **Criterios de aceptación**                                                                                                                                                                                                                              | **Relacionado con (Epic ID)** |
|--------------|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| HU1          | Visualización de información de startup    | Como invitado, quiero visualizar la información de la startup para informarme sobre la empresa.                                                                                        | Escenario 1: Visualización correcta de la información. Dado que se ingresó texto, cuando se muestre la página, se mostrará correctamente. Escenario 2: Visualización incorrecta. Si no se cargó la información, se mostrará el aria-label.              | EP1                           |
| HU2          | Visualización de foto de startup           | Como invitado, quiero visualizar la foto de la startup para informarme sobre la empresa.                                                                                               | Escenario 1: Imagen válida, se muestra correctamente. Escenario 2: Imagen no cargada, se mostrará el aria-label.                                                                                                                                         | EP1                           |
| HU3          | Visualización de información de producto   | Como invitado, quiero visualizar la información del producto para informarme sobre lo que se ofrece.                                                                                   | Escenario 1: Información cargada, se muestra correctamente. Escenario 2: Información no cargada, se mostrará el aria-label.                                                                                                                              | EP2                           |
| HU4          | Visualización de foto de producto          | Como invitado, quiero visualizar la foto del producto para informarme sobre lo que se ofrece.                                                                                          | Escenario 1: Imagen válida, se muestra correctamente. Escenario 2: Imagen no cargada, se mostrará el aria-label.                                                                                                                                         | EP2                           |
| HU5          | Ingreso a la aplicación web                | Como invitado, quiero ingresar a la aplicación web para hacer uso del producto.                                                                                                        | Escenario 1: Enlace cargado correctamente, la aplicación se muestra correctamente. Escenario 2: Información no cargada, se mostrará el aria-label.                                                                                                      | EP2                           |
| HU6          | Visualización de información de planes     | Como invitado, quiero visualizar la información de los planes para informarme sobre la membresía.                                                                                      | Escenario 1: Información cargada, se muestra correctamente. Escenario 2: Información no cargada, se mostrará el aria-label.                                                                                                                              | EP3                           |
| HU7          | Visualización de preguntas frecuentes      | Como invitado, quiero visualizar las preguntas frecuentes y sus respuestas para solucionar dudas sobre el producto.                                                                    | Escenario 1: Información cargada correctamente. Escenario 2: Información no cargada, se mostrará el aria-label.                                                                                                                                          | EP4                           |
| HU8          | Visualización de imágenes de preguntas frecuentes | Como invitado, quiero visualizar las imágenes en las preguntas frecuentes para solucionar dudas sobre el producto.                                                               | Escenario 1: Imagen válida, se muestra correctamente. Escenario 2: Imagen no cargada, se mostrará el aria-label.                                                                                                                                         | EP4                           |
| HU9          | Ingreso de datos personales y consulta     | Como invitado, quiero ingresar mi nombre, correo y un mensaje para comunicarme con la startup.                                                                                         | Escenario 1: Texto válido en nombre, correo y mensaje → correo enviado correctamente. Escenario 2: Texto vacío en campos → se muestra error y se cancela el envío. Escenario 3: Correo inválido → se muestra error y se cancela el envío.                | EP5                           |
| HU10         | Ingreso de recetas médicas                 | Como doctor, quiero registrar la receta médica de mi paciente con la finalidad de ver a detalle los medicamentos que va tomando el paciente.                                          | Escenario 1: El doctor registra los medicamentos con validaciones. Al procesarse, el sistema muestra el medicamento registrado. Escenario 2: El doctor guarda la receta y el sistema muestra un mensaje de guardado exitoso.                             | EP06                          |
| HU11         | Añadir instrucciones a recetas             | Como doctor, quiero agregar instrucciones a las recetas con la finalidad de prevenir que el paciente cometa errores al seguir su medicación.                                          | Escenario 1: El doctor puede ingresar instrucciones detalladas. Escenario 2: El sistema valida que las instrucciones no estén vacías y las guarda correctamente.                                                                                         | EP06                          |
| HU12         | Historial de recetas                       | Como doctor, quiero visualizar los medicamentos registrados para hacer un mejor diagnóstico y mantener un historial de medicamentos del paciente.                                     | Escenario 1: El sistema muestra una lista ordenada de recetas anteriores. Escenario 2: Se puede acceder al historial desde la vista del paciente.                                                                                                       | EP06                          |
| HU13         | Ingreso de nombre completo                 | Como usuario, quiero registrar mi nombre para identificarme.                                                                                                                           | Escenario 1: El usuario puede ingresar su nombre. Escenario 2: El sistema valida que el nombre no esté vacío.                                                                                                                                            | EP07                          |
| HU14         | Ingreso de correo                          | Como usuario, quiero registrar mi correo para identificarme en la aplicación.                                                                                                          | Escenario 1: El usuario puede ingresar un correo válido. Escenario 2: El sistema valida el formato del correo antes de guardarlo.                                                                                                                        | EP07                          |
| HU15         | Registro de certificado médico del doctor  | Como doctor, quiero registrar mi certificado médico para validar mi identidad y generar confianza en mis pacientes.                                                                   | Escenario 1: El sistema permite subir el certificado en formato PDF o imagen. Escenario 2: Se muestra un mensaje de éxito al guardarse correctamente.                                                                                                     | EP08                          |
| HU16         | Registro de número telefónico del doctor   | Como madre, quiero registrar el número telefónico de una doctora para guardar su contacto.                                                                                            | Escenario 1: La usuaria puede ingresar un número válido. Escenario 2: El sistema guarda el número en el perfil de contacto de la doctora.                                                                                                                | EP08                          |
| HU17         | Envío de mensaje                           | Como madre, quiero enviar un mensaje a una doctora para comunicarme con ella.                                                                                                          | Escenario 1: La usuaria puede redactar y enviar el mensaje. Escenario 2: El sistema muestra confirmación de mensaje enviado.                                                                                                                             | EP08                          |
| HU18         | Ingreso de consulta                        | Como madre, quiero enviar un mensaje a soporte técnico para comunicar un problema con la aplicación.                                                                                  | Escenario 1: La usuaria puede ingresar una descripción del problema. Escenario 2: El sistema valida el formulario antes de enviarlo.                                                                                                                     | EP09                          |
| HU19         | Respuesta del servicio técnico             | Como madre, quiero recibir la respuesta del servicio técnico para solucionar un problema con la aplicación.                                                                           | Escenario 1: El sistema notifica cuando hay una respuesta disponible. Escenario 2: La usuaria puede ver el historial de respuestas.                                                                                                                      | EP09                          |
| HU20         | Seguimiento de signos vitales              | Como madre gestante o médico, quiero registrar y visualizar el historial de signos vitales para monitorear el bienestar fetal y materno y detectar anomalías a tiempo.               | Escenario 1: Se puede registrar presión arterial, frecuencia cardíaca y temperatura. Escenario 2: El sistema grafica la evolución de los signos vitales.                                                                                                | EP10                          |

### 3.2.1 Technical Stories

<table>
  <tr>
    <th>ID</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Criterios de Aceptación</th>
  </tr>

  <!-- Escenario 1: Registro de Usuarios -->
  <tr>
    <td>TS21</td>
    <td>Registro de Usuarios </td>
    <td>Como usuario no registrado, quiero crear una cuenta con mi email, contraseña y datos personales (nombre, fecha de nacimiento), para acceder a las funcionalidades de la aplicación.</td>
    <td>
      <strong>Scenario 1: Registro exitoso</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/register" está disponible.<br>
      <strong>When:</strong> Se envía un POST request con { "email": "paciente@example.com", "password": "Secure123", "name": "Juan Pérez", "birthdate": "1990-01-01" }.<br>
      <strong>Then:</strong> El sistema responde con status 201, crea el usuario en PostgreSQL y encripta la contraseña con bcrypt.<br><br>
      <strong>Scenario 2: Registro con email duplicado</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/register" y un email ya registrado ("paciente@example.com").<br>
      <strong>When:</strong> Se envía un POST request con el mismo email.<br>
      <strong>Then:</strong> El sistema responde con status 409 y el mensaje "Email already registered".
    </td>
  </tr>

  <!-- Escenario 2: Validación de Credenciales Médicas -->
  <tr>
    <td>TS22</td>
    <td>Validación de Credenciales Médicas</td>
    <td>Como médico, quiero subir mi certificado médico (PDF/IMG) para que el equipo administrativo valide mi identidad y me otorgue acceso a funcionalidades profesionales.</td>
    <td>
      <strong>Scenario 1: Subida exitosa de certificado</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/doctors/:id/certificate" acepta archivos (multipart/form-data).<br>
      <strong>When:</strong> Se envía un POST request con el archivo certificate.pdf y el doctorId válido.<br>
      <strong>Then:</strong> El sistema guarda el archivo en AWS S3, marca al médico como pending_verification y responde con status 202.<br><br>
      <strong>Scenario 2: Subida con formato inválido</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/doctors/:id/certificate".<br>
      <strong>When:</strong> Se envía un archivo certificate.txt (no soportado).<br>
      <strong>Then:</strong> El sistema responde con status 400 y el mensaje "Only PDF/JPEG/PNG allowed".
    </td>
  </tr>

  <!-- Escenario 3: Agendar Cita Médica -->
  <tr>
    <td>TS23</td>
    <td>Agendar Cita Médica</td>
    <td>Como paciente, quiero seleccionar una fecha/hora disponible en el calendario de un médico para agendar una cita.</td>
    <td>
      <strong>Scenario 1: Cita agendada correctamente</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/appointments" y un slot disponible para el médico doctorId=123.<br>
      <strong>When:</strong> Se envía un POST request con { "doctorId": 123, "patientId": 456, "date": "2025-05-20", "time": "10:00" }.<br>
      <strong>Then:</strong> El sistema crea la cita en PostgreSQL, envía un email de confirmación y responde con status 201.<br><br>
      <strong>Scenario 2: Slot ya ocupado</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/appointments" y un slot ya reservado.<br>
      <strong>When:</strong> Se intenta agendar la misma fecha/hora para el mismo médico.<br>
      <strong>Then:</strong> El sistema responde con status 409 y el mensaje "Time slot not available".
    </td>
  </tr>

  <!-- Escenario 4: Comunicación Encriptada (Chat) -->
  <tr>
    <td>TS24</td>
    <td>Comunicación Encriptada (Chat)</td>
    <td>Como paciente, quiero enviar mensajes encriptados a mi médico para discutir síntomas o resultados.</td>
    <td>
      <strong>Scenario 1: Mensaje enviado con éxito</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/chat/messages" usa WebSockets con TLS.<br>
      <strong>When:</strong> Se envía { "senderId": "patient123", "receiverId": "doctor456", "content": "Tengo dolor de cabeza" }.<br>
      <strong>Then:</strong> El sistema encripta el mensaje (AES-256), lo guarda en MongoDB y devuelve status 200.<br><br>
      <strong>Scenario 2: Intento de acceso no autorizado</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/chat/messages".<br>
      <strong>When:</strong> Un usuario sin JWT válido intenta enviar un mensaje.<br>
      <strong>Then:</strong> El sistema responde con status 401 y "Unauthorized".
    </td>
  </tr>

  <!-- Escenario 5: Monitoreo de Signos Vitales -->
  <tr>
    <td>TS25</td>
    <td>Monitoreo de Signos Vitales</td>
    <td>Como dispositivo wearable, quiero enviar datos de frecuencia cardíaca y presión arterial al servidor para monitoreo en tiempo real.</td>
    <td>
      <strong>Scenario 1: Datos válidos recibidos</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/patients/:id/vitals" está activo.<br>
      <strong>When:</strong> Se envía un POST request con { "patientId": "789", "heartRate": 75, "bloodPressure": "120/80", "timestamp": "2025-04-23T12:00:00Z" }.<br>
      <strong>Then:</strong> El sistema guarda los datos en Firebase Realtime DB y responde con status 200.<br><br>
      <strong>Scenario 2: Datos incompletos</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/patients/:id/vitals".<br>
      <strong>When:</strong> Se envía un request sin heartRate o bloodPressure.<br>
      <strong>Then:</strong> El sistema responde con status 400 y "Missing required fields".
    </td>
  </tr>

  <!-- Escenario 6: Generación de Recetas Digitales -->
  <tr>
    <td>TS26</td>
    <td>Generación de Recetas Digitales</td>
    <td>Como médico, quiero generar recetas con firma digital para que los pacientes las presenten en farmacias.</td>
    <td>
      <strong>Scenario 1: Receta firmada correctamente</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/prescriptions" y un JWT válido de médico.<br>
      <strong>When:</strong> Se envía { "patientId": "456", "medication": "Paracetamol", "dosage": "500mg" }.<br>
      <strong>Then:</strong> El sistema genera un PDF con firma RSA, lo guarda en S3 y devuelve la URL (status 201).<br><br>
      <strong>Scenario 2: Intento sin autenticación</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/prescriptions".<br>
      <strong>When:</strong> Un usuario no médico envía un request.<br>
      <strong>Then:</strong> El sistema responde con status 403 y "Forbidden: Doctor role required".
    </td>
  </tr>

  <!-- Escenario 7: Soporte Técnico (Creación de Tickets) -->
  <tr>
    <td>TS27</td>
    <td>Soporte Técnico (Creación de Tickets)</td>
    <td>Como usuario, quiero reportar problemas técnicos para recibir ayuda del equipo de soporte.</td>
    <td>
      <strong>Scenario 1: Ticket creado exitosamente</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/support/tickets".<br>
      <strong>When:</strong> Se envía { "userId": "123", "issue": "No puedo subir archivos", "priority": "high" }.<br>
      <strong>Then:</strong> El sistema crea un ticket en Zendesk, envía un email de confirmación y responde con ticketId (status 201).<br><br>
      <strong>Scenario 2: Falta descripción del problema</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/support/tickets".<br>
      <strong>When:</strong> Se envía un request sin el campo issue.<br>
      <strong>Then:</strong> El sistema responde con status 400 y "Issue description is required".
    </td>
  </tr>

  <!-- Escenario 8: Integración con Laboratorios (HL7/FHIR) -->
  <tr>
    <td>TS28</td>
    <td>Integración con Laboratorios (HL7/FHIR)</td>
    <td>Como administrador, quiero sincronizar resultados de exámenes de laboratorios externos automáticamente.</td>
    <td>
      <strong>Scenario 1: Resultados recibidos vía API HL7</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/labs/results" está configurado para parsear HL7.<br>
      <strong>When:</strong> El laboratorio envía un mensaje HL7 con patientId=456 y testType="blood".<br>
      <strong>Then:</strong> El sistema guarda los datos en PostgreSQL y notifica al paciente (status 200).<br><br>
      <strong>Scenario 2: Mensaje HL7 mal formado</strong><br>
      <strong>Given:</strong> El endpoint "/api/v1/labs/results".<br>
      <strong>When:</strong> Se recibe un mensaje HL7 inválido (sin patientId).<br>
      <strong>Then:</strong> El sistema responde con status 400 y "Invalid HL7 message".
    </td>
  </tr>

  <!-- Escenario 9: Recordatorios de Citas (Automáticos) -->
  <tr>
    <td>TS29</td>
    <td>Recordatorios de Citas (Automáticos)</td>
    <td>Como sistema, quiero enviar recordatorios de citas 24 horas antes para reducir inasistencias.</td>
    <td>
      <strong>Scenario 1: Notificación enviada por SMS</strong><br>
      <strong>Given:</strong> Un cron job ejecuta checkAppointments diariamente.<br>
      <strong>When:</strong> Encuentra una cita próxima (appointmentId=789).<br>
      <strong>Then:</strong> El sistema envía un SMS via Twilio al paciente y registra el envío en la DB.<br><br>
      <strong>Scenario 2: Paciente sin número de teléfono</strong><br>
      <strong>Given:</strong> El cron job checkAppointments.<br>
      <strong>When:</strong> La cita no tiene phoneNumber asociado.<br>
      <strong>Then:</strong> El sistema envía un email en su lugar y registra el fallo en logs.
    </td>
  </tr>

</table>

## 3.3. Impact Mapping.
Impact Mapping es una técnica visual que facilita la definición clara de los objetivos que queremos alcanzar y cómo estos se relacionan con nuestros usuarios. Esta herramienta nos permite mantener el enfoque y orientar nuestros esfuerzos hacia el cumplimiento del objetivo principal. Al finalizar el mapa, se identifican las funcionalidades y acciones necesarias para desarrollar el proyecto de forma eficiente.

Segmento objetivo #1: Mujer en gestacion

![madreImpactMaping.jpg](../../assets/chapter-3/madreImpactMaping.jpg)

Segmento objetivo #2: Obstetra

![docImpactMaping.jpg](../../assets/chapter-3/docImpactMaping.jpg)


## 3.4. Product Backlog.

| #  | User Story Id | Título                         | Descripción                                                                                     | Story Points | Epic Relacionado    |
|----|--------------|--------------------------------|-------------------------------------------------------------------------------------------------|--------------|---------------------|
| 1  | HU20         | Seguimiento de signos vitales  | Como madre/médico quiero registrar y visualizar signos vitales para monitorear bienestar fetal/materno. | 8 | Monitoreo de bebés  |
| 2  | HU10         | Ingreso de recetas médicas     | Como doctor quiero registrar recetas médicas para que los pacientes sigan tratamientos correctamente. | 5 | Ingreso de datos    |
| 3  | HU12         | Historial de recetas           | Como doctor quiero revisar historial de medicamentos recetados para mejorar diagnósticos.        | 5 | Ingreso de datos    |
| 4  | HU21         | Visualización de medicamentos  | Como madre quiero consultar medicamentos anteriores para reponer recetas.                      | 5 | Historial de citas  |
| 5  | HU23         | Gestión de citas (doctores)    | Como doctor quiero organizar las agendas de mis pacientes.                                      | 5 | Calendario de citas |
| 6  | HU-SUB       | Gestión de suscripción premium | Como usuario quiero actualizar mi plan premium para acceder a funciones exclusivas.            | 5 | Monetización        |
| 7  | HU18         | Ingreso de consulta            | Como madre quiero reportar problemas técnicos para obtener soporte inmediato.                   | 3 | Soporte al usuario  |
| 8  | HU17         | Envío de mensaje               | Como madre quiero comunicarme directamente con mi doctora para resolver dudas urgentes.         | 3 | Comunicación        |
| 9  | HU11         | Añadir instrucciones           | Como doctor quiero agregar notas a las recetas para evitar errores en la medicación.            | 3 | Ingreso de datos    |
| 10 | HU16         | Registro de número telefónico  | Como madre quiero guardar el contacto de mi doctora para emergencias.                          | 3 | Comunicación        |
| 11 | HU19         | Respuesta del servicio técnico | Como madre quiero recibir soluciones a mis reportes técnicos.                                  | 3 | Soporte al usuario  |
| 12 | HU15         | Registro de certificado médico | Como doctor quiero validar mi credencial profesional en la plataforma.                         | 3 | Comunicación        |
| 13 | HU24         | Gestión de citas (pacientes)   | Como paciente quiero ver mis citas programadas para no olvidarlas.                             | 3 | Calendario de citas |
| 14 | HU14         | Ingreso de correo              | Como usuario quiero registrar mi correo para recibir notificaciones importantes.               | 2 | Datos personales    |
| 15 | HU13         | Ingreso de nombre completo     | Como usuario quiero personalizar mi perfil con mi identidad real.                              | 2 | Datos personales    |
