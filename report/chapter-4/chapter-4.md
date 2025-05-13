# Capítulo IV: Product Design

## 4.1. Style Guidelines.

En esta seccion se establecen las bases con las que realizaremos y organizaremos la presentacion de nuestro proyecto. Se incluyen los General Style Guidelines y los Web Style Guidelines.

### 4.1.1. General Style Guidelines.

![ColorGuideLine](../../assets/chapter-4/StyleGuidelines/ColorGuidelines.png)

#### Colores cromáticos:

#FADADD (Rosa Pastel - Principal)
Este color es el corazón de nuestra identidad. El rosa pastel representa ternura, amor y sensibilidad, evocando la conexión entre madre y bebé. Se utiliza como color principal en fondos y componentes destacados para reforzar el tono afectivo y empático de la plataforma.

#F79AB0 (Rosa Vivo - Acento)
Un tono más fuerte y energético que complementa el rosa pastel. Este color se usa para botones principales y llamados a la acción, aportando dinamismo sin perder la suavidad emocional del entorno.


#FFE5DC (Melocotón Claro - Complementario)
Este tono cálido y sutil aparece en ilustraciones, etiquetas y elementos secundarios. Brinda variedad cromática sin alejarse de la armonía maternal del diseño.


#C24865 (Rosa Intenso – Énfasis emocional)
Este tono profundo y elegante aporta fuerza emocional al diseño. Se recomienda para alertas suaves, énfasis en citas o recordatorios importantes, sin ser agresivo. Mantiene la coherencia cromática con un contraste atractivo.

#F5ABE7 (Rosa Lila – Detalles decorativos)
Este tono dulce y lúdico se puede usar para acentos gráficos, ilustraciones o pequeños detalles decorativos que aportan fantasía y encanto visual. Es ideal para secciones informativas o elementos destinados a conectar emocionalmente con las usuarias.

#### Colores acromáticos:

#FFFFFF (Blanco Puro)
El fondo principal de la interfaz. Aporta limpieza visual, claridad y ligereza, permitiendo que el contenido respire y se mantenga fácilmente legible.

#F5F5F5 (Gris Claro)
Utilizado para secciones secundarias, tarjetas de información y áreas que requieren diferenciación suave sin perder la unidad visual.

#A0A0A0 (Gris Medio)
Presente en textos secundarios, íconos no activos y descripciones. Transmite neutralidad y equilibrio.

#4F4F4F (Gris Profundo)
Usado para títulos o elementos que requieren mayor jerarquía visual. Permite contraste sin recurrir al negro absoluto, manteniendo la estética cálida y accesible.

#### Tipografía:

Para este proyecto se han elegido tipografías sans serif con características redondeadas y amigables, que aseguren una lectura clara, suave y moderna. La elección responde al deseo de ofrecer un entorno emocionalmente cálido, sin sacrificar funcionalidad.
- Poppins – Sans Serif
    Moderna, versátil y altamente legible. Perfecta para encabezados y botones.
- Nunito – Sans Serif
Más redondeada, ideal para el cuerpo de texto. Refuerza la idea de suavidad y cercanía.
 
![FontGuideLine](../../assets/chapter-4/StyleGuidelines/FontsGuidelines-01.png)

Ambas fuentes trabajan en conjunto para equilibrar lo técnico con lo humano, lo clínico con lo emocional.

#### Ícono / logotipo:


![FontGuideLine](../../assets/chapter-4/StyleGuidelines/LogoHelpMom.png)



El logo representa una figura materna abrazando a un bebé, con líneas envolventes que forman un corazón. Este símbolo visual comunica de inmediato los valores fundamentales del proyecto: cuidado, protección, ternura y conexión emocional.
Forma: Curvas suaves que evocan suavidad y seguridad.


Significado: Unión del embarazo y la crianza temprana en un solo trazo.


Color: Rosa pastel sobre fondo claro, reforzando el ambiente tranquilo y amoroso.


Este logo no solo representa la identidad visual de la plataforma, sino también su propósito esencial: acompañar cada etapa del crecimiento del bebé desde el vientre materno hasta sus primeros meses de vida, con profesionalismo y cariño.


### 4.1.2. Web Style Guidelines.

En esta seccion mostramos la aplicacion de los lineamientos antes descritos en un avance de nuestra solucion web. 
En estas primeras pantallas demostramos el uso de los colores y tipografia propios de nuestro Branding. Como modo de navegacion principal hemos escogido una barra de navegacion ubicada en la izquierda donde se colocaran las funcionalidades usadas por el usuario.

![m1](../../assets/chapter-4/m3.png)

![m2](../../assets/chapter-4/m4.png)

## 4.2. Information Architecture.

En esta seccion mostramos las decisiones de Arquitectura de Informacion para organizar el contenido de nuestra aplicacion de tal manera que los usuarios puedan tener una experiencia eficiente. Se incluyen las secciones de Organization Systems, Labeling Systems, Navigation Systems y Searching Systems.

### 4.2.1. Organization Systems.
En este punto se mostraran los tipos de estructura visual que tendra cada grupo de informacion con respecto al segmento objetivo y al tipo de categorización que se usará

**Segmento objetivo 1: Mujeres en gestacion**

Al acceder a la plataforma HelpMom, las usuarias embarazadas pueden iniciar sesión, registrarse si aún no tienen una cuenta o recuperar su contraseña en caso de olvido. Una vez autenticadas, la página principal les presenta un panel personalizado con un menú de navegación que incluye opciones como "Mi Embarazo", "Salud", "Consejos", "Chat Médico", "Perfil" y "Ajustes".

En la sección "Mi Embarazo", las usuarias pueden visualizar el progreso de su gestación semana a semana, acceder a información relevante sobre el desarrollo del bebé, así como recibir recomendaciones personalizadas para cada etapa del embarazo, incluyendo nutrición, ejercicio y bienestar emocional.

En "Salud", se presenta un resumen de los signos vitales monitoreados por la pulsera inteligente (IoT), como frecuencia cardíaca, temperatura y calidad del sueño. También pueden registrar síntomas, cargar análisis médicos y recibir alertas si se detectan datos fuera de lo habitual.

La opción "Consejos" ofrece acceso a una biblioteca de artículos, videos y podcasts creados por especialistas en salud materno-infantil, con contenido actualizado sobre lactancia, preparación para el parto, salud mental y más.

En el módulo de "Chat Médico", las mujeres embarazadas pueden comunicarse en tiempo real con médicas y médicos disponibles 24/7, resolver dudas, compartir síntomas o recibir orientación inmediata en situaciones urgentes.

En el "Perfil", las usuarias pueden actualizar su información personal, incluyendo edad gestacional, datos de contacto, historial médico y preferencias de notificaciones.

En "Ajustes", pueden gestionar su cuenta, cambiar la contraseña, revisar los permisos de acceso a sus datos y configurar las alertas automáticas enviadas por la plataforma.

![OrganizationSystemMadres](../../assets/chapter-4/os-s1.jpg)

**Segmento objetivo 2: Medicos especialistas en atender el proceso de parto**

Al acceder a la plataforma del proyecto HelpMom para profesionales de la salud infantil y maternal, los usuarios (pediatras, médicos generales, enfermeras especializadas y otros profesionales de la salud) pueden iniciar sesión, registrarse si no tienen una cuenta previa, o recuperar su contraseña en caso de olvido. Una vez autenticados, la página principal presenta un panel de control personalizado con un menú de navegación que incluye opciones como "Pacientes", "Agenda", "Alertas", "Perfil" y "Ajustes".

![OrganizationSystemsDoctores](../../assets/chapter-4/os-s2.jpg)

### 4.2.2. Labeling Systems.

Al acceder a la plataforma HelpMom, los profesionales de la salud (pediatras, ginecólogos, obstetras y médicos generales) pueden iniciar sesión, registrarse si aún no tienen una cuenta, o recuperar su contraseña. Una vez dentro, se les presenta un panel de control adaptado a su rol, con un menú de navegación que incluye "Pacientes", "Agenda", "Alertas", "Perfil" y "Ajustes".

En la sección "Pacientes", los médicos pueden acceder a una lista de mujeres gestantes y recién nacidos bajo su atención. Al seleccionar un caso, se despliega un perfil detallado con el historial médico, resultados de exámenes, signos vitales recolectados en tiempo real por los dispositivos IoT, y un resumen del seguimiento clínico.

La subsección "Tratamientos en curso" permite consultar y registrar diagnósticos, recetas médicas, seguimiento de vacunas, intervenciones recomendadas y tareas médicas asignadas.

La opción "Agenda" ofrece una vista completa de las próximas citas médicas, controles prenatales o consultas pediátricas. Los médicos pueden agendar nuevas sesiones, modificar citas existentes y generar recordatorios automáticos para los pacientes.

En "Alertas", se centralizan las notificaciones generadas por el sistema en función del monitoreo de salud. Se destacan cambios anormales en los signos vitales, señales de alerta durante el embarazo y cualquier variación crítica detectada por los dispositivos conectados.

En el módulo "Perfil", los médicos pueden modificar su información profesional, como especialidad, horarios de atención, datos de contacto y credenciales verificadas.

En "Ajustes", es posible gestionar la seguridad de la cuenta, cambiar la contraseña, activar o desactivar notificaciones, y establecer preferencias en la visualización de datos clínicos.

**Navbar (Menú Principal):**

* "Inicio": Redirige a la página principal de la web.
* "Nosotros": Muestra información sobre la empresa, su misión y valores.
* "Productos": Describe los servicios o soluciones ofrecidas.
* "Membresía": Detalla los planes disponibles y sus beneficios.
* "FAQ": Responde a preguntas frecuentes de los usuarios.
* "Contacto": Proporciona acceso directo a los canales de comunicación.

**Secciones Principales:**

* "Inicio": Página de bienvenida con información destacada.
* "Nosotros": Historia, equipo y propósito de la empresa.
* "Productos": Características y ventajas de los servicios.
* "Membresía": Precios, planes y opciones de suscripción.
* "FAQ": Soluciones rápidas a dudas comunes.
* "Contacto": Formulario o datos para ponerse en contacto.

**Formulario de Contacto:**

* "Nombre": Campo para ingresar el nombre completo.
* "Email": Espacio para la dirección de correo.
* "Asunto": Breve descripción del motivo.
* "Mensaje": Área para detalles adicionales.
* "Enviar": Botón para submitir el formulario.

**Pie de Página:**

* "Nosotros": Enlace a la sección "Acerca de".
* "Productos": Acceso rápido a los servicios.
* "FAQ": Preguntas frecuentes.
* "Términos": Condiciones legales del sitio.
* "Privacidad": Política de protección de datos.
* "Contacto": Redirección a la sección correspondiente.

Cada etiqueta se diseñó para ser intuitiva, facilitando la navegación y mejorando la experiencia del usuario. La estructura prioriza claridad y coherencia, alineándose con los objetivos de la plataforma.

### 4.2.3. SEO Tags and Meta Tags

En esta seccion se mostraran los Meta Tags a usar dentro de nuestra landing page y web application.

<pre>
<code>
<title>HelpMom | Plataforma de control durante la maternidad</title>
meta name=»description» content=»HelpMom es una aplicacion dirigida para madres primerizas que necesitan contactar con su doctora para monitorear la salud de sus hijos.»>
meta name=”keywords” content= “baby, mother, doctor, application, baby health”>
meta name="author" content="Camila Reyes, Stephano Espinoza, Gabrel Mamani, Romina Maita, Gabriel Rivera">
</code>
</pre>

### 4.2.4. Searching Systems.

***1. ¿Qué se busca?***

  Tiene como objetivo proporcionar soluciones tecnológicas accesibles y eficientes para personas en situación de dependencia, tales como mujeres embarazadas, personas de la tercera edad y personas con movilidad reducida. La búsqueda está orientada a mejorar la calidad de vida de los usuarios, brindándoles autonomía, seguridad y acceso a ayuda personalizada mediante una aplicación web que sea intuitiva y fácil de usar.

***2. ¿Qué resultados se mostrarán?***

WebExpert busca ofrecer soluciones tecnológicas accesibles para mujeres embarazadas, con el objetivo de poder tener un buen control del bebé  través de plataformas intuitivas y fáciles de usar.

***3. Interfaz de búsqueda***

La interfaz de búsqueda está diseñada para ser accesible e intuitiva, permitiendo a los usuarios encontrar rápidamente lo que necesitan. Se incluirán sugerencias automáticas mientras se escribe y filtros para ordenar los resultados por categorías como necesidades, fecha o relevancia.

### 4.2.5. Navigation Systems.

Hemos decidido aplicar para un navigation system con un enfoque centrado en las tareas del usuario dentro de la aplicacion. A continuacion se muestra las tareas que seran accesibles desde la navegacion.

Dentro del perfil de madres:

- Health monitoring
- - Medication List
- Chat
- Appointments

Dentro del perfil de doctoras:

- Patient List
- - Add patient
  - About patient
  - Chat
  - Appointments
  - Health monitoring
  - Medication List

## 4.3. Landing Page UI Design.

En esta seccion se indicaran los bocetos iniciales de media y alta fidelidad de nuestra landing page usando las herramientas de Wireframes y Mock-ups. Para este boceto hemos considerado las elecciones de color conforme a nuestro Branding. Ademas, hemos considerado dentro de nuestra seccion de Productos las distintas funciones a las que se puede acceder segun los Organization y Navigation Systems.

### 4.3.1. Landing Page Wireframe.

![Landing page wireframe HomePage](../../assets/chapter-4/Landing_Page_wireframe.png)

### 4.3.2. Landing Page Mock-up.

El mockup de la landing page sigue un diseño adaptado tanto para Desktop como Mobile, utilizando una paleta de colores rosados suaves como base, reforzando la temática de maternidad y cuidado. Se incorporan toques de verde como color de contraste, aportando frescura y equilibrio visual.
![Landing page mock up HomePage](../../assets/chapter-4/Landing_Page_mockup.png)

## 4.4. Web Applications UX/UI Design.

En esta seccion se indicaran los bocetos iniciales de media y alta fidelidad de nuestra Web Application usando las herramientas de Wireframes y Mock-ups. Para este boceto hemos considerado las elecciones de color conforme a nuestro Branding. Ademas, hemos considerado como funcionalidades a las que puede acceder cada segmento la separacion indicada en los Organization y Navigation Systems.

### 4.4.1. Web Applications Wireframes.

Para los diseños de la aplicación hemos creado una pantalla para cada segmento objetivo.

Segmento madres:

![w1](../../assets/chapter-4/w1.jpeg)
![w2](../../assets/chapter-4/w2.jpeg)
![w3](../../assets/chapter-4/w3.jpeg)
![w4](../../assets/chapter-4/w4.jpeg)
![w5](../../assets/chapter-4/w5.jpeg)
![w6](../../assets/chapter-4/w6.jpeg)
![w7](../../assets/chapter-4/w7.jpeg)
![w8](../../assets/chapter-4/w8.jpeg)
![w9](../../assets/chapter-4/w9.jpeg)
![w10](../../assets/chapter-4/w10.jpeg)

Segmento Obstetras:

![w2_1](../../assets/chapter-4/w2_1.jpeg)
![w2_2](../../assets/chapter-4/w2_2.jpeg)
![w2_3](../../assets/chapter-4/w2_3.jpeg)
![w2_4](../../assets/chapter-4/w2_4.jpeg)
![w2_5](../../assets/chapter-4/w2_5.jpeg)
![w2_6](../../assets/chapter-4/w2_6.jpeg)

### 4.4.2. Web Applications Wireflow Diagrams.

Tomando en cuenta cada objetivo de cada segmento, se han creado los siguientes wireflows para cada uno de ellos.

User goal: Como madre quiero ver los signos vitales de mi bebe para comprobar su estado de salud.
![wflow1](../../assets/chapter-4/wflow1.png)

User goal: Como madre quiero ver el chat de mi doctora para comunicarme con ella.
![wflow2](../../assets/chapter-4/wflow2.png)

User goal: Como madre quiero ver el calendario de citas para asistir a las citas programadas.
![wflow3](../../assets/chapter-4/wflow3.png)

User goal: Como madre quiero ver la lista de medicamentos para comprar las recetas programadas.
![wflow4](../../assets/chapter-4/wflow4.png)

User goal: Como doctora quiero anadir el perfil de una paciente para comunicarme con ella.
![wflow21](../../assets/chapter-4/wflow5.png)

User goal: Como madre quiero ver el chat de mi paciente para comunicarme con ella.
![wflow22](../../assets/chapter-4/wflow2_1.png)

User goal: Como madre quiero ver los signos vitales del bebe de una paciente para monitorear su estado de salud.
![wflow23](../../assets/chapter-4/wflow2_2.png)

User goal: Como madre quiero anadir una cita al calendario para asistir a la cita programada.
![wflow24](../../assets/chapter-4/wflow2_3.png)

User goal: Como doctora quiero anadir una receta a la lista de medicamentos para informar a mi paciente.
![wflow25](../../assets/chapter-4/wflow2_4.png)

### 4.4.2. Web Applications Mock-ups.

Segmento madres:

![m2](../../assets/chapter-4/m2.png)
![m3](../../assets/chapter-4/m3.png)
![m4](../../assets/chapter-4/m4.png)
![m5](../../assets/chapter-4/m5.png)

Segmento Obstetras:

![m2_1](../../assets/chapter-4/m2_1.png)
![m2_2](../../assets/chapter-4/m2_2.png)
![m2_3](../../assets/chapter-4/m2_3.png)
![m2_4](../../assets/chapter-4/m2_4.png)

### 4.4.3. Web Applications User Flow Diagrams.

Tomando en cuenta cada objetivo de cada segmento, se han creado los siguientes User Flows para cada uno de ellos.

User goal: Como madre quiero ver los signos vitales de mi bebe para comprobar su estado de salud.
![uflow1](../../assets/chapter-4/uflow1.png)

User goal: Como madre quiero ver el chat de mi doctora para comunicarme con ella.
![uflow2](../../assets/chapter-4/uflow2.png)

User goal: Como madre quiero ver el calendario de citas para asistir a las citas programadas.
![uflow3](../../assets/chapter-4/uflow3.png)

User goal: Como madre quiero ver la lista de medicamentos para comprar las recetas programadas.
![uflow4](../../assets/chapter-4/uflow4.png)

User goal: Como doctora quiero anadir el perfil de una paciente para comunicarme con ella.
![uflow21](../../assets/chapter-4/uflow2_1.png)

User goal: Como madre quiero ver el chat de mi paciente para comunicarme con ella.
![uflow22](../../assets/chapter-4/uflow2_2.png)

User goal: Como madre quiero ver los signos vitales del bebe de una paciente para monitorear su estado de salud.
![uflow23](../../assets/chapter-4/uflow2_3.png)

User goal: Como madre quiero anadir una cita al calendario para asistir a la cita programada.
![uflow24](../../assets/chapter-4/uflow2_4.png)

User goal: Como doctora quiero anadir una receta a la lista de medicamentos para informar a mi paciente.
![uflow25](../../assets/chapter-4/uflow2_5.png)

## 4.5. Web Applications Prototyping.

A continuacion se demuestra una simulacion de la aplicacion web, donde se puede observar el flujo de la aplicacion y como se comporta cada una de las pantallas.
![Prototipo](../../assets/chapter-4/prototype.png)

Enlace donde se puede probar la interacción: https://www.figma.com/proto/CgL9dyaLJIA5rMKlIDgF4v/UX-UI-DESIGN-WEB?node-id=0-1&t=i5Oy6CKeg4crXJq0-1

## 4.6. Domain-Driven Software Architecture.
Los diagramas de arquitectura de software son herramientas clave para diseñar y comprender la estructura de un sistema. Al aplicar el enfoque de Domain Driven Design (DDD), estos diagramas nos permiten representar visualmente los distintos elementos del dominio, sus límites y las relaciones entre ellos, lo que facilita una mejor planificación y comunicación del diseño

### 4.6.1. Software Architecture Context Diagram.
En el diagrama de contexto se presenta cómo los usuarios, que incluyen a dueños de restaurantes y trabajadores, interactúan tanto con nuestro software. Además, se incluyen los sistemas externos que utilizaría KeepFresh.
![ContextDiagram.png](../../assets/ContextDiagram.png)

### 4.6.2. Software Architecture Container Diagrams.
A continuación, se presentará el diagrama de contenedores de nuestro sistema. Este artefacto corresponde al segundo nivel del modelo C4 y ofrece una descripción más detallada de los componentes técnicos, lo que proporciona una visión ampliada de la arquitectura del software
![ContainerDiagram.png](../../assets/ContainerDiagram.png)

### 4.6.3. Software Architecture Components Diagrams.
A continuación, se mostrarán los diagramas de componentes para cada Bounded Context, junto con detalles sobre las tecnologías utilizadas e implementaciones específica

Diagrama de componente de Baby Monitoring
![ComponentbabyMonitoringBC.png](../../assets/ComponentbabyMonitoringBC.png)

Diagrama de componente de Billing Subsciption
![ComponentbillingSubscriptionBC.png](../../assets/ComponentbillingSubscriptionBC.png)

Diagrama de componente de Managment
![ComponentcontentManagementBC.png](../../assets/ComponentcontentManagementBC.png)

Diagrama de componente de MedicalAssistance
![ComponentmedicalAssistanceBC.png](../../assets/ComponentmedicalAssistanceBC.png)

Diagrama de componente de Notification
![ComponentnotificationBC.png](../../assets/ComponentnotificationBC.png)

Diagrama de cmponente de User Managment
![ComponentuserManagementBC.png](../../assets/ComponentuserManagementBC.png)

## 4.7. Software Object-Oriented Design.

### 4.7.1. Class Diagrams.

![Class Diagrams](../../assets/chapter-4/cd2.png)

![Class Diagrams](../../assets/chapter-4/cd3.png)

![Class Diagrams](../../assets/chapter-4/cd4.png)

Link for LucidChart: https://lucid.app/lucidchart/30ba92cc-d4a4-4173-a345-d9df240369ba/edit?viewport_loc=355%2C-1059%2C5568%2C2702%2COMP.TpOaBXWe&invitationId=inv_162805fe-76e1-4eb0-9f55-a1369699a168

### 4.7.2. Class Dictionary.
* **Class Mother:** Representa a las madres en el sistema, con información como fecha de nacimiento y estado de embarazo.
* **Class MedicalDocument:** Representa los documentos médicos subidos al sistema, como informes o análisis.
* **Class Subscription:** Representa las suscripciones activas de los usuarios en la plataforma.
* **Class Baby:** Representa a los bebés registrados, con datos como nombre, fecha de nacimiento y etapa de desarrollo.
* **Class Membership:** Representa los tipos de membresía disponibles, con detalles como precio y nivel de acceso.
* **Class MedicalCheckUp:** Representa los controles médicos realizados al bebé, incluyendo peso, talla y observaciones.
* **Class MedicalHistory:** Representa el historial clínico del bebé, editable solo por doctores.
* **Class VitalSign:** Representa las señales vitales registradas (como temperatura o frecuencia cardíaca).
* **Class Vaccine:** Representa las vacunas aplicadas al bebé, con detalles como fecha y dosis.
* **Class Medicine:** Representa los medicamentos prescritos por el doctor.
* **Class Doctor:** Representa a los médicos en el sistema, con especialidad y número de colegiatura.
* **Class Message:** Representa los mensajes intercambiados entre usuarios (madres, doctores, etc.).

## 4.8. Database Design.

En esta seccion especificaremos la especificacion de la organizacion para la base de datos de nuestra solucion.

### 4.8.1. Database Diagram.
![Database Diagram](../../assets/chapter-4/Diagrama_DB.png)

Link for LucidChart: https://lucid.app/lucidchart/30ba92cc-d4a4-4173-a345-d9df240369ba/edit?viewport_loc=-3800%2C-3824%2C6488%2C3148%2C_OP.s7PTPVPg&invitationId=inv_162805fe-76e1-4eb0-9f55-a1369699a168
