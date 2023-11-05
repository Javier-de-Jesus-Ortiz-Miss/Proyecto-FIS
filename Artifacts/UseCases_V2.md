## Casos de uso 

1. Registrar un nuevo usuario 
2. Ingresar a la cuenta de un usuario 
3. Ver e interactuar con videos subidos por otros usuarios
4. Hacer match con un usuario  deslizando a la derecha al ver un video en la página principal
5. Acceder al perfil de un usuario seleccionando la foto de perfil al ver un video en la página principal
6. Buscar un usuario 
7. Visualizar proyectos afines
8. Hacer match con un proyecto  deslizando hacia la derecha al visualizarlo en la página principal.
9. Acceder al perfil de un proyecto, seleccionando la foto de perfil al ver un video en la página principal
10. Buscar un proyecto
11. Crear un nuevo proyecto
12. Ver contenido del perfil personal
13. Eliminar contenido de mi perfil
14. Hacer contenido favorito para que se muestre a otros usuarios en la sección principal* 
15. Subir un nuevo contenido (Video)
16. Ver Informacion personal
17. Personalizar perfil personal
18. Ver Proyectos en los que el usuario participa
19. Editar proyectos en los que el usuario es el líder
20. Ver los contactos personales
21. Interactuar en un chat personal
22. interactuar un chat grupal
23. Editar un chat grupal
24. Aceptar una solicitud de match
25. aceptar solicitud de match a un proyecto
26. Dar match a un usuario
27. Dar match a un proyecto
28. Visualizar el contenido del perfil de un usuario
29. Visualizar la descripción de un usuario
30. Visualizar los proyectos de un usuario 
31. Visualizar los contactos  de un usuario


Casos de uso 

Registrar un nuevo usuario 
Ingresar a la cuenta de un usuario 

Ver e interactuar con videos subidos por otros usuarios
Hacer match con un usuario  deslizando a la derecha al ver un video en la página principal
Acceder al perfil de un usuario seleccionando la foto de perfil al ver un video en la página principal
Buscar un usuario 

Visualizar proyectos afines
hacer match con un proyecto  deslizando hacia la derecha al visualizarlo en la página principal.
acceder al perfil de un proyecto, seleccionando la foto de perfil al ver un video en la página principal
Buscar un proyecto
Crear un nuevo proyecto

Ver contenido del perfil personal
Eliminar contenido de mi perfil
Hacer contenido favorito para que se muestre a otros usuarios en la sección principal
Subir un nuevo contenido (Video)
Ver Informacion personal
Personalizar perfil personal
Ver Proyectos en los que el usuario participa
Editar proyectos en los que el usuario es el líder
Ver los contactos personales

Interactuar en un chat personal
interactuar un chat grupal
Editar un chat grupal
Aceptar una solicitud de match
aceptar solicitud de match a un proyecto

Dar match a un usuario
Dar match a un proyecto
Visualizar el contenido del perfil de un usuario
Visualizar la descripción de un usuario
Visualizar los proyectos de un usuario 
Visualizar los contactos  de un usuario




# Casos de Uso
## UC01 Registrar un Nuevo Usuario

|                     |                         |                     |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario crear una cuenta personal para acceder a todas las características de la aplicación. |
| **Precondición** | La cuenta del usuario no está registrada en la plataforma. |
| **Secuencia Normal** | 1. El usuario selecciona la opción “Sign Up” |
|| 2. El sistema abre la ventana de registro de nuevo usuario |
|| 3. El usuario completa los campos solicitados con su información personal (nombre de usuario, email,contraseña, fecha de nacimiento, género, país, ciudad) |
|| 4. El usuario selecciona “Continue” para enviar el formulario de registro. |
|| 5. El sistema valida la información dada y la registra. |
|| 6. El sistema abre la ventana de personalización de perfil|
|| 7. El usuario ingresa y selecciona la información que considere(Géneros, roles, instrumentos, pago, descripción, foto de perfil, etc.|
|| 8. El usuario selecciona “Submit” para enviar el formulario de registro. |
|| 9. El sistema valida la información dada y la registra. |
|| 10. El sistema inicia la sesión del usuario. |
| **Postcondición** | Se crea y personaliza la cuenta del usuario. |
| **Excepciones** | Paso 5 - Si la información ingresada es inválida, el sistema rechaza los datos ingresados |
|| 5.1. El sistema no considera válida la información dada en el cuestionario. |
|| 5.2. El sistema muestra un mensaje de error y señala la información invalida |
|| Paso 8 - Si la información ingresada es inválida, el sistema rechaza los datos ingresados |
|| 8.1. El sistema no considera válida la información dada en el cuestionario. | 
|| 8.2. El sistema muestra un mensaje de error y señala la información inválida |

## UC02 Ingresar a la cuenta de un usuario

|                  |                     |                  ||
| ---------------- | ------------------- | ---------------- |-|
| **Descripción**  | Este caso de uso permite a un usuario ingresar a su cuenta previamente registrada en la base de datos. |
| **Precondición** | El usuario se encuentra en la página de registro y tiene una cuenta registrada. |
| **Secuencia Normal** | 1. El usuario ingresa el correo y contraseña. |
|| 2. El usuario selecciona “Log In”
|| 3. El sistema valida los datos ingresados. |
|| 4. El sistema inicia la sesión del usuario. |
| **Postcondición** | Se inicia sesión en el perfil validado. |
| **Excepciones** | Paso 3 - El sistema no valida los datos ingresados
||3.1 El sistema rechaza los datos ingresados.|
||3.2 El sistema muestra un mensaje de error. |
||3.3 El sistema borra los datos ingresados. |

## UC03 Ver videos Subidos por Otros Usuarios

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario navegar y ver videos subidos por otros usuarios de la plataforma. |
| **Precondición** | El usuario ha iniciado sesión en su cuenta. |
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal en la sección de “Feed”. |
|| 2. El sistema reproduce automáticamente un video afín a los intereses del usuario. |
|| 3. El usuario podrá deslizar hacia abajo para ver otro video con características similares o hacia arriba para ver un video anterior|
| **Postcondición** | El usuario ve el video seleccionado. |
| **Excepciones** | - Si el video seleccionado no está disponible o ha sido eliminado, se muestra un mensaje de error. |

## UC04 Hacer match con un usuario  deslizando a la derecha al ver un video en la página principal

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario 1 acceder al perfil de un usuario 2 si está interesado luego de ver su video en la sección principal. | 
| **Precondición** | El usuario 1 ha iniciado sesión en su cuenta. El usuario 1 ha visto y muestra interés en el video del usuario 2.| 
| **Secuencia Normal** | 1. El usuario 1 visualiza el vídeo del usuario 2. |
| | 2. El usuario 1 desliza a la derecha  |
| | 3. El sistema manda automáticamente una notificación de match al usuario 2.|
| **Postcondición** | El usuario 2 recibió la notificación de match del usuario 1. |
| **Excepciones** | -  | 

## UC05 Acceder al Perfil del Usuario seleccionando la foto de perfil al ver un video en la página principal 

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario 1 acceder al perfil de un usuario 2 si está interesado luego de ver su video en la sección principal. | 
| **Precondición** | El usuario 1 ha iniciado sesión en su cuenta y ha visto el video del usuario 2 en la sección principal. | 
| **Secuencia Normal** | 1. El usuario 1 visualiza el vídeo del usuario 2. |
| | 2. El usuario 1 selecciona la foto de perfil del usuario 2 en la página principal |
| | 3. El sistema abre una ventana con el perfil del usuario 2 |
|| Para interactuar con el perfil véase UC26, UC27, UC28, UC29, UC30, UC31| 
| **Postcondición** | El usuario accede al perfil del usuario que subió el video. |
| **Excepciones** | - Ninguna | 

## UC06 Buscar un Usuario

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario buscar y encontrar otros usuarios en la plataforma. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal en la sección de “Feed”. |
|| 2. El usuario selecciona el icono de la lupa. |
|| 3. El sistema abre la ventana de búsqueda de usuarios 
|| 4. El usuario ingresa criterios de búsqueda, como instrumento, rol musicall, ubicación, etc. |
| | 5. El usuario ejecuta la búsqueda seleccionando “Search”. |
|| 6. El sistema registra los datos ingresados y los utiliza para la búsqueda | 
| | 7. El sistema muestra los resultados de la búsqueda. |
|| 8. El usuario selecciona el perfil del usuario que le interese |
|| 9. El sistema abre el perfil del usuario seleccionado |
|| Para interactuar con el perfil véase UC26, UC27, UC28, UC29, UC30, UC31| 
| **Postcondición** | Se muestra una lista de usuarios que coinciden con los criterios de búsqueda. |
| **Excepciones** | Paso 7 - Si no se encuentran usuarios que coincidan con los criterios de búsqueda, se muestra un mensaje informativo. |

## UC07 Visualizar Proyectos Afines

|                  |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver proyectos musicales que son afines a sus intereses o habilidades. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona la sección “Projects”. |
|| 2. El sistema mostrará un proyecto creado por otro usuario que coincida con los intereses o habilidades del usuario. |
|| 3. El usuario podrá deslizar hacia abajo para pasar al siguiente proyecto|
| **Postcondición** | El usuario visualiza proyectos afines a sus intereses y habilidades. |
| **Excepciones** | Paso 2 - Si no se encuentran proyectos afines a los intereses del usuario el sistema mostrará proyectos en la misma ciudad |

## UC08 Hacer match con un proyecto deslizando hacia la derecha al visualizarlo en la página principal
|                     |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario hacer match con un proyecto de otro usuario. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta.| 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal en la sección de “Projects”. |
|| 2. El usuario busca entre los proyectos principales uno con el que desee hacer match. |
|| 3. El usuario desliza de izquierda a derecha para realizar el match. |
|| 3. El sistema entrega el mensaje el mensaje “match request send succesfully. |
| **Postcondición** | El match aparece en la sección de chat. |
| **Excepciones** | Ninguna |
## UC09 Acceder al perfil de un proyecto, seleccionando la foto de perfil al ver un video en la página principal
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario visualizar los proyectos de otros usuarios desde la página principal de la aplicación. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta.| 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona la sección “Projects”. |
|| 2. El usuario selecciona la foto del proyecto o el nombre. |
|| 3. El sistema abre la ventana del proyecto seleccionado. |
|| Para unirse al proyecto visualizar el UC27|
| **Postcondición** | El usuario visualiza el perfil del proyecto. |
| **Excepciones** |Ninguna |

## UC10 Buscar un Proyecto

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario buscar y encontrar proyectos en la plataforma. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona la sección “Projects”. |
| | 2. El usuario selecciona el ícono de la lupa. |
| | 3. El sistema abre la ventana de búsqueda de proyectos | 
| | 4. El usuario ingresa criterios de búsqueda, como necesidades del proyecto, generos, pago por hora, proximidad, etc. |
| | 5. El usuario selecciona “Search”. |
|| 6. El sistema registra los datos ingresados y los utiliza para la búsqueda | 
| | 7. El sistema muestra los resultados de la búsqueda. |
| **Postcondición** | Se muestra una lista de proyectos que coinciden con los criterios de búsqueda. |
| **Excepciones** | Paso 6 - Si no se encuentran proyectos que coincidan con los criterios de búsqueda, se muestra un mensaje informativo y proyectos que cumplan con algunos de los filtros. |

## UC11 Crear un Nuevo Proyecto

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario crear un nuevo proyecto musical en la plataforma. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona la sección “Projects”. |
|| 2. El usuario selecciona la opción “New project” |
|| 3. El sistema abre la ventana de creación de un nuevo proyecto. |
|| 4. El usuario completa los campos solicitados para la creación del proyecto y selecciona “Continue”. |
|| 5. El sistema valida la información ingresada y la registra |
|| 6. El sistema presenta el nuevo proyecto, usuarios afines lo verán y creará el chat grupal entre los usuarios agregados. |  
| **Postcondición** | Se crea un nuevo proyecto musical en la plataforma, el usuario se convierte en el creador del proyecto y se crea el chat grupal. |
| **Excepciones** | Paso 4 - Si la información registrada es inválida, el sistema no concluirá la creación del proyecto |
|| 4.1 El sistema muestra un mensaje de error y señala la información inválida. |

## UC12 Ver contenido del perfil personal
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver el contenido de su propio perfil. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal en cualquiera de las dos secciones.|
|2. El usuario selecciona el icono del usuario ubicado en el menú inferior a la derecha. |
|3. El sistema abre la ventana del perfil personal en la sección de contenido.|
|4. El usuario visualiza su contenido. |
| **Postcondición** | El usuario puede ver su contenido en su perfil principal. |
| **Excepciones** | 2. Si el usuario no ha publicado ningún video el perfil saldrá vacío y el usuario podrá subir su contenido.|
## UC13 Eliminar contenido
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario eliminar el contenido de su propio perfil. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta..  | 
| **Secuencia Normal** | 1. El usuario se encuentra en la sección principal. |
||2. El usuario selecciona el icono del usuario ubicado en el menú inferior a la derecha. |
| |3. El sistema abre la ventana del perfil en la sección de contenido. |
|| 4. El usuario selecciona el icono del lápiz|
||5. El sistema abre la ventana de edición de contenido |
|| 6. El usuario selecciona el botón rojo en la esquina de los videos para eliminarlos. |
|| 4. Al presionar el botón rojo, el sistema eliminará el video del perfil del usuario. |
| **Postcondición** | Los videos que se hayan eliminado desaparecerán del perfil personal del usuario. |
| **Excepciones** | 2. Si no ha subido ningún video usuario, no saldrá la opción de eliminar contenido. |
## UC14 Hacer contenido favorito para que se muestre a otros usuarios en la sección principal
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario marcar como favorito el contenido de su propio perfil. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta.. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la sección principal. |
||2. El usuario selecciona el icono del usuario ubicado en el menú inferior a la derecha. |
| |3. El sistema abre la ventana del perfil en la sección de contenido. |
|| 4. El usuario selecciona el icono del lápiz|
||5. El sistema abre la ventana de edición de contenido |
|| 6. El usuario selecciona la estrella amarilla en la esquina de los videos para hacerlos favoritos. |
|| 7. Al seleccionar la estrella, el sistema establecerá el video como favorito y otros usuarios lo visualizarán en su feed. |
| **Postcondición** | Los videos seleccionados como favoritos saldrán en la sección principal de otros usuarios. |
| **Excepciones** | Si el usuario no ha subido ningún video, no le saldrá esta opción.|

## UC15 Subir un nuevo contenido 
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | En este caso de uso permite al usuario subir un nuevo contenido a su perfil | 
| **Precondición** |1. El usuario ha iniciado sesión en su cuenta | 
| **Secuencia Normal** | 1. El usuario se encuentra en la sección principal. |
||2. El usuario selecciona el icono del usuario ubicado en el menú inferior a la derecha. |
| |3. El sistema abre la ventana del perfil en la sección de contenido. |
|| 4. El usuario selecciona el icono del lápiz|
||5. El sistema abre la ventana de edición de contenido |
|| 6. El usuario selecciona el símbolo de más para añadir contenido. |
|| 7. Al seleccionar el símbolo de más, el sistema abre una ventana para seleccionar el contenido a subir. |
|| 8. El sistema sube el video seleccionado y se podrá ver en el perfil del usuario |
| **Postcondición** | El usuario ha subido su contenido nuevo  |
| **Excepciones** | Si el usuario no ha cargado el contenido no se subirá|

## UC16 Ver informacion personal
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver su información personal en su perfil | 
| **Precondición** |1. El usuario ha iniciado sesión en su cuenta | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona botón de perfil |
|| 2. El usuario selecciona la sección “About me” |
|| 3. En la sección "About me" del perfil, el usuario puede ver la siguiente información:
Ciudad: La ubicación de residencia del usuario.
Curriculum: Información sobre la experiencia y habilidades del usuario.
Instrumentos que toca: Lista de instrumentos musicales que el usuario sabe tocar.
Géneros musicales: Los géneros musicales que le interesan o en los que se especializa.
Costo: Información sobre las tarifas que el usuario cobra por sus servicios.
Matches: Número conexiones con otros usuarios en la aplicación.
 |
| **Postcondición** | El usuario ha visualizado su información personal en su perfil |
| **Excepciones** | Ninguna |
## UC17 Personalizar Perfil CAMBIAR ORDEN

|                  |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario personalizar su perfil. |
| **Precondición** | El usuario ha iniciado sesión en su cuenta. |
| **Secuencia Normal** | 1. El usuario selecciona el ícono de perfil. |
||2. El sistema abre la ventana de perfil personal |
|| 3. El usuario selecciona la sección “About me” |
|| 4. El usuario selecciona la opción “Edit profile” |
|| 5. El sistema abre la ventana de personalización de perfil |
|| 6. El usuario completa el formulario ingresando y seleccionando la información respectiva (Géneros, roles, instrumentos, pago, descripción, foto de perfil, etc.|
|| 7. El usuario selecciona “Submit” para enviar el formulario de registro. |
|| 8. El sistema valida la información ingresada y la registra. |
|| 9. El sistema regresa a la sección “About me” con los datos modificados. |
| **Postcondición** | El perfil del usuario se actualiza con la información registrada. |
| **Excepciones** | Paso 7 - Si la información ingresada es inválida, el sistema rechaza los datos ingresados |
|| 7.1. El sistema no considera válida la información dada en el cuestionario. | 
|| 7.2. El sistema muestra un mensaje de error y señala la información inválida |

## UC18 Ver Proyectos en los que el usuario participa
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver la lista de proyectos en los que está involucrado | 
| **Precondición** |1. El usuario ha iniciado sesión en su cuenta | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona botón de perfil |
|| 2. El usuario selecciona la sección “Projects” |
|| 3. El sistema muestra una lista de proyectos en los que el usuario está actualmente involucrado, incluyendo información relevante sobre cada proyecto, como nombre, descripción y estado.|
| **Postcondición** | El usuario ha visualizado sus proyectos involucrados  en su perfil |
| **Excepciones** | Si el usuario no ha iniciado sesión no se verá la información personal del usuario |
## UC19 Editar proyectos en los que el usuario es el líder
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario que es líder de un proyecto editar la información y configuración de dicho proyecto| 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y es el líder de un proyecto| 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona botón de perfil |
|| 2. El sistema abre la ventana del perfil del usuario |
|| 3. El usuario selecciona la sección “Projects” |
|| 4. El sistema abre la sección “Projects” |
|| 5. El usuario selecciona el botón “Edit project”|
||6. El usuario selecciona el ícono de lápiz en la parte superior derecha|
|| 7. El sistema abre la ventana para editar el proyecto |
||8. El usuario puede editar la información y configuración del proyecto |
|| 9. El usuario selecciona “Continue” |
|| 10. El sistema valida la información proporcionada |
|| 11. El sistema guarda y actualiza con los nuevos datos |
| **Postcondición** | El usuario ya ha editado exitosamente la información y configuración de uno de los proyectos en el cual es líder|
| **Excepciones** |Paso 6. Si el usuario no es líder del proyecto no podrá editarlo|
|| Paso 10. Si el sistema no valida la información no se guardaran los datos |
## UC 20 Ver los contactos personales
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver su lista de contactos personales |
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona botón de chat |
|| 2. El sistema abre la ventana de chat | 
|| 3. El usuario puede visualizar los chats y los contactos personales|  
| **Postcondición** | El usuario visualiza sus contactos personales| 
| **Excepciones** | El usuario visualizará de igual manera sus chats grupales| 
## UC21 - Interactuar en un chat personal
|  |  |
|-|-|
|**Descripción** | Este caso de uso permite a dos usuarios interactuar mediante un chat privado |
|**Precondición** | Ambos usuarios deben tener cuentas activas en el sistema y haber hecho match previamente |  
|**Secuencia Normal** | El usuario se encuentra en la pantalla principal y selecciona el icono de la sección de chat|
|| 2. El sistema abre la sección de chat|
||3. El usuario A accede a la lista de chats  |
||4.El usuario A selecciona el chat con el usuario B  |
||5.El sistema muestra la ventana de chat entre A y B  |
||6.Los usuarios intercambian mensajes de texto en tiempo real |
|**Postcondición** | Queda registrado el historial de conversación entre los usuarios A y B |
|**Excepciones** |  Paso 3. El usuario B ha bloqueado al usuario A, no se puede acceder al chat |

## UC22 - Interactuar en un chat grupal  
|  |  |
|-|-|
|**Descripción** | Permite la interacción entre varios usuarios en un chat grupal|
|**Precondición** | Los usuarios deben pertenecer al mismo proyecyo y tener cuentas activas en el sistema |
|**Secuencia Normal** | El usuario se encuentra en la pantalla principal y selecciona el icono de la sección de chat|
|| 2. El sistema abre la sección de chat|
||3. El usuario A accede a la lista de chats  |
||4.El usuario A selecciona el chat grupal con el que desee interactuar. |
||5.El sistema muestra la ventana de chat grupal  |
||6.Los usuarios intercambian mensajes de texto en tiempo real |
|**Postcondición**| El historial y contenido compartido quedan registrados en el grupo G|
|**Excepciones** |   |
## UC23-Editar un chat grupal
|   |   |  
| - | - |
| **Descripción**  | Este caso de uso permite a un usuario administrar un chat grupal, lo que incluye la capacidad de agregar o eliminar miembros, cambiar configuraciones, etc. |
| **Precondición** | El usuario ha iniciado sesión en su cuenta y es administrador del grupo. |
|**Secuencia Normal** | El usuario se encuentra en la pantalla principal y selecciona el icono de la sección de chat|
|| 2. El sistema abre la sección de chat|
||3. El usuario A accede a la lista de chats  |
||4.El usuario A selecciona el chat grupal que desea editar. |
||5.El sistema muestra la ventana de chat grupal  |
||6.El usuario selecciona el icono de engranaje en la parte superior a la derecha |
|| 7. El sistema abre el menú de configuración de grupo |
|| 8. El usuario puede editar el nombre del grupo y los integrantes |
| **Postcondición** | El chat grupal se administra según las acciones realizadas por el usuario. |
| **Excepciones** | 6. El usuario no puede acceder a las configuraciones del grupo debido a que no es administrador del grupo |
## UC24 - Aceptar una solicitud de match  
|  |  |
|-|-|
|**Descripción** | Permite a un usuario aceptar una solicitud de match con otro usuario |
|**Precondición** | El usuario debe haber iniciado sesión y tener una solicitud de match pendiente de otro usuario |
|**Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona la sección de chat |
|| 2. El sistema abre la sección de chat|
|| 3. El usuario A selecciona una solicitud de match |
|| 4. El sistema abre el perfil del usuario B |
|| 5. El usuario A selecciona “Accept match” |
|| 6. El sistema registra el match entre los usuarios A y B |
|| 7. El sistema regresa a la sección de chat y se habilita el chat entre el usuario A y B|
| **Postcondición** | Queda registrado el match entre los usuarios A y B, permitiendo la interacción por chat |
| **Excepciones** |   Paso 3. El usuario B eliminó la solicitud de match|
|| Paso 5. El usuario A niega la solicitud del usuario B|

## UC25 - Aceptar solicitud de match a un proyecto
|  |  |
|-|-|
|**Descripción** | Permite a un usuario aceptar una solicitud de otro usuario para unirse a su proyecto publicado |
|**Precondición** | El usuario debe haber iniciado sesión y tener publicado un proyecto con solicitudes pendientes de match |
|**Secuencia Normal** | 1. El usuario se encuentra en la página principal |
|| 2. El usuario selecciona el icono de chat para abrir la sección de chat |
|| 3. El sistema abre la sección de chat, donde llegan las notificaciones de match |
|| 4. El sistema selecciona la notificación de match de proyecto|
|| 5. El sistema abre el perfil del usuario que quiere unirse al proyecto  |
||6. El usuario selecciona la opción “Integrate to proyect” | 
|| 7. El sistema registra el match y añade al usuario que creó el match al proyecto|
|| 8. El sistema regresa a la sección de chat|
|**Postcondición** | El usuario B queda registrado como miembro del proyecto P |
|**Excepciones** | 6. El dueño del grupo no quiere añadir al usuario |
## UC26 Dar Match a un Usuario 

|                  |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario indicar interés en otro usuario, lo que puede llevar a un "match" si ambos usuarios están interesados mutuamente. | 
| **Precondición** | El usuario 1 ha iniciado sesión en su cuenta y se encuentra en el perfil del usuario 2. | 
| **Secuencia Normal** | 1. El usuario 1 visualiza el perfil del usuario 2. |
|| 2. El usuario 1 selecciona la opción de "Match". |
|| 3. El sistema notifica al usuario 2 en la sección de Chat. |
| **Postcondición** | El sistema ha notificado al usuario 2 el interés del usuario 1. |
| **Excepciones** | - Ninguna |

## UC27 Dar match a un proyecto
| | |
|--|--|
| **Descripción**  | Este caso de uso permite a un usuario indicar interés en un proyecto, lo que puede llevar a ser parte del proyecto si es aceptado. | 
| **Precondición** | El usuario 1 ha iniciado sesión en su cuenta y se encuentra en la pantalla del proyecto. | 
| **Secuencia Normal** | 1. El usuario 1 visualiza la pantalla del proyecto. |
|| 2. El usuario 1 selecciona la opción de "I want to join". |
|| 3. El sistema notifica al líder del proyecto en la sección de Chat. |
| **Postcondición** | El sistema ha notificado al líder del proyecto el interés del usuario 1. |
| **Excepciones** | - Ninguna |

## UC28 Visualizar el contenido del perfil de un usuario

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver los videos musicales que otro usuario ha subido a su cuenta en la plataforma. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y está viendo el perfil de otro usuario. | 
| **Secuencia Normal** | 1. El usuario 1 accede al perfil del usuario 2. |
| | 2. El sistema muestra el perfil del usuario 2 y por defecto muestra la sección “contenido”, donde se muestran los videos musicales subidos por el usuario 2. |
| | 3. El usuario 1 ve los videos musicales subidos por el usuario 2. |
| **Postcondición** | El usuario visualiza los videos musicales del perfil del otro usuario. |
| **Excepciones** | Paso 3 - Si no hay videos disponibles en el perfil del otro usuario, el sistema muestra un mensaje informativo. |

## UC29 Visualizar la descripción de un usuario

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver la descripción y detalles personales de otro usuario en su perfil. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y está viendo el perfil de otro usuario. | 
| **Secuencia Normal** | 1. El usuario accede al perfil de otro usuario. |
| | 2. El usuario selecciona la sección de “Sobre mí” en el perfil del otro usuario. |
|| 3. El sistema abre la sección de descripción del perfil. |
| | 3. El usuario lee la información proporcionada por el otro usuario. |
| **Postcondición** | El usuario visualiza información personal del perfil del otro usuario. |
| **Excepciones** | Ninguna |

## UC30 Visualizar los proyectos de un usuario

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver los proyectos musicales abiertos a recibir solicitudes que otro usuario ha creado. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y está viendo el perfil de otro usuario. | 
| **Secuencia Normal** | 1. El usuario accede al perfil de otro usuario. |
| | 2. El usuario selecciona la sección de “Proyectos” en el perfil del otro usuario. |
| | 3. El sistema muestra una lista de proyectos que el usuario 2 tiene disponibilidad para otros usuarios |
| | 4. El usuario selecciona un proyecto de la lista de proyectos disponibles del usuario 2. |
|| 5. El sistema abre la pantalla del proyecto |
| | 6. El usuario visualiza la descripción y video de presentación del proyecto, los miembros con los que cuenta y los roles que necesita para el proyecto. |
| **Postcondición** | El usuario visualiza los proyectos musicales del perfil del otro usuario. |
| **Excepciones** | Paso 3 - Si el usuario 2 no cuenta con proyectos creados, el sistema muestra un mensaje informativo. |

## UC31 Visualizar los contactos de un usuario

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario 1 ver la lista de “Matches” de el usuario 2 en la plataforma. | 
| **Precondición** | El usuario 1 ha iniciado sesión en su cuenta y está viendo el perfil del usuario 2. | 
| **Secuencia Normal** | 1. El usuario 1 accede al perfil de otro usuario. |
| | 2. El usuario 1 selecciona el área de “Matches” en el perfil del usuario 2. |
|| 3. El sistema abre la ventana de los matches del usuario 2 |
| | 3. El usuario ve la lista de “Matches” del usuario 2. |
| **Postcondición** | El usuario 1 visualiza la lista de “Matches” del perfil del usuario 2. |
| **Excepciones** | Paso 3 - Si el otro usuario no tiene “Matches” en su perfil, el sistema no muestra resultados. |


# Especificación de Casos de Uso

## UC01 Registrar un Nuevo Usuario

|                     |                         |                     |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario crear una cuenta personal para acceder a todas las características de la aplicación. |
| **Precondición** | La cuenta del usuario no está registrada en la plataforma. |
| **Secuencia Normal** | 1. El usuario selecciona la opción “Sign Up” |
|| 2. El sistema abre la ventana de registro de nuevo usuario |
|| 3. El usuario completa los campos solicitados con su información personal (nombre de usuario, email,contraseña, fecha de nacimiento, género, país, ciudad) |
|| 4. El usuario selecciona “Continue” para enviar el formulario de registro. |
|| 5. El sistema valida la información dada y la registra. |
|| 6. El sistema abre la ventana de personalización de perfil|
|| 7. El usuario ingresa y selecciona la información que considere(Géneros, roles, instrumentos, pago, descripción, foto de perfil, etc.|
|| 8. El usuario selecciona “Submit” para enviar el formulario de registro. |
|| 9. El sistema valida la información dada y la registra. |
|| 10. El sistema inicia la sesión del usuario. |
| **Postcondición** | Se crea y personaliza la cuenta del usuario. |
| **Excepciones** | Paso 5 - Si la información ingresada es inválida, el sistema rechaza los datos ingresados |
|| 5.1. El sistema no considera válida la información dada en el cuestionario. |
|| 5.2. El sistema muestra un mensaje de error y señala la información invalida |
|| Paso 8 - Si la información ingresada es inválida, el sistema rechaza los datos ingresados |
|| 8.1. El sistema no considera válida la información dada en el cuestionario. | 
|| 8.2. El sistema muestra un mensaje de error y señala la información inválida |

## UC02 Ingresar a la cuenta de un usuario

|                  |                     |                  ||
| ---------------- | ------------------- | ---------------- |-|
| **Descripción**  | Este caso de uso permite a un usuario ingresar a su cuenta previamente registrada en la base de datos. |
| **Precondición** | El usuario se encuentra en la página de registro y tiene una cuenta registrada. |
| **Secuencia Normal** | 1. El usuario ingresa el correo y contraseña. |
|| 2. El usuario selecciona “Log In”
|| 3. El sistema valida los datos ingresados. |
|| 4. El sistema inicia la sesión del usuario. |
| **Postcondición** | Se inicia sesión en el perfil validado. |
| **Excepciones** | Paso 3 - El sistema no valida los datos ingresados
||3.1 El sistema rechaza los datos ingresados.|
||3.2 El sistema muestra un mensaje de error. |
||3.3 El sistema borra los datos ingresados. |

## UC03 Ver videos Subidos por Otros Usuarios

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario navegar y ver videos subidos por otros usuarios de la plataforma. |
| **Precondición** | El usuario ha iniciado sesión en su cuenta. |
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal en la sección de “Feed”. |
|| 2. El sistema reproduce automáticamente un video afín a los intereses del usuario. |
|| 3. El usuario podrá deslizar hacia abajo para ver otro video con características similares o hacia arriba para ver un video anterior|
| **Postcondición** | El usuario ve el video seleccionado. |
| **Excepciones** | - Si el video seleccionado no está disponible o ha sido eliminado, se muestra un mensaje de error. |

## UC04 Hacer match con un usuario  deslizando a la derecha al ver un video en la página principal

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario 1 acceder al perfil de un usuario 2 si está interesado luego de ver su video en la sección principal. | 
| **Precondición** | El usuario 1 ha iniciado sesión en su cuenta. El usuario 1 ha visto y muestra interés en el video del usuario 2.| 
| **Secuencia Normal** | 1. El usuario 1 visualiza el vídeo del usuario 2. |
| | 2. El usuario 1 desliza a la derecha  |
| | 3. El sistema manda automáticamente una notificación de match al usuario 2.|
| **Postcondición** | El usuario 2 recibió la notificación de match del usuario 1. |
| **Excepciones** | -  | 

## UC05 Acceder al Perfil del Usuario seleccionando la foto de perfil al ver un video en la página principal 

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario 1 acceder al perfil de un usuario 2 si está interesado luego de ver su video en la sección principal. | 
| **Precondición** | El usuario 1 ha iniciado sesión en su cuenta y ha visto el video del usuario 2 en la sección principal. | 
| **Secuencia Normal** | 1. El usuario 1 visualiza el vídeo del usuario 2. |
| | 2. El usuario 1 selecciona la foto de perfil del usuario 2 en la página principal |
| | 3. El sistema abre una ventana con el perfil del usuario 2 |
|| Para interactuar con el perfil véase UC26, UC27, UC28, UC29, UC30, UC31| 
| **Postcondición** | El usuario accede al perfil del usuario que subió el video. |
| **Excepciones** | - Ninguna | 

## UC06 Buscar un Usuario

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario buscar y encontrar otros usuarios en la plataforma. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal en la sección de “Feed”. |
|| 2. El usuario selecciona el icono de la lupa. |
|| 3. El sistema abre la ventana de búsqueda de usuarios 
|| 4. El usuario ingresa criterios de búsqueda, como instrumento, rol musicall, ubicación, etc. |
| | 5. El usuario ejecuta la búsqueda seleccionando “Search”. |
|| 6. El sistema registra los datos ingresados y los utiliza para la búsqueda | 
| | 7. El sistema muestra los resultados de la búsqueda. |
|| 8. El usuario selecciona el perfil del usuario que le interese |
|| 9. El sistema abre el perfil del usuario seleccionado |
|| Para interactuar con el perfil véase UC26, UC27, UC28, UC29, UC30, UC31| 
| **Postcondición** | Se muestra una lista de usuarios que coinciden con los criterios de búsqueda. |
| **Excepciones** | Paso 7 - Si no se encuentran usuarios que coincidan con los criterios de búsqueda, se muestra un mensaje informativo. |

## UC07 Visualizar Proyectos Afines

|                  |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver proyectos musicales que son afines a sus intereses o habilidades. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona la sección “Projects”. |
|| 2. El sistema mostrará un proyecto creado por otro usuario que coincida con los intereses o habilidades del usuario. |
|| 3. El usuario podrá deslizar hacia abajo para pasar al siguiente proyecto|
| **Postcondición** | El usuario visualiza proyectos afines a sus intereses y habilidades. |
| **Excepciones** | Paso 2 - Si no se encuentran proyectos afines a los intereses del usuario el sistema mostrará proyectos en la misma ciudad |

## UC08 Hacer match con un proyecto deslizando hacia la derecha al visualizarlo en la página principal
|                     |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario hacer match con un proyecto de otro usuario. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta.| 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal en la sección de “Projects”. |
|| 2. El usuario busca entre los proyectos principales uno con el que desee hacer match. |
|| 3. El usuario desliza de izquierda a derecha para realizar el match. |
|| 3. El sistema entrega el mensaje el mensaje “match request send succesfully. |
| **Postcondición** | El match aparece en la sección de chat. |
| **Excepciones** | Ninguna |
## UC09 Acceder al perfil de un proyecto, seleccionando la foto de perfil al ver un video en la página principal
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario visualizar los proyectos de otros usuarios desde la página principal de la aplicación. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta.| 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona la sección “Projects”. |
|| 2. El usuario selecciona la foto del proyecto o el nombre. |
|| 3. El sistema abre la ventana del proyecto seleccionado. |
|| Para unirse al proyecto visualizar el UC27|
| **Postcondición** | El usuario visualiza el perfil del proyecto. |
| **Excepciones** |Ninguna |

## UC10 Buscar un Proyecto

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario buscar y encontrar proyectos en la plataforma. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona la sección “Projects”. |
| | 2. El usuario selecciona el ícono de la lupa. |
| | 3. El sistema abre la ventana de búsqueda de proyectos | 
| | 4. El usuario ingresa criterios de búsqueda, como necesidades del proyecto, generos, pago por hora, proximidad, etc. |
| | 5. El usuario selecciona “Search”. |
|| 6. El sistema registra los datos ingresados y los utiliza para la búsqueda | 
| | 7. El sistema muestra los resultados de la búsqueda. |
| **Postcondición** | Se muestra una lista de proyectos que coinciden con los criterios de búsqueda. |
| **Excepciones** | Paso 6 - Si no se encuentran proyectos que coincidan con los criterios de búsqueda, se muestra un mensaje informativo y proyectos que cumplan con algunos de los filtros. |

## UC11 Crear un Nuevo Proyecto

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario crear un nuevo proyecto musical en la plataforma. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona la sección “Projects”. |
|| 2. El usuario selecciona la opción “New project” |
|| 3. El sistema abre la ventana de creación de un nuevo proyecto. |
|| 4. El usuario completa los campos solicitados para la creación del proyecto y selecciona “Continue”. |
|| 5. El sistema valida la información ingresada y la registra |
|| 6. El sistema presenta el nuevo proyecto, usuarios afines lo verán y creará el chat grupal entre los usuarios agregados. |  
| **Postcondición** | Se crea un nuevo proyecto musical en la plataforma, el usuario se convierte en el creador del proyecto y se crea el chat grupal. |
| **Excepciones** | Paso 4 - Si la información registrada es inválida, el sistema no concluirá la creación del proyecto |
|| 4.1 El sistema muestra un mensaje de error y señala la información inválida. |

## UC12 Ver contenido del perfil personal
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver el contenido de su propio perfil. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal en cualquiera de las dos secciones.|
|2. El usuario selecciona el icono del usuario ubicado en el menú inferior a la derecha. |
|3. El sistema abre la ventana del perfil personal en la sección de contenido.|
|4. El usuario visualiza su contenido. |
| **Postcondición** | El usuario puede ver su contenido en su perfil principal. |
| **Excepciones** | 2. Si el usuario no ha publicado ningún video el perfil saldrá vacío y el usuario podrá subir su contenido.|
## UC13 Eliminar contenido
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario eliminar el contenido de su propio perfil. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta..  | 
| **Secuencia Normal** | 1. El usuario se encuentra en la sección principal. |
||2. El usuario selecciona el icono del usuario ubicado en el menú inferior a la derecha. |
| |3. El sistema abre la ventana del perfil en la sección de contenido. |
|| 4. El usuario selecciona el icono del lápiz|
||5. El sistema abre la ventana de edición de contenido |
|| 6. El usuario selecciona el botón rojo en la esquina de los videos para eliminarlos. |
|| 4. Al presionar el botón rojo, el sistema eliminará el video del perfil del usuario. |
| **Postcondición** | Los videos que se hayan eliminado desaparecerán del perfil personal del usuario. |
| **Excepciones** | 2. Si no ha subido ningún video usuario, no saldrá la opción de eliminar contenido. |
## UC14 Hacer contenido favorito para que se muestre a otros usuarios en la sección principal
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario marcar como favorito el contenido de su propio perfil. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta.. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la sección principal. |
||2. El usuario selecciona el icono del usuario ubicado en el menú inferior a la derecha. |
| |3. El sistema abre la ventana del perfil en la sección de contenido. |
|| 4. El usuario selecciona el icono del lápiz|
||5. El sistema abre la ventana de edición de contenido |
|| 6. El usuario selecciona la estrella amarilla en la esquina de los videos para hacerlos favoritos. |
|| 7. Al seleccionar la estrella, el sistema establecerá el video como favorito y otros usuarios lo visualizarán en su feed. |
| **Postcondición** | Los videos seleccionados como favoritos saldrán en la sección principal de otros usuarios. |
| **Excepciones** | Si el usuario no ha subido ningún video, no le saldrá esta opción.|

## UC15 Subir un nuevo contenido 
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | En este caso de uso permite al usuario subir un nuevo contenido a su perfil | 
| **Precondición** |1. El usuario ha iniciado sesión en su cuenta | 
| **Secuencia Normal** | 1. El usuario se encuentra en la sección principal. |
||2. El usuario selecciona el icono del usuario ubicado en el menú inferior a la derecha. |
| |3. El sistema abre la ventana del perfil en la sección de contenido. |
|| 4. El usuario selecciona el icono del lápiz|
||5. El sistema abre la ventana de edición de contenido |
|| 6. El usuario selecciona el símbolo de más para añadir contenido. |
|| 7. Al seleccionar el símbolo de más, el sistema abre una ventana para seleccionar el contenido a subir. |
|| 8. El sistema sube el video seleccionado y se podrá ver en el perfil del usuario |
| **Postcondición** | El usuario ha subido su contenido nuevo  |
| **Excepciones** | Si el usuario no ha cargado el contenido no se subirá|

## UC16 Ver informacion personal
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver su información personal en su perfil | 
| **Precondición** |1. El usuario ha iniciado sesión en su cuenta | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona botón de perfil |
|| 2. El usuario selecciona la sección “About me” |
|| 3. En la sección "About me" del perfil, el usuario puede ver la siguiente información:
Ciudad: La ubicación de residencia del usuario.
Curriculum: Información sobre la experiencia y habilidades del usuario.
Instrumentos que toca: Lista de instrumentos musicales que el usuario sabe tocar.
Géneros musicales: Los géneros musicales que le interesan o en los que se especializa.
Costo: Información sobre las tarifas que el usuario cobra por sus servicios.
Matches: Número conexiones con otros usuarios en la aplicación.
 |
| **Postcondición** | El usuario ha visualizado su información personal en su perfil |
| **Excepciones** | Ninguna |
## UC17 Personalizar Perfil CAMBIAR ORDEN

|                  |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario personalizar su perfil. |
| **Precondición** | El usuario ha iniciado sesión en su cuenta. |
| **Secuencia Normal** | 1. El usuario selecciona el ícono de perfil. |
||2. El sistema abre la ventana de perfil personal |
|| 3. El usuario selecciona la sección “About me” |
|| 4. El usuario selecciona la opción “Edit profile” |
|| 5. El sistema abre la ventana de personalización de perfil |
|| 6. El usuario completa el formulario ingresando y seleccionando la información respectiva (Géneros, roles, instrumentos, pago, descripción, foto de perfil, etc.|
|| 7. El usuario selecciona “Submit” para enviar el formulario de registro. |
|| 8. El sistema valida la información ingresada y la registra. |
|| 9. El sistema regresa a la sección “About me” con los datos modificados. |
| **Postcondición** | El perfil del usuario se actualiza con la información registrada. |
| **Excepciones** | Paso 7 - Si la información ingresada es inválida, el sistema rechaza los datos ingresados |
|| 7.1. El sistema no considera válida la información dada en el cuestionario. | 
|| 7.2. El sistema muestra un mensaje de error y señala la información inválida |

## UC18 Ver Proyectos en los que el usuario participa
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver la lista de proyectos en los que está involucrado | 
| **Precondición** |1. El usuario ha iniciado sesión en su cuenta | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona botón de perfil |
|| 2. El usuario selecciona la sección “Projects” |
|| 3. El sistema muestra una lista de proyectos en los que el usuario está actualmente involucrado, incluyendo información relevante sobre cada proyecto, como nombre, descripción y estado.|
| **Postcondición** | El usuario ha visualizado sus proyectos involucrados  en su perfil |
| **Excepciones** | Si el usuario no ha iniciado sesión no se verá la información personal del usuario |
## UC19 Editar proyectos en los que el usuario es el líder
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario que es líder de un proyecto editar la información y configuración de dicho proyecto| 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y es el líder de un proyecto| 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona botón de perfil |
|| 2. El sistema abre la ventana del perfil del usuario |
|| 3. El usuario selecciona la sección “Projects” |
|| 4. El sistema abre la sección “Projects” |
|| 5. El usuario selecciona el botón “Edit project”|
||6. El usuario selecciona el ícono de lápiz en la parte superior derecha|
|| 7. El sistema abre la ventana para editar el proyecto |
||8. El usuario puede editar la información y configuración del proyecto |
|| 9. El usuario selecciona “Continue” |
|| 10. El sistema valida la información proporcionada |
|| 11. El sistema guarda y actualiza con los nuevos datos |
| **Postcondición** | El usuario ya ha editado exitosamente la información y configuración de uno de los proyectos en el cual es líder|
| **Excepciones** |Paso 6. Si el usuario no es líder del proyecto no podrá editarlo|
|| Paso 10. Si el sistema no valida la información no se guardaran los datos |
## UC 20 Ver los contactos personales
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver su lista de contactos personales |
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona botón de chat |
|| 2. El sistema abre la ventana de chat | 
|| 3. El usuario puede visualizar los chats y los contactos personales|  
| **Postcondición** | El usuario visualiza sus contactos personales| 
| **Excepciones** | El usuario visualizará de igual manera sus chats grupales| 
## UC21 - Interactuar en un chat personal
|  |  |
|-|-|
|**Descripción** | Este caso de uso permite a dos usuarios interactuar mediante un chat privado |
|**Precondición** | Ambos usuarios deben tener cuentas activas en el sistema y haber hecho match previamente |  
|**Secuencia Normal** | El usuario se encuentra en la pantalla principal y selecciona el icono de la sección de chat|
|| 2. El sistema abre la sección de chat|
||3. El usuario A accede a la lista de chats  |
||4.El usuario A selecciona el chat con el usuario B  |
||5.El sistema muestra la ventana de chat entre A y B  |
||6.Los usuarios intercambian mensajes de texto en tiempo real |
|**Postcondición** | Queda registrado el historial de conversación entre los usuarios A y B |
|**Excepciones** |  Paso 3. El usuario B ha bloqueado al usuario A, no se puede acceder al chat |

## UC22 - Interactuar en un chat grupal  
|  |  |
|-|-|
|**Descripción** | Permite la interacción entre varios usuarios en un chat grupal|
|**Precondición** | Los usuarios deben pertenecer al mismo proyecyo y tener cuentas activas en el sistema |
|**Secuencia Normal** | El usuario se encuentra en la pantalla principal y selecciona el icono de la sección de chat|
|| 2. El sistema abre la sección de chat|
||3. El usuario A accede a la lista de chats  |
||4.El usuario A selecciona el chat grupal con el que desee interactuar. |
||5.El sistema muestra la ventana de chat grupal  |
||6.Los usuarios intercambian mensajes de texto en tiempo real |
|**Postcondición**| El historial y contenido compartido quedan registrados en el grupo G|
|**Excepciones** |   |
## UC23-Editar un chat grupal
|   |   |  
| - | - |
| **Descripción**  | Este caso de uso permite a un usuario administrar un chat grupal, lo que incluye la capacidad de agregar o eliminar miembros, cambiar configuraciones, etc. |
| **Precondición** | El usuario ha iniciado sesión en su cuenta y es administrador del grupo. |
|**Secuencia Normal** | El usuario se encuentra en la pantalla principal y selecciona el icono de la sección de chat|
|| 2. El sistema abre la sección de chat|
||3. El usuario A accede a la lista de chats  |
||4.El usuario A selecciona el chat grupal que desea editar. |
||5.El sistema muestra la ventana de chat grupal  |
||6.El usuario selecciona el icono de engranaje en la parte superior a la derecha |
|| 7. El sistema abre el menú de configuración de grupo |
|| 8. El usuario puede editar el nombre del grupo y los integrantes |
| **Postcondición** | El chat grupal se administra según las acciones realizadas por el usuario. |
| **Excepciones** | 6. El usuario no puede acceder a las configuraciones del grupo debido a que no es administrador del grupo |
## UC24 - Aceptar una solicitud de match  
|  |  |
|-|-|
|**Descripción** | Permite a un usuario aceptar una solicitud de match con otro usuario |
|**Precondición** | El usuario debe haber iniciado sesión y tener una solicitud de match pendiente de otro usuario |
|**Secuencia Normal** | 1. El usuario se encuentra en la página principal y selecciona la sección de chat |
|| 2. El sistema abre la sección de chat|
|| 3. El usuario A selecciona una solicitud de match |
|| 4. El sistema abre el perfil del usuario B |
|| 5. El usuario A selecciona “Accept match” |
|| 6. El sistema registra el match entre los usuarios A y B |
|| 7. El sistema regresa a la sección de chat y se habilita el chat entre el usuario A y B|
| **Postcondición** | Queda registrado el match entre los usuarios A y B, permitiendo la interacción por chat |
| **Excepciones** |   Paso 3. El usuario B eliminó la solicitud de match|
|| Paso 5. El usuario A niega la solicitud del usuario B|

## UC25 - Aceptar solicitud de match a un proyecto
|  |  |
|-|-|
|**Descripción** | Permite a un usuario aceptar una solicitud de otro usuario para unirse a su proyecto publicado |
|**Precondición** | El usuario debe haber iniciado sesión y tener publicado un proyecto con solicitudes pendientes de match |
|**Secuencia Normal** | 1. El usuario se encuentra en la página principal |
|| 2. El usuario selecciona el icono de chat para abrir la sección de chat |
|| 3. El sistema abre la sección de chat, donde llegan las notificaciones de match |
|| 4. El sistema selecciona la notificación de match de proyecto|
|| 5. El sistema abre el perfil del usuario que quiere unirse al proyecto  |
||6. El usuario selecciona la opción “Integrate to proyect” | 
|| 7. El sistema registra el match y añade al usuario que creó el match al proyecto|
|| 8. El sistema regresa a la sección de chat|
|**Postcondición** | El usuario B queda registrado como miembro del proyecto P |
|**Excepciones** | 6. El dueño del grupo no quiere añadir al usuario |
## UC26 Dar Match a un Usuario 

|                  |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario indicar interés en otro usuario, lo que puede llevar a un "match" si ambos usuarios están interesados mutuamente. | 
| **Precondición** | El usuario 1 ha iniciado sesión en su cuenta y se encuentra en el perfil del usuario 2. | 
| **Secuencia Normal** | 1. El usuario 1 visualiza el perfil del usuario 2. |
|| 2. El usuario 1 selecciona la opción de "Match". |
|| 3. El sistema notifica al usuario 2 en la sección de Chat. |
| **Postcondición** | El sistema ha notificado al usuario 2 el interés del usuario 1. |
| **Excepciones** | - Ninguna |

## UC27 Dar match a un proyecto
| | |
|--|--|
| **Descripción**  | Este caso de uso permite a un usuario indicar interés en un proyecto, lo que puede llevar a ser parte del proyecto si es aceptado. | 
| **Precondición** | El usuario 1 ha iniciado sesión en su cuenta y se encuentra en la pantalla del proyecto. | 
| **Secuencia Normal** | 1. El usuario 1 visualiza la pantalla del proyecto. |
|| 2. El usuario 1 selecciona la opción de "I want to join". |
|| 3. El sistema notifica al líder del proyecto en la sección de Chat. |
| **Postcondición** | El sistema ha notificado al líder del proyecto el interés del usuario 1. |
| **Excepciones** | - Ninguna |

## UC28 Visualizar el contenido del perfil de un usuario

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver los videos musicales que otro usuario ha subido a su cuenta en la plataforma. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y está viendo el perfil de otro usuario. | 
| **Secuencia Normal** | 1. El usuario 1 accede al perfil del usuario 2. |
| | 2. El sistema muestra el perfil del usuario 2 y por defecto muestra la sección “contenido”, donde se muestran los videos musicales subidos por el usuario 2. |
| | 3. El usuario 1 ve los videos musicales subidos por el usuario 2. |
| **Postcondición** | El usuario visualiza los videos musicales del perfil del otro usuario. |
| **Excepciones** | Paso 3 - Si no hay videos disponibles en el perfil del otro usuario, el sistema muestra un mensaje informativo. |

## UC29 Visualizar la descripción de un usuario

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver la descripción y detalles personales de otro usuario en su perfil. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y está viendo el perfil de otro usuario. | 
| **Secuencia Normal** | 1. El usuario accede al perfil de otro usuario. |
| | 2. El usuario selecciona la sección de “Sobre mí” en el perfil del otro usuario. |
|| 3. El sistema abre la sección de descripción del perfil. |
| | 3. El usuario lee la información proporcionada por el otro usuario. |
| **Postcondición** | El usuario visualiza información personal del perfil del otro usuario. |
| **Excepciones** | Ninguna |

## UC30 Visualizar los proyectos de un usuario

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ver los proyectos musicales abiertos a recibir solicitudes que otro usuario ha creado. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y está viendo el perfil de otro usuario. | 
| **Secuencia Normal** | 1. El usuario accede al perfil de otro usuario. |
| | 2. El usuario selecciona la sección de “Proyectos” en el perfil del otro usuario. |
| | 3. El sistema muestra una lista de proyectos que el usuario 2 tiene disponibilidad para otros usuarios |
| | 4. El usuario selecciona un proyecto de la lista de proyectos disponibles del usuario 2. |
|| 5. El sistema abre la pantalla del proyecto |
| | 6. El usuario visualiza la descripción y video de presentación del proyecto, los miembros con los que cuenta y los roles que necesita para el proyecto. |
| **Postcondición** | El usuario visualiza los proyectos musicales del perfil del otro usuario. |
| **Excepciones** | Paso 3 - Si el usuario 2 no cuenta con proyectos creados, el sistema muestra un mensaje informativo. |

## UC31 Visualizar los contactos de un usuario

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario 1 ver la lista de “Matches” de el usuario 2 en la plataforma. | 
| **Precondición** | El usuario 1 ha iniciado sesión en su cuenta y está viendo el perfil del usuario 2. | 
| **Secuencia Normal** | 1. El usuario 1 accede al perfil de otro usuario. |
| | 2. El usuario 1 selecciona el área de “Matches” en el perfil del usuario 2. |
|| 3. El sistema abre la ventana de los matches del usuario 2 |
| | 3. El usuario ve la lista de “Matches” del usuario 2. |
| **Postcondición** | El usuario 1 visualiza la lista de “Matches” del perfil del usuario 2. |
| **Excepciones** | Paso 3 - Si el otro usuario no tiene “Matches” en su perfil, el sistema no muestra resultados. |
