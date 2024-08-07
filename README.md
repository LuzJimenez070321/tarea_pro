# TAREA_PRO

## PROBLEMA
Como estudiante del tecnologico, me cuesta trabajo mantener organizadas mis tareas y proyectos. Tengo que entregar mis tareas y proyectos en diferentes fechas, y me preocupa olvidar alguna fecha limite importante o no tener suficiente tiempo para completar todo. Nesecito una forma de organizar y priorizar mis tareas de manera efectiva para asegurarme de cumplir mis compromisos academicos.

## SOLUCION 
La solucion para el problema del estudiante que nesecita organizar y priorizar sus tareas y proyectos podria ser un gestor de tareas con las siguientes caracteristicas:

1-`CREACION DE TAREAS`: Permitir al usuario crear tareas y proyectos con informacion detallada , como:
  -Titulo y descripcion 
  -Fecha limite
  -Prioridad (alta, media, alta)
  -Categoria (trabajo, proyecto, estudia, etc.)

2-`ORGANIZACION DE TAREAS`: Popórcionar una forma de organizar las tareas de manera logica, como:
  -Listas de tareas por categoria 
  -calendario para fechas limite
  -Filtros para buscar tareas por prioridad, fecha, etc.

3-`NOTIFICACIONES Y RECORDATORIOS`: Enviar notificacion y recordatorios al usuario para:
  -Fechas limite proximas 
  -Tareas pendientes
  -Recordatorios personalizados

4-`SEGUIMIENTO DE PROCESO`: Permitir al usuarios ver su proceso y coompletar tareas, con:
  -Marca de tareas como completadas 
  -Historia de tareas completas
  -estadisticas de productividad 

Al impletar estas caracteristicas, el gestor de tareas podria ayudar al estudiante a:

👍 Organizar y priorizar sus tareas de manera efectiva

👍 Reeducir el estres y la ansiedad 

👍 Mejorar su productividad y cumplir con sus compromisos academicos 

## ACTORES 
Los actores en el gestor de tareas serian:

1.-`ESTUDIANTE`: El usuario principal que utiliza el gestor de tareas para organizar y priorizar sus tareas y proyectos.

2.-`ADMINISTRADOR`: Un usuario con permisos para configurar y personalizar el gestor de tareas, como:
   -Configurar categorias y prioridades 
   -Establecer notificaciones y recordatorios 
   -Ver estadisticas de productividad

3.-`DESARROLLADOR`: El equipo de desarrollador que crea y mantiene el gestor de tareas, incluyendo:
   -Diseñadores de interfaz de usuario 
   -Desarrolladores de backend y frontend
   -Comprobadores y depuradores 

4.-`SISTEMA`: El gestor de tareas en si mismo, que interactua con los actores para:
   -Almacenar y recuperar informacion de tareas
   -Enviar notificaciones y recordatorios 
   -Proporcionar estadisticas y visualizaciones 

5.-`DISPOSITIVOS`: Los dispositivos que los actores utilizan para acceder al gestor de tareas, como:
   -Computadoras
   -Telefonos moviles
   -Tabletas

6.-`CALENDARIO`: Un sistema de calendario externo que se integra con el gestor de tareas para:
   -Sincronizar fechas limite
   -mostrar eventos y tareas en un calendario

7.-`HERRAMIENTAS DE PRODUCTIVIDAD`: Otras herramientas y aplicaciones que se integran con el gestor de tareas para:
   -Compartir informacion
   -Automatizar tareas 
   -Mejorar la productividad

## HISTORIA DEL USUARIO 

*TITULO*: Como estudiante, quiero un gestor de tareas para organizar y priorizar mis tareas y proyectos de manera efectiva.

# HISTORIA DEL USUARIO 

1.`CREAR TAREAS`: Quiero poder crear tareas y proyectos con informacion detallada, como titulo, decripcion, fecha limite y prioridad, para tener una vision clara de mis responsabilidades 

2.`ORGANIZAR TAREAS`: Quiero poder organizar mis tareas mis tareas en categorias y prioridades para enfocarme en las mas importantes y urgentyes.

3.`NOTIFICACIONES Y RECORDATORIOS`: Quiero recibir notificaciones y recordatorios para fecha limite proximas y tareas pendientes para no olvidar compromisos importantes.

4.`SEGUIMIENTO DE PROCESO`: Quiero poder ver mi proceso y ompletar tareas para sentir un sentido de logro y motivacion 

5.`ACCESIBILIDAD`: Quiero poder acceder a mi gestor de tareas desde cualquier dispósitivo para estar siempre organizado
   
# DIAGRAMA DE CASOS DE USO

![alt text](<Captura de pantalla 2024-08-07 093444.png>)


# MAPA DE NAVEGACION 
Este mapa de navegacion muestra las diferentes pantallas y flujos de navegacion de la aplicacion, lo que ayuda a entender como se relaciona entre si y como se puede interactuar con la aplicacion.

![alt text](<Captura de pantalla 2024-08-07 095917.png>)

# PATRON DE ARQUTECTURA 

El patron de arqutectura para la aplicacion de gestor de tareas podria ser Modelo-Vista-Controlador, que se divide en tres capas:

1.`MODELO`: Representa la capa de presentacion, donde se almacenan y gestionan los datos de las tareas.

2.`VISTA`: Representa la capa de la presentacion, donde se muestra la interfaz del usuario.

3.`CONTROLADOR`: Representa la capa de control, donde se manejan las solicitudes del usuario y se interactua con el modelo y la vista.

![alt text](<Captura de pantalla 2024-08-07 105521.png>)