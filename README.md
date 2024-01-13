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


![image](https://github.com/haliercesr/FitRevolution/assets/115671323/04aaa867-f424-4929-ad15-2de0c0fee3ae)


![image](https://github.com/haliercesr/FitRevolution/assets/115671323/b4c501c1-21a5-45df-95bc-58f1d0fd7c6b)

![image](https://github.com/haliercesr/FitRevolution/assets/115671323/359d007e-4594-4682-b62a-5ebc891b9673)





## Guía de Uso

**1.** Visita [https://fit-revolution-main.vercel.app/](https://fit-revolution-main.vercel.app/) en tu navegador.

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/222eef4f-48de-4338-9c4c-4392769045a3" alt="Inicio" width=400 height=200>
</p>


**2.** Registrate como usuario o como entrenador ya sea con usuario y/o contraseña, google o facebook

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/ec0adc08-4e06-4c19-9333-4f4fc871c9cf" alt="Inicio" width=400 height=200>
</p>

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/2f08ccbe-15a7-4e14-95ca-87cf9d763f9a" alt="Inicio" width=400 height=200>
</p>


**3.** Para los deportistas deben elegir un profesor un comprar uno de sus planes de entrenamientos

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/7068b312-ccd0-454b-b4e7-b519ae7c4274" alt="Inicio" width=400 height=200>
</p>


**4.** Una vez que elijen el profesor van al carrito para pagar. Los datos de la tarjeta de prueba son : n° de tarjeta "4242 4242 4242 4242", el vencimiento "04/33" tiene que ser mayor a la fecha actual  y con el siguiente formato mm/yy,el CVC "123" y el CP "45678" 

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/401c42a2-c5d9-467c-a925-0aa8002cc511" alt="Inicio" width=400 height=200>
</p>

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/5a0cbdd8-2d8d-4502-b0e7-8aced94deb86" alt="Inicio" width=400 height=200>
</p>


**5.** Para los entrenadores la primera vez que se loguean en la aplicacion deben ser aprobados por un administrador.Deben completar todos los datos del formulario y esperar a que sean aprobados.

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/20d8539d-c5fa-486c-bd77-508980c07031" alt="Inicio" width=400 height=200>
</p>

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/65605779-3f4d-4ab6-a834-725bbd52bfa7" alt="Inicio" width=400 height=200>
</p>

**6.** Una vez que el entrenador es aprobado, puede ver los usuarios activos, crear rutinas, ver la informacion de su cuenta y demas.


**7.** Para ver el panel de administrador se ingresa en el login de usuario o entrenador y se inicia sesion con las siguientes crendenciales: usuario "cesarhalier@gmail.com" y contraseña "Cesar123!".

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/556c1a5a-f356-4d02-bb9b-ae01ed323d66" alt="Inicio" width=400 height=200>
</p>


**8.** Una vez en el inicio de sesion de Admin, ingresar con las siguientes credenciales: usuario "adminTr" y contraseña "postal". En el dashboard del admin se pueden aprobar y suspender entrenadores, bannear y desbannear usuarios, enviar emails massivos , buscar usuarios y con una clave secreta borrar todos los usuarios.

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/f7f16682-a861-4569-898f-dccf5b4f51b3" alt="Inicio" width=400 height=200>
</p>

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/f463fbe2-0412-4be4-9e18-d0341bc5055a" alt="Inicio" width=400 height=200>
</p>

**9.** El dashboard del superadmin tiene las mismas funciones que el admin ademas de otra funcion. El superadmin puede cambiar el rol de un usuario, ejemplo cambiar usuario a entrenador. Para ver el panel de superadmin se ingresa en el login de usuario o entrenador y se inicia sesion con las siguientes crendenciales: usuario "haliercesr@gmail.com" y contraseña "Cesar123!".

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/de39037a-d45b-4f28-9b90-5f44721b37e7" alt="Inicio" width=400 height=200>
</p>

<p align="center">
  <img src="https://github.com/haliercesr/FitRevolution/assets/115671323/b32af0fb-49a2-4b21-a237-294007a69bb6" alt="Inicio" width=400 height=200>
</p>


**10.** Disfruta.



## Cómo Contribuir

Si quieres contribuir a este proyecto, sigue estos pasos:

1. Haz un fork de este repositorio.
2. Crea una rama con tu nueva funcionalidad (`git checkout -b nueva-funcionalidad`).
3. Realiza tus cambios y realiza commits (`git commit -m 'Añadir nueva funcionalidad'`).
4. Sube tus cambios a tu fork (`git push origin nueva-funcionalidad`).
5. Crea un pull request en este repositorio.

## Licencia

Este proyecto está bajo la Licencia [---](----).
