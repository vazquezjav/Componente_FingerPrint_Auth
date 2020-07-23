# Pagina Oficial Documentacion
https://ionicframework.com/docs/native/android-fingerprint-auth

# Implementacion 
Agregar los modulos dentro de la pagina donde quisieramos llamar a nuestro coponente 
![All Text](Imagenes/module.PNG?raw=true "Modulo") 

En la pagina html tendremos que llamar al componente de acuerdo a como lo definamos breve a la creacion del componente, en este caso se le esta pasando 
como parametro un icono a nuestro componente, y definimos tambien  **event** que nos permitira obtener y mostrar lo que nos devuelve el componente
![All Text](Imagenes/inicio.jpg?raw=true "Inicio") 

#
Asi lo tendriamos definido el boton dentro de nuestro home que nos ayudara a llamar al componente 
![All Text](Imagenes/homeHTML.PNG?raw=true "Home") 

Una vez que presionemos el boton nos aparecera la opcion de autentificarnos, aqui ya depende de las especificaciones de nuestro dispositivo,
este componente automaticamente detecta si el telefono cuenta con sensor de huella dactilar, y si no es caso se puede hacer **use backup**
esto nos permitira autenticarnos co nuestro PIN o Password que tengamos en nuestro telefono 

![All Text](Imagenes/elejirDesbloqueo.jpg?raw=true "Elejir") 

Al ingresar con nuestra huella la detecta es la que se encuentra registrada en el telefono 

![All Text](Imagenes/huellaConfirmada.jpg?raw=true "Confirmacion Huella") 

Y por detras lo que el componete hace, es devolvernos una alerta del estado de la autentificacion, es decir si el acceso fue correcto con un mensaje 
que se logro autenticar, si en algun punto cancela este paso de autenticarse, solo para este caso se le programa que se cierre la aplicacion pero ya
se podria enviar algun mensaje con una alerta e incluso se podria redirijir a una nueva pagina 
![All Text](Imagenes/resultadoComponente.jpg?raw=true "Resultadp") 
