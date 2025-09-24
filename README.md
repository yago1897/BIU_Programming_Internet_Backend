<img width="808" height="372" alt="image" src="https://github.com/user-attachments/assets/3c781ee9-6bef-41bf-8948-5d5116e07654" />




Plataforma de Ventas Ecommerce es una solución integral para la compra y venta de productos en línea. Ofrecemos una experiencia de usuario optimizada con una amplia selección de artículos tecnológicos, también incluimos electrodomésticos y artículos para el hogar. Nuestro objetivo es brindar a los clientes acceso a productos de alta calidad al mejor precio, con un proceso de compra eficiente y seguro

Inicialmente se observa la vista del login donde de acuerdo al perfil del usuario puede acceder con sus credenciales 
![image](https://github.com/user-attachments/assets/7eca75aa-812e-4cdb-b9cc-967b26a38dd7)

Se observa el diseño de la maqueta cumple con los requerimientos que se solicitaron. Se puede observar el módulo Dashboard donde muestra el total de ingresos, las ventas realizadas y los productos vendidos como se aprecia en la imagen
![image](https://github.com/user-attachments/assets/ec915a40-6bea-43d9-9a2c-b0eaed2ab230)

Luego se selecciona el módulo de Productos con algunos de ellos ya registrados en base de datos sql server y se reflejan en la vista como se aprecia en la imagen

![image](https://github.com/user-attachments/assets/ae95f925-f470-4a13-bcde-72982d6bc140)

Luego se puede seleccionar el módulo de Ventas donde se puede efectuar una compra como se aprecia en la imagen

![image](https://github.com/user-attachments/assets/71f7dd4a-a7e0-4646-8b13-c6a556a5c2ef)

Se puede seleccionar el módulo de historial de ventas donde se puede ver el detalle de la venta realizada como se aprecia en las imágenes

![image](https://github.com/user-attachments/assets/35e0324d-4296-4377-ae4c-4f435b900a2c)

![image](https://github.com/user-attachments/assets/35b5a9b4-8514-4dc7-873a-a9de3730d5b9)

También cuenta con un módulo de reportes donde se puede realizar un reporte filtrando por fecha de cuando fue realizada la venta y exportar a excel 

![image](https://github.com/user-attachments/assets/2af0287f-ced6-4d3f-b416-8469649d33d0)

Modo en que se realizó la plataforma Ecommerce: la maquetación fue realizada por Angular versión 15, en este caso ya está funcionando ya que está conectada a base de datos sql server y el backend realizado en la plataforma .Net-Core

La plataforma "Sistema de ventas Ecommerce" fue realizado bajo las especificaciones planteadas cuya maquetación cumpliera con lo solicitado, que era crear un proyecto front de libre albedrio que consumiera datos de una API. en este caso yo escojí angular 15 para el frontend y poder consumir un crud de datos realizado en ASP.NET-CORE, donde expongo 4 servicios API-REST-FULL "GET", "POST","PUT" y "DELETE". La aplicación está realizada bajo una arquitectura de N-capas, empleando un patron repositorio, empleando DTOS, validaciones de datos, autommaper, interfaces e inyección de dependencias, con buenas prácticas y principios solid.


Tarea: Asignación No. 3 Desarrollo de un validador de formularios dinámico del lado del cliente, caso Registro de nuevo Usuario del Sistema

Como se aprecia en la imagen los campos validan su obligatoriedad

![image](https://github.com/user-attachments/assets/528c2e6d-4ee1-4684-b9a8-13ac1f68319b)

En este caso también valida que el formato del correo electrónico sea el formato correcto como se ve en la imagen

![image](https://github.com/user-attachments/assets/cdccb09f-a332-40d9-aeb9-b97d2a4f5e7c)

Se ingresan las credenciales equivocadas y arroja el mensaje de alerta notificando que no se encontraron coincidencias

![image](https://github.com/user-attachments/assets/3e688369-8aa7-4301-99c7-3da646b8b942)


En este caso ya se ingresa el email y contraseña correctos para poder ingresar

![image](https://github.com/user-attachments/assets/1b8be49e-93e9-4225-8fa6-2b58f0be9219)

Del mismo modo las validaciones de los campos ocurren en el módulo Agregar Usuarios, no se activa el botón guardar hasta que no se llenen los campos por completo

![image](https://github.com/user-attachments/assets/23929bcf-3db0-47cd-ac8b-50fd0b93e404)

De igual forma en el módulo "Agregar Producto"

![image](https://github.com/user-attachments/assets/a923dcee-7306-4954-a40e-ec9931cf82ee)

De igual manera con el módulo "Ventas"

![image](https://github.com/user-attachments/assets/2b7f0de5-ee15-4e99-9756-5c9e3f8d1dea)

De igual manera con el módulo de "Reportes"

![image](https://github.com/user-attachments/assets/e484d03a-c03e-4c91-affe-114a74526fa8)

Al realizar un ingreso de un usuario con rol de empleado, se llenan los datos como se muestra a continuación 

![image](https://github.com/user-attachments/assets/71e11423-c130-4ff1-a72e-836346005860)

Y se observa que se ingresa correctamente en la grilla y mostrando un mensaje de alerta exitoso como se aprecia en la imágen

![image](https://github.com/user-attachments/assets/f6485d89-f8fe-4a06-b374-4511d0d7d1ef)

Las validaciones de los campos y los mensajes de alerta del lado cliente fueron implementados utilizando Angular 14. Se usaron Reactive Forms para gestionar la validación de los inputs, incluyendo la verificación del formato del email con Validators.email. Además, se empleó Angular Material para mostrar mensajes de error y mejorar la experiencia del usuario.







Tarea: Asignación No. 4 Convertir el frontend de la Plataforma en una SPA  con AngularJS


Tal y como se pide en el primer requerimiento, la aplicación Ecommerce se convierte en una SPA(Single Page Application) en Angular 14 y permite la navegación de rutas sin recargar la página, sino todo contendido en la SPA como se muestra en las siguientes imágenes

![image](https://github.com/user-attachments/assets/c02389d7-a308-47ef-82e6-3a6fc38bb4c6)

![image](https://github.com/user-attachments/assets/bdc10554-9317-47d6-8eca-ec1382e3096d)

![image](https://github.com/user-attachments/assets/5aba5d63-1827-4141-be58-030b7ce94a98)

![image](https://github.com/user-attachments/assets/aa1e51fa-4509-481d-a034-4dad6433a2be)

![image](https://github.com/user-attachments/assets/4546dcac-550e-4dae-ac87-ecc02055b401)



Tal como lo pide en otro de los requerimientos, se gestiona productos, con nombre, categoría, valor, stock, estado etc... como se aprecia en la imagen y se pone en funcionamiento como se verá a continuación

![image](https://github.com/user-attachments/assets/f5beb04d-f6ce-4c2a-86da-2c4c18e3f62b)

Se ingresa un teclado inalámbrico con valor de 1500 como ejemplo y se da guardar

![image](https://github.com/user-attachments/assets/b0c1f3da-9821-491d-ada8-1b632df116ee)


Y vemos que el mensaje de alerta dice "registrado con éxito"

![image](https://github.com/user-attachments/assets/90fc57f6-5eb0-4ff7-bfab-64f6a46e99f3)

Y vemos que queda registrado el teclado inalámbrico como se aprecia en la imagen subrayada en color rojo

![image](https://github.com/user-attachments/assets/3c2ed97b-1262-4c9a-ada1-2fccb8c225ec)

La manera de como se implementaron fue por medio de API RESTful que se mostrarán a continuación como fue solicitado en los requerimientos

Estas API RESTful fueron realizadas en .Net-Core para luego ser consumidas por Angular 14, a continuación se muestran las API RESTful en .Net-Core

![image](https://github.com/user-attachments/assets/209065f2-4a28-4959-a67a-8fc96fa9de55)

![image](https://github.com/user-attachments/assets/749b3a92-754d-4651-a0e8-1bc7d93e1b3e)

![image](https://github.com/user-attachments/assets/6743266c-e8ac-44b9-a32a-a2d1e9a211b5)

A continuación se muestra parte del código de las Apis en .Net-Core, en este caso las API RESTful de Usuarios para Iniciar Sesion, Crear, Editar, y eliminar usuarios

![image](https://github.com/user-attachments/assets/66ac3493-2e81-436d-a7e2-c9b01bd9a0ea)

![image](https://github.com/user-attachments/assets/1b86164c-deb6-404e-aa85-1edbf5d04f40)

![image](https://github.com/user-attachments/assets/16451e6c-63ae-4a55-921c-c51c453ee01f)

![image](https://github.com/user-attachments/assets/b5d5f37f-f795-4890-aca9-d96ec2acf46e)

![image](https://github.com/user-attachments/assets/b113220e-687b-4bb0-80bf-3d9bdf1cbff7)

![image](https://github.com/user-attachments/assets/6c80f091-61c5-4d66-bc8a-d00dea664494)

A continuación se muestra como se consumen las API en angular

Este endPoint es el que se consume, para lograr la comunicación entre el endPoint que se expone y Angular que lo consume es importante habilitar CORS
![image](https://github.com/user-attachments/assets/3c9d8055-d09e-484c-867c-197c68e13ecc)



![image](https://github.com/user-attachments/assets/75605e9c-73bd-4224-b1ef-a1fcf38be905)

En Angular 14 y urilizando el editor de código VS-Code vemos que se consume el Api de "Iniciar Sesión"

![image](https://github.com/user-attachments/assets/627635bb-da13-4885-b16a-8bf2b32c9a54)

Y se observa que se consumen las demás Api que son: Guardar, Editar y eliminar, y vemos que la aplicación en angular se ejecuta en el puerto 4200 de localhost

![image](https://github.com/user-attachments/assets/ac46493a-cde8-4ca0-ace2-44a268e5b2ad)

Finalmente para ejecutar la aplicación, lo primero es que se debe ejecutar la aplicación en .Net-Core como se ve a continuación, ya que si no se ejecuta no consumura las APIS RESTfull en Angular 14
Se muestra a contunuación .Net-Core y se ejecuta presionando la tecla "F5" o presionando elboton "Continuar" ubicado en la parte superior, donde esta subrayado en color rojo

![image](https://github.com/user-attachments/assets/032092e9-9493-4030-9511-559b56102aea)

Luego estando en el editor de código VS-Code se ejecuta la aplicación escribiendo el siguiente comando "ng serve" como se ve a continuación

![image](https://github.com/user-attachments/assets/48efcf60-ce37-42ab-8088-ec3d3504e589)


Y listo, vemos que la aplicación se ejecuta en el puerto 4200 como se ve a continuación

![image](https://github.com/user-attachments/assets/3c5fb3f0-7eb5-43cd-b711-82895747e633)




Tarea: Asignación No. 5 Desarrollo del backend de la Plataforma

Uno de los requerimientos era configurar base de datos SQL, en este caso elegí SQL Server Versión 2019, y se puede apreciar el modelo Entidad-Relación de la aplicación Ecommerce

![image](https://github.com/user-attachments/assets/1c67c5b8-7d6b-44b4-b53b-6d8c9697908f)

Acá se ovserva el script de la creación de la base de datos con las tablas que contendra la aplicación

![image](https://github.com/user-attachments/assets/999a3294-8f6c-4f98-878e-d608f637ee8e)

![image](https://github.com/user-attachments/assets/89cdbb6c-03ba-4c66-8572-a7d719c2056d)

![image](https://github.com/user-attachments/assets/05d27933-787f-453c-9d85-01484d5544a3)

Acá se muestran las ejecuciones de algunas de las tablas ya creadas anteriormente y con datos que fueron mostrados en la aplicación de las actividades anteriores

![image](https://github.com/user-attachments/assets/75f54f98-0314-494b-8f50-e43d134319d9)

![image](https://github.com/user-attachments/assets/6e58525d-e9e2-4f47-965c-6b4705cf86de)


 

Como se solicito en uno de los requerimientos, continuación se muestra parte del código de las Apis en .Net-Core, en este caso las API RESTful de productos para Crear, Editar, y eliminar productos que posteriormente serán consumidos desde la aplicación de Angular

![image](https://github.com/user-attachments/assets/510384b3-ce4d-4629-b205-9ca45437d85b)

Para listar y obtener los productos

![image](https://github.com/user-attachments/assets/56089bdc-61ba-4d7a-8893-2a58bfa59353)

Para crear o guardar productos

![image](https://github.com/user-attachments/assets/7f99f44f-7879-43ba-a2f2-76069831ab92)

Para editar productos

![image](https://github.com/user-attachments/assets/c34317a8-ecbf-4306-ac77-8ed7a0b8ffef)

Para eliminar productos

![image](https://github.com/user-attachments/assets/0c6422e4-e5f4-4c0a-b880-a55c9bdc85db)




Y para probar las funcionalidades CRUD (Crear, Leer, Actualizar, Eliminar) para los productos, se realiza de la siguiente manera

Se presiona en el botón "Nuevo producto", lo cual abre una ventana modal para ingresar un producto y se le da al botón "Guardar", como se aprecia en la imagen

![image](https://github.com/user-attachments/assets/63f27729-2628-4ce6-82b8-9d38f8e99300)

Y se observa que quedo registrado el prpoducto exitosamente tanto en la aplicación como en base de datos, como se aprecia en la imagen

![image](https://github.com/user-attachments/assets/b88bb1f2-c67b-4927-9a22-b08c3719d53d)
![image](https://github.com/user-attachments/assets/0b29ff08-adff-46e0-a27d-03b9053a5238)

Para editar un producto, en este caso el que acabamos de crear, se presiona la imagen del lápiz y se abre la ventana modal con el producto ya seleccinado para su edición

![image](https://github.com/user-attachments/assets/f29ebde3-45e0-481d-be86-65f5201342be)


El producto se edita por un computador portátil como se ve en la imagen
![image](https://github.com/user-attachments/assets/d40a9bcb-f628-4d99-9602-b3fadce7a083)

Y vemos que el producto fue editado exitosamente como lo notifica el mensaje de alerta, de igual manera en base de datos

![image](https://github.com/user-attachments/assets/893e51d9-b4f6-49cd-b00d-788e86af35cd)
![image](https://github.com/user-attachments/assets/a8660762-427b-4eaf-8fcc-348c27482b96)

Para eliminar un producto se realiza de la siguiente manera, en este caso eliminaremos el producto que agregamos y modificamos

Se selecciona el ícono de la "basura" y se abre una ventana modal y presionamos el botón eliminar

![image](https://github.com/user-attachments/assets/ab84dd8c-e46b-4479-ba8a-4b72cdc086f6)

Y se observa que el producto fue eliminado exitosamente como lo notifica el mensaje de alerta t en base de datos no aparece

![image](https://github.com/user-attachments/assets/7624f6fd-bb0b-4617-b241-a56d5c6f963c)
![image](https://github.com/user-attachments/assets/68030d86-8523-4836-b5b9-cac666c173a4)






Tarea: Asignación No. 6 Integración y Seguridad

Tal como se solicita en la tarea, se integra seguridad a la aplicación, en este caso la seguridad es por medio de JWT(Jason Web Token) de Asp.Net-Core que se ve a continuación

Se debe instalar las librerías de JWT como se ve en la imagen
![image](https://github.com/user-attachments/assets/6f7c3a16-2e48-43a7-89e9-76d24ee23b28)


Luego se crea una clase llamada"Utilidades" donde se crea un método de encriptación llamado "encriptarSHA256", esto con el fin de al registrar un usuario encripte la contraseña por motivos de seguridad
![image](https://github.com/user-attachments/assets/bff4651f-516a-4915-8ecd-5bfdaff844ac)

Se crea otro método llamado "generarJWT" que genera el token con el propósito de que cuando se loguee al iniciar sesión el usuario con las credenciales le genere un token y así tenga permitido la autorización de ingresar a las demás apis de Listar, editar, eliminar, consultar productos o pedidos
![image](https://github.com/user-attachments/assets/254eab5f-f34b-4d1c-9127-1cc3474ab8da)

En el controlador llamado "Acceso" se crea la acción de "Registrarse" como se ve en la imagen

![image](https://github.com/user-attachments/assets/6171c535-563a-4c45-af34-dddabf050e62)

Se crea la acción de "Login" con el propósito de que al iniciar sesión con las credenciales correctas le genere el token y le permita al usuario tener la autorización de acceder a las demas apis de Listar, editar, eliminar, consultar productos o pedidos
![image](https://github.com/user-attachments/assets/f75a16aa-f88f-4461-b0ff-c5adb49f8235)

Este es el controlador de Productos el cual como se ve en la imagen se coloca la palabra "Authorize" con el fin de que solo pueden acceder a esta api quien este autorizado por un token

![image](https://github.com/user-attachments/assets/afa486c0-6f34-4e24-8aa9-4d5a49de4d75)

Al realizar la prueba con la herramienta "Swagger" y "Postman" e intentar acceder a la api de Productos me arroja un mensaje de 401 que no estoy autorizado como se muestra en las imágenes

![image](https://github.com/user-attachments/assets/daf1e815-a691-41dc-94b4-0644bc8cbf51)
![image](https://github.com/user-attachments/assets/f0bf5884-efec-40de-ac4b-6bc132dd03f0)

Se procede a realizar la siguiente prueba de registrar un usuario para crearle credenciales y encriptar su contraseña 
Como se observa en la imagen la contraseña es "123456"

![image](https://github.com/user-attachments/assets/4e467c9d-88e6-44a5-bf9a-bb6263d4c60d)

Y se observa que la contraseña quedo encriptada en base de datos como se aprecia en la imagen

![image](https://github.com/user-attachments/assets/4690aa20-2dd5-4b8c-88a4-c5ffe4adef00)

Si intentamos de acceder con una contraseña diferente no arroja el token que se espera que arroje y toma el valor de "false" como se aprecia en la imagen

![image](https://github.com/user-attachments/assets/700e1767-3854-4b33-91ff-ea39cd188f54)

Si por el contrario ingresamos las credenciales correctas con la contraseña correcta, genera el token como se ve en la imagen y como se esperaba

![image](https://github.com/user-attachments/assets/26808a8a-e9fb-4217-b02e-42f3cab18a3f)

Y con el token generado ya podriamos ingresar a la api de "Productos" como se ve en la imagen, el token se ingresa en el campo señalado con una flecha en color rojo

![image](https://github.com/user-attachments/assets/2b361c66-32b3-42c5-81c1-9a342b32cd0c)

Esto sería todo por el lado de la seguridad con JWT(Jason Web Token)



SEM9 - Tarea: Asignación No. 8 Despliegue de la Plataforma e-Commerce en AWS EC2 - ENTREGA FINAL
En este caso la aplicación por ser de .Net-Core el despliegue lo realizo en Azure

Se ingresa al portal de Azure
![image](https://github.com/user-attachments/assets/a30e4a66-3224-4aad-b167-7dfaaac41586)


Se crea la suscripción en azure para realizar el despliegue
![image](https://github.com/user-attachments/assets/f72ac6f3-55df-41ef-a145-65b74588e7f2)

Luego de crear la suscripción se debe crear el "Grupo de Recursos"
![image](https://github.com/user-attachments/assets/e5c4647a-b8bc-4c22-b1eb-5d8943206dc7)

Luego de crear el grupo de recursos se crea la appWeb donde estará alojado el código
![image](https://github.com/user-attachments/assets/addf4b7a-2847-4280-95c9-dd9e0c7d603b)

Y se configura los datos para crear la aplcicación como se aprecia en la imagen
![image](https://github.com/user-attachments/assets/c6753dc0-a9ac-4acb-8cd8-c10672a0f4b1)
![image](https://github.com/user-attachments/assets/a366ae99-66fa-465d-9b19-45d9a2ba9601)
![image](https://github.com/user-attachments/assets/75692b5e-b260-403a-ae13-065d0d28e23c)

Y vemos que se creo el recurso exitosamente, es decir la app para alojar el código
![image](https://github.com/user-attachments/assets/3990a82b-49da-4b94-85c3-ff55729d70ab)

El siguiente paso es crear la base de datos SQL AZURE para alojar la base de datos creada en sql server como se ve en la imagen
![image](https://github.com/user-attachments/assets/d704686f-6d2a-41f4-af46-e74d9b58e7e0)

Luego en la plataforma visual Studio de .Net se publica la aplicación como se ve en la imagen
![image](https://github.com/user-attachments/assets/6c332275-aeb0-4f5f-8cb7-f48340216240)

Al escoger la opción de publicar automaticamente visual studio reconoce la appWeb creada en Azure con el nombre del grupo de recursos como se observa em la imagen
![image](https://github.com/user-attachments/assets/66fe147f-3f6b-4338-889d-4abe648b3e78)

Se crea el perfil de publicación como se esperaba
![image](https://github.com/user-attachments/assets/9894003b-e658-48c7-89f1-e80eaabf6ab6)


![image](https://github.com/user-attachments/assets/4446f42c-5d6f-45da-b37a-775a0dbb1a0f)

Y se presiona el botón de publicar como se ve en la imagen
![image](https://github.com/user-attachments/assets/5c207626-d4dd-4a5c-acd2-306709c1bd77)

Y vemos que la publicación fue exitosa como se aprecia en la imagen

Y se observa la URL es el dominio predeterminada de Azure donde se aloja la aplicación Web Api, que en este caso es el BACKEND 
![image](https://github.com/user-attachments/assets/7465a311-fb3b-4a5d-b7e1-957c0ef71401)

Se observa que es la misma url del dominio donde se encuentra el BACKEND
![image](https://github.com/user-attachments/assets/6d6fb60c-f6d7-47ac-ab00-4aa77eafec6c)

Ahora crearemos otro Hosting en Azure para alojar el FRONTEND, es decir la aplicación en Angular

Tal como hicimos con el anterior, se crea una appWeb como se ve en la imagen para alojar la aplicación de Angular

![image](https://github.com/user-attachments/assets/12c693eb-299a-48f9-a44a-79250bc74a05)

Esta aplicación recibe el nombre de AngularBiu como se ve en la imagen
![image](https://github.com/user-attachments/assets/d48e883b-32d6-486f-83b8-6e7b925010fc)

Y se observa que se crea el alojamiento como se ve en la imagen, para alojar la eplicación de Angular 15
![image](https://github.com/user-attachments/assets/5f57d4ae-1688-4116-bc1b-d7c6f49d6e49)

Si presionamos el enlace de la url señalada em color rojo como se ve en la imagen
![image](https://github.com/user-attachments/assets/64b40f3e-b126-432c-b30d-89ac44ded81a)

Vemos que nos lleva a una página donde aún no hay nada, eso es porque ya esta creado el alojamiento pero la aplicación no hay contenido ya que la aplicación no ha sido publicada

![image](https://github.com/user-attachments/assets/2c606e66-49f3-45f1-b30e-39cd88a94c51)

La aplicación angular es realizada en VisualCode como se ve en la imagen y para el despliegue de la app se escoje la appWeb donde se alojará como se ve en la imagen

![image](https://github.com/user-attachments/assets/85cdcbe5-ad0f-4863-940d-40ba7147ec26)

Como se observa en la imagen se elije la opción "Deploy to WebApp"
![image](https://github.com/user-attachments/assets/419f5f78-5ffc-4b00-8e45-b2cbbed084d2)

Y vemos que se publica exitosamente como se esperaba, se puede ver la URL del dominio predeterminado creado por Azure donde está alojada la aplicación de Angular

![image](https://github.com/user-attachments/assets/281afdd3-23bc-4ef5-b30c-b554cdef667b)
![image](https://github.com/user-attachments/assets/171773d8-72d7-4066-a4a5-ceac9aa76990)


Este es el módulo de usuarios, como se puede observar , el despliegue del Front de Angular fue exitosamente publicado al igual que el Backend publicado anteriormente

![image](https://github.com/user-attachments/assets/1379f720-c8c7-4835-867a-c41d2a0651be)

Módulo productos

![image](https://github.com/user-attachments/assets/a8c4466d-0c19-4fe5-a018-e5dfa888d0df)

Módulo ventas

![image](https://github.com/user-attachments/assets/4f29e8bb-ca76-4b98-96ae-ab621a3bee0e)

Historial de Ventas

![image](https://github.com/user-attachments/assets/b88c6d53-5256-4d2a-b901-250ff2e75a71)

Módulo reportes

![image](https://github.com/user-attachments/assets/41b3a71e-17da-42f3-bdc7-ec3a8e15e2d3)

Esto sería todo por el lado del despliegue a Azure

Para concluír se cumple con el objetivo de publicar las 2 aplicaciones, la de Backend y la del lado Front en Azure, se muestra el paso a paso desde la creación de la suscipción, la creación del grupo de recursos y la creación de las appWeb donde se alojan las aplicaciones. Para finalizar se eliminarán todos los recuros ya que Azure cobra por uso ya que no estoy usando una cuenta gratuita. Cuando se crea por primera vez la cuenta Azure obsequia 200 dolares por 30 días para uso de cualquier recurso, sin embargo ya esos 200 dólares se agotaron en el uso de otras aplicaciones que habia sibido meses antes, lo cual me llevo a utilizar la versión paga para efectos de esta prueba. Es por eso que ya habiendo documentado esta prueba eliminaré todos los recuros.























































