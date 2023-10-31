# Casos de Uso

## UC01 Ingresar a la cuenta de un usuario

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario ingresar a su cuenta. | 
| **Precondición** | El usuario se encuentra en la pagina de registro. | 
| **Secuencia Normal** | 1. El usuario ingresa el conrreo y contraseña. |
| | 2. El sistema valida los datos ingresados. |
|| 3. El sistema inicia la sesión del usuario. |
| **Postcondición** | Se inicia sesión en el perfil validado. |
| **Excepciones** | Paso 4- El sistema rechaza los datos ingresados
4.1 el sistema rechhaza los datos
Si la información ingresada es inválida, el sistema muestra un mensaje de error. |

<!--
## UC03 Verificar Usuario
|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso implica verificar la identidad o cuenta de un usuario. | 
| **Precondición** | El usuario está registrado en la plataforma. | 
| **Secuencia Normal** | 1. El usuario proporciona la información de verificación necesaria. |
| **Postcondición** | La cuenta del usuario se verifica. |
| **Excepciones** | - Si la información proporcionada es incorrecta, el proceso de verificación falla. |
-->

## UC02 Registrar un Nuevo Usuario

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite a un usuario crear una cuenta personal para acceder a todas las características de la aplicación. | 
| **Precondición** | El usuario no está registrado en la plataforma. | 
| **Secuencia Normal** | 1. El usuario abre la aplicación. |
| | 2. El usuario ingresa su información personal (nombre de usuario, email, fecha de nacimiento, género, país, ciudad) <!-- Foto de perfil, descripción --> |
| | 3. El usuario selecciona de entre las opciones mostradas, los instrumentos musicales en los cuales tiene experienciade |
| | 4. El usuario selecciona que roles desempeña en la industria musical |
| | 5. El usuario envía el formulario de registro. |
| **Postcondición** | Se crea la cuenta del usuario y se inicia sesión. |
| **Excepciones** | Si la información ingresada es inválida, el sistema muestra un mensaje de error.  - |
<!-- Secuencia normal, pasos que probablemente pongamos:
| | 5. El usuario selecciona una de las dos opciones de cobro, si selecciona pagar, muestra el cobro por hora, en caso contrario esta opción no es desplegada  |
| | 6. El usuario sube un video mostrando una interpretación músical con un instrumento que domine, este video será mostrado en la pantalla de presentación de usuario  |
-->


## UC04 Personalizar Perfil

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario personalizar su perfil. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario va a la sección de personalización de perfil. |
| | 2. El usuario realiza cambios en su información de perfil o configuraciones. |
| | 3. El usuario guarda los cambios. |
| **Postcondición** | El perfil del usuario se actualiza con la información personalizada. |
| **Excepciones** | - Si hay errores en los datos de personalización, el sistema puede mostrar un mensaje de error. - Ejecutarse automaticamente cuando se inicie sesion por primera vez|

## UC05 Ver Videos Subidos por Otros Usuarios

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario navegar y ver videos subidos por otros usuarios de la plataforma. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario accede a la sección de navegación de videos. |
| | 2. El usuario selecciona un video para ver. |
| **Postcondición** | El usuario ve el video seleccionado. |
| **Excepciones** | - Si el video seleccionado no está disponible o ha sido eliminado, se puede mostrar un mensaje de error. |

## UC06 Deslizar el Video a la Derecha para Generar un Match

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario deslizar un video hacia la derecha para indicar interés y potencialmente generar un match. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y está viendo un video. | 
| **Secuencia Normal** | 1. El usuario desliza el video hacia la derecha. |
| **Postcondición** | El sistema registra el interés del usuario en el video. |
| **Excepciones** | - Ninguna |

## UC07 Deslizar el Video a la Izquierda para Indicar que no Interesa

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario deslizar un video hacia la izquierda para indicar desinterés. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y está viendo un video. | 
| **Secuencia Normal** | 1. El usuario desliza el video hacia la izquierda. |
| **Postcondición** | El sistema registra el desinterés del usuario en el video. |
| **Excepciones** | - Ninguna |

## UC08 Deslizar el Video hacia Abajo para Pasar al Siguiente Video

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario deslizar un video hacia abajo para saltar al siguiente video en la secuencia. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y está viendo un video. | 
| **Secuencia Normal** | 1. El usuario desliza el video hacia abajo. |
| **Postcondición** | Se muestra el siguiente video en la secuencia. |
| **Excepciones** | - Ninguna |

## UC09 Seleccionar la Foto de Otro Usuario para Ver su Perfil

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario seleccionar la foto de otro usuario para ver su perfil. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta y está navegando por las fotos de otros usuarios. | 
| **Secuencia Normal** | 1. El usuario toca la foto de otro usuario. |
| **Postcondición** | Se muestra el perfil del usuario seleccionado. |
| **Excepciones** | - Ninguna |

## UC10 Seleccionar la Lupa para Desplegar la Sección de Búsqueda

|                 |                     |                  |
| ---------------- | ------------------- | ---------------- |
| **Descripción**  | Este caso de uso permite al usuario acceder a la funcionalidad de búsqueda al seleccionar el ícono de la lupa. | 
| **Precondición** | El usuario ha iniciado sesión en su cuenta. | 
| **Secuencia Normal** | 1. El usuario toca el ícono de la lupa. |
| **Postcondición** | Se abre la sección de búsqueda y el usuario puede ingresar consultas de búsqueda. |
| **Excepciones** | - Ninguna |
