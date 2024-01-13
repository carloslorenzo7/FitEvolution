<h1 align="center">FitRevolution</h1>

![image](https://github.com/haliercesr/FitRevolution/assets/115671323/364d958a-2751-4d92-9c48-caea6f23f163)

El proyecto consiste en una aplicación web que permite unir deportistas y/o personas que se ejercitan con entrenadores personales, logrando una mayor comodidad, diversidad de precios, flexibilidad de horarios y elección de entrenadores. Trabajamos en un equipo de 7 desarrolladores bajo metodologias agiles como SCRUM y Trello, un mentor y un PO. La duracion del proyecto fue de 1 mes y medio. Los mockups iniciales se hicienron en Figma, el diagrama y las relaciones de la base de datos se hicieron en Diagrams.net.

## Tabla de Contenidos

- [Funcionalidades](#funcionalidades)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Capturas de Pantalla](#capturas-de-pantalla)
- [Guía de Uso](#guía-de-uso)
- [Cómo Contribuir](#cómo-contribuir)
- [Licencia](#licencia)

## Funcionalidades

**1.** Posibilidad de login con usuario y contraseña, google y facebook usando el servicio de Firebase de Google Cloud. Registro de usuarios y entrenadores con posibilidad de subir imagenes gracias al servicio de Cloudinary.

**2.** Para los entrenadores se debe aprobar la cuenta despues de loguearse en la pagina mediante el panel de administrador o superadministrador

**3.** Los usuarios deben elegir un entrenador, si no aparece ninguno es porque deben aprobarse desde la cuenta de administrador y/o superadministrador

**4.** Tanto los usuarios como los entrenadores cuentan con un dashboard.

**5.** En el dashboard del usuario cada deportista puede ver sus compras realizadas, ver sus entrenamientos, cambiar de entrenador, descargar su comprobante de pago y/o sus rutinas, seleccionar un plan de entrenamiento y pagar con tarjeta de credito.

**6.** Cada usuario tiene la posibilidad de hacer una review y pdar un puntaje a cada entrenador.

**7.** Filtros combinados para la seleccion de entrenadores

**8.** Cada entrenador en su dashboard tiene una lista para ver todos sus usuarios, ver sus pagos, crear un plan de entrenamiento para un cliente, y ver la informacion de su cuenta.

**9.** Se esta trabajando en la posibilidad de tener un chat entre el usuario y el entrenador.Tambien la posibilidad de hacer videollamadas

**10.** Alertas Personalizadas: Se muestran alertas personalizadas en caso de errores o acciones importantes, en el registro y login de usuarios

**11.** Rutas y Enrutamiento: Se utiliza React Router para administrar y facilitar la navegación entre diferentes páginas y componentes de la aplicación.

**12.** Gestión de Estado con Redux: Redux se utiliza para gestionar el estado global de la aplicación, como guardar informacion recibida del servidor para usarla en el front ya sea para entrenadores y usuarios.

**13.** Se esta trabajando en el Diseño Responsivo usando Material UI: La interfaz está diseñada para adaptarse a diferentes tamaños de pantalla y dispositivos, asegurando una experiencia de usuario consistente.

**14.** Estilos Personalizados: Solo se utilizo Material UI , gracias a su acil instalacion, uso de componentes y diseño adaptable.

**15.** Las cuentas de usuarios y entrenadores se guardan en la base de datos que esta echa con PostreSQL.

**16.** La aplicacion cuenta con un panel de administrador con las siguientes funciones: mandar emails con Nodemailer a cada usuario y entrenador, filtrar y ordenar usuarios y entrenadores. Tambien cuenta con borrado logico para suspendes o aprobar un entrenador y para bannear o desbannear un deportista.

**17.** La aplicacion tambien cuenta con panel de superadministrador que ademas de tener todas las funciones del administrador, se puede cambiar de rol a cualquier cuenta.

**18.** Guardado de informacion mediante localstorage y vista de invitado con posibilidad de agregar productos al carrito de compras



## Tecnologías Utilizadas

- Vite
- React
- React Router
- Redux
- Axios
- CSS
- NodeJS
- Express
- PostgreSQL
- Sequalize
- Promises
- AsyncAwait

## Capturas de Pantalla


 <img src="https://github.com/haliercesr/PI-Drivers-2023/assets/115671323/f1bb13fb-7707-47c2-aad8-b7fe6c64302a" alt="alt text" width=225 height=400>

 <img src="https://github.com/haliercesr/PI-Drivers-2023/assets/115671323/9cd98e80-655c-48aa-ab1b-90b413f24b35" alt="alt text" width=225 height=400>

 <img src="https://github.com/haliercesr/PI-Drivers-2023/assets/115671323/1880336d-d10b-4cd2-8821-8d7bfc25b267" alt="alt text" width=225 height=400>

 <img src="https://github.com/haliercesr/PI-Drivers-2023/assets/115671323/401cfe29-fd28-43c1-b2bf-6c536613c7b0" alt="alt text" width=225 height=400>

![image](https://github.com/haliercesr/PI-Drivers-2023/assets/115671323/ebc325ca-0c5a-4aad-80a3-5de7908ddba5)


![image](https://github.com/haliercesr/PI-Drivers-2023/assets/115671323/92402a00-94aa-4179-9b80-483e680b6f48)







## Guía de Uso

**1.** Visita [https://pi-drivers-2023.vercel.app/](https://pi-drivers-2023.vercel.app/) en tu navegador.

<p align="center">
  <img src="https://github.com/haliercesr/PI-Drivers-2023/assets/115671323/7dbeb234-2ef7-4ed5-a9c8-1996bc6e086f" alt="Inicio" width=400 height=200>
</p>


**2.** Para ver los detalles de alguna conductor hacer click en una card o insertar el nombre en el buscador y presionar "buscar"

<p align="center">
  <img src="https://github.com/haliercesr/PI-Drivers-2023/assets/115671323/f42a7b76-93f8-415b-bb49-fe780fa60ef9" alt="Inicio" width=400 height=200>
</p>


**3.** Para crear una raza hacer click en el boton "Create", completar todos los campos obligatorios y hacer click en crear.Para la imagen podes buscar el link de alguna imagen en la web.Si todo va bien te saldra el mensaje "el piloto se creo con exito!". Para volver al menu principal seleccionar el boton "volver a inicio"

<p align="center">
  <img src="https://github.com/haliercesr/PI-Drivers-2023/assets/115671323/f2d7ad7a-17af-4444-ad8d-faf9256354d0" alt="Inicio" width=400 height=200>
</p>


**4.** Para filtrar mejor las busquedas utilizar los filtros combinados.

<p align="center">
  <img src="https://github.com/haliercesr/PI-Drivers-2023/assets/115671323/199a6ae1-8fca-4565-8515-8f836a2b5d34" alt="Inicio" width=400 height=200>
</p>


**5.** Disfruta buscando a tu conductor favorito.

## Cómo Contribuir

Si quieres contribuir a este proyecto, sigue estos pasos:

1. Haz un fork de este repositorio.
2. Crea una rama con tu nueva funcionalidad (`git checkout -b nueva-funcionalidad`).
3. Realiza tus cambios y realiza commits (`git commit -m 'Añadir nueva funcionalidad'`).
4. Sube tus cambios a tu fork (`git push origin nueva-funcionalidad`).
5. Crea un pull request en este repositorio.

## Licencia

Este proyecto está bajo la Licencia [---](----).
