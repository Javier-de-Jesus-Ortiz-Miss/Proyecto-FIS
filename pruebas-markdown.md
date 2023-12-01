

## UC21 - Interactuar en un chat personal

|  |  |
|-|-|
|**Descripción** | Este caso de uso permite a dos usuarios interactuar mediante un chat privado |
|**Precondición** | Ambos usuarios deben tener cuentas activas en el sistema y haberse agregado previamente |  
|**Secuencia Normal** | 1. El usuario A accede a la lista de chats  ||
||2.Selecciona el chat con el usuario B  |
||3.El sistema muestra la ventana de chat entre A y B  |
||4.Los usuarios intercambian mensajes de texto en tiempo real |
||5.Los usuarios pueden compartir imágenes y audio en el chat |
|**Postcondición** | Queda registrado el historial de conversación entre los usuarios A y B |
|**Excepciones** |  3.1. El usuario B ha bloqueado al usuario A, no se puede acceder al chat |
||4.1. Un archivo compartido excede el límite permitido|





## UC22 - Interactuar en un chat grupal  

|  |  |
|-|-|
|**Descripción** | Permite la interacción entre varios usuarios en un chat grupal|
|**Precondición** | Los usuarios deben pertenecer al mismo grupo y tener cuentas activas en el sistema |
|**Secuencia Normal** | 1. El usuario A ingresa al chat grupal G  |
||2. El sistema muestra los miembros y el historial de G  |
||3. Los usuarios del grupo intercambian mensajes en tiempo real | 
||4. Los usuarios pueden compartir archivos e interactuar |  
|**Postcondición** | El historial y contenido compartido quedan registrados en el grupo G |
|**Excepciones** |  3.2. Un usuario escribe contenido inapropiado y es expulsado  |
||4.1. Un archivo compartido excede el límite permitido |


## UC23-Editar un chat grupal
|                 |                     |  
| ---------------- | ------------------- | 
| **Descripción**  | Este caso de uso permite a un usuario administrar un chat grupal, lo que incluye la capacidad de agregar o eliminar miembros, cambiar configuraciones, etc. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y es administrador del grupo. | 
| **Secuencia Normal** | 1. El usuario accede a la sección de administración del chat grupal. |
| | 2. El usuario realiza acciones de administración, cómo agregar y/o eliminar miembros, cambiar configuraciones, eliminar mensajes, etc. |
| **Postcondición** | El chat grupal se administra según las acciones realizadas por el usuario. |
| **Excepciones** | 1.2 El usuario no puede acceder a las configuraciones del grupo debido a que no es administrador del grupo |



## UC24 - Aceptar una solicitud de match  

|  |  |
|-|-|
|**Descripción** | Permite a un usuario aceptar una solicitud de match con otro usuario |
|**Precondición** | El usuario debe tener una solicitud de match pendiente de otro usuario |
|**Secuencia Normal** | 1. El sistema notifica al usuario A que tiene una solicitud de match del usuario B  |
||2. El usuario A ingresa a la sección de solicitudes de match |
|| 3. El usuario A selecciona aceptar la solicitud de match con el usuario B  |
||4. El sistema registra el match entre los usuarios A y B |
|**Postcondición** | Queda registrado el match entre los usuarios A y B, permitiendo la interacción |
|**Excepciones** |   3.1. El usuario B eliminó la solicitud de match|
|| 3.2. El usuario A niega la solicitud del usuario B|




## UC25 - Aceptar solicitud de match a un proyecto

|  |  |  
|-|-|
|**Descripción** | Permite a un usuario aceptar una solicitud de otro usuario para unirse a su proyecto publicado |
|**Precondición** | El usuario debe tener publicado un proyecto con solicitudes pendientes de match |
|**Secuencia Normal** | 1. El sistema notifica al usuario A que su proyecto P tiene una solicitud de match de usuario B  |
||2. El usuario A ingresa a las solicitudes de match para el proyecto P |
|| 3. El usuario A acepta la solicitud de match del usuario B  |
||4. El sistema registra que el usuario B se ha unido al proyecto P |  
|**Postcondición** | El usuario B queda registrado como miembro del proyecto P |
|**Excepciones** | 3.1 El cupo de miembros está lleno |
|| 3.2 El usuario B eliminó la solicitud |


