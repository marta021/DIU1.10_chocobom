# DIU23
Prácticas Diseño Interfaces de Usuario 2022-23 (Tema: .... ) 

Grupo: DIU1_10Chocobom.  Curso: 2022/23 
Updated: 23/3/2023

Proyecto: 
>>> Decida el nombre corto de su propuesta en la práctica 2 

Descripción: 

>>> Describa la idea de su producto en la práctica 2 

Logotipo: 
>>> Opcionalmente si diseña un logotipo para su producto en la práctica 3 pongalo aqui

Miembros
 * :bust_in_silhouette:   Marta Rincón Otero     :octocat:     
 * :bust_in_silhouette:  Manuel Francisco Frías Lorite     :octocat:

----- 

# Proceso de Diseño 

## Paso 1. UX Desk Research & Analisis 

1.a Empathy Map
-----

Breve análisis entre lo que piensa, siente, dice y hace los tres diferentes perfiles planteados para nuestro ejemplo. 

![Método UX](img/Competitive.png) 1.b Competitive Analysis
-----

Comparación entre tres sitios webs diferentes cuya temática principal es el Tablao Flamenco.

![Método UX](img/Persona.png) 1.c Persona
-----

Hemos seleccionado dos personajes: Emma Kim, persona extranjera recién llegada a Granada que no conoce nada de la cultura y quiere aprender de ella, y por otro lado tenemos a Francisco José, amante del flamenco y la cultura española que le gustan mucho las actividades relacionadas con el flamenco.

![image](https://user-images.githubusercontent.com/78885190/227064349-bc0d6c0e-1fc2-483f-b8f6-a8c0b00a9546.png)

![image](https://user-images.githubusercontent.com/78885190/227064366-7302e54e-3d20-4473-ae4e-a119d7894a23.png)


![Método UX](img/JourneyMap.png) 1.d User Journey Map
----


Hemos escogido la opción de comprar entrada para acudir al Tablao Flamenco porque es necesario pasar por este proceso para ir a ver el espectáculo. Se trata de dos experiencias cuyo objetivo es el mismo pero que llegan desde inicios diferentes, en el caso de Emma, accede a la información a través de un folleto que se le es proporcionado mientras que Francisco José se entera usando las redes sociales.

![Método UX](img/usabilityReview.png) 1.e Usability Review
----

- Enlace al documento: [ P1/usability review - Hoja 1.pdf ](https://github.com/marta021/DIU1.10_chocobom/blob/a0b10b804eefbb28b408945b07f0b681750cf46f/P1/usability%20review%20-%20Hoja%201.pdf)
- Valoración final (numérica):  58.8445
- Comentario sobre la valoración:  Teniendo en cuenta las experiencias que nuestras dos personas pueden tener obtenemos una media de Moderate, siendo esta algo mejorable en aspectos como la búsqueda y la ayuda.

1.f Briefing
----
Durante esta practica hemos realizado una revisión de usabilidad acerca de la página web de un tablao flamenco mediante diversas herramientas.
Acerca de estas, pensamos que son una buena utilidad para poder realizar un análisis a fondo de cualquier página web.
Finalmente hemos concluido que la página web está relativamente bien diseñada para los diversos tipos de personas que pueden llegar a acceder a ella.

## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid / EMpathy map / POV
----
Comenta con un diagrama los aspectos más destacados a modo de conclusion de la práctica anterior,
![image](https://github.com/marta021/DIU1.10_chocobom/blob/master/P2/Feedback%20Capture%20Grid%20(Community).png)
![image](https://github.com/marta021/DIU1.10_chocobom/blob/master/P2/POV.png)

![Método UX](img/ScopeCanvas.png) 2.b ScopeCanvas
----
Propuesta de valor 
![image](https://github.com/marta021/DIU1.10_chocobom/blob/master/P2/scope_canvas_5_print_es.png)

![Método UX](img/Sitemap.png) 2.b Tasks analysis 
-----

 Definir "User Map" y "Task Flow" ... 
Hemos elegido hacer el User Task Matrix.
![image](https://github.com/marta021/DIU1.10_chocobom/blob/master/P2/User_Task%20Matrix.png)

![Método UX](img/labelling.png) 2.c IA: Sitemap + Labelling 
----
![image](https://github.com/marta021/DIU1.10_chocobom/blob/master/P2/sitemap_y_labelling.png)

![Método UX](img/Wireframes.png) 2.d Wireframes
-----
 Plantear el  diseño del layout para Web/movil (organización y simulación ) 

![image](https://github.com/marta021/DIU1.10_chocobom/blob/master/P2/sneakpeekit-4-browsers.png)


## Paso 3. Mi UX-Case Study (diseño)


![Método UX](img/moodboard.png) 3.a Moodboard
-----


>>> Plantear Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo
>>> Si diseña un logotipo, explique la herramienta utilizada y la resolución empleada. ¿Puede usar esta imagen como cabecera de Twitter, por ejemplo, o necesita otra?


![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page 

![Método UX](img/guidelines.png) 3.c Guidelines
----

>>> Estudio de Guidelines y Patrones IU a usar 
>>> Tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 

Para las guidelines nos ayudaremos de la página https://getbootstrap.com/docs/5.3/components/

Utilizaremos el logo del tablao (izquierda) y el componente Navbar (derecha) para el encabezado común a todas las páginas. 
En el Navbar incluiremos los respectivos menús de nuestra página ( Inicio / Galería / Espectáculos / Experiencias / Sobre Nosotros / Contacto ) además de un barra de búsqueda. Dentro de cada menú (menos el botón de Inicio) encontramos un menú desplegable (Dropdowns). Al final del Navbar encontramos otro Dropdown referido a los idiomas en los que podemos traducir la página.

En el aparrtado de Experiencias encontramos un submenú donde se habla de los menús de comida con los que se pueden acompañar el espectáculo. Para mostrar las fotos de estos menús de comida vamos a utilizar el componente de Carousel. De esta manera, las fotos se irán deslizando  mostrando todas las opciones de comida disponibles. Así mismo, en la misma página utilizaremos el componente de Cards para detallar un poco más cada uno de los menús con otra foto de referencia. El texto de el Card se encuentra a la derecha. Este estilo de página es similar para la página de los espectáculos aunque sin el Carousel.



![Método UX](img/mockup.png)  3.d Mockup
----

>>> Layout: Mockup / prototipo HTML  (que permita simular tareas con estilo de IU seleccionado)


![Método UX](img/caseStudy.png) 3.e ¿My UX-Case Study?
-----


>>> Publicar my Case Study en Github..
>>> Documente y resuma el diseño de su producto en forma de video de 90 segundos aprox


## Paso 4. Evaluación 


![Método UX](img/ABtesting.png) 4.a Caso asignado
----


>>> Breve descripción del caso asignado con enlace a  su repositorio Github


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Seleccione 4 personas ficticias. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Asigne dos a Caso A y 2 al caso B
 

| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


![Método UX](img/Survey.png). 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal 


![Método UX](img/usability-report.png) 4.d Usability Report
----

>> Añadir report de usabilidad para práctica B (la de los compañeros)



>>> Valoración personal 


>>> ## Paso 5. Evaluación de Accesibilidad  (no necesaria)


>>> ![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report 
>>>> ----

>>> Indica qué pretendes evaluar (de accesibilidad) sobre qué APP y qué resultados has obtenido 

>>> 5.a) Evaluación de la Accesibilidad (con simuladores o verificación de WACG) 
>>> 5.b) Uso de simuladores de accesibilidad 

>>> (uso de tabla de datos, indicar herramientas usadas) 

>>> 5.c Breve resumen del estudio de accesibilidad (de práctica 1) y puntos fuertes y de mejora de los criterios de accesibilidad de tu diseño propuesto en Práctica 4.



## Conclusión final / Valoración de las prácticas


>>> (90-150 palabras) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  













