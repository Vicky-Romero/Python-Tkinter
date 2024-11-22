#proyecto sobre enviar mail
##modificamos un código para agregar más o nuevas cosas

este proyecto consiste en forkear un repositorio con varios códigos y elegir uno para modificarlo.
En este caso yo tome el código de enviar un mail y le cambie el logo por uno hecho por mí, también le cambie algunas líneas de código para tener
un menu de opciones, el cual contiene tres mails, en este menu se puede ingresar cualquier mail aparte de las tres opciones de mail.

![Imagen del logo](output/image/gmail.png)

![Vistazo del programa](output/image/captura.png)

En el código, importe de tkinter un ttk (Tkinter Themed Widgets) que ayuda a la infaz gráfica para poder agregar el combobox (ingresar un mail y al
mismo tiempo tener un option menu incluido).En el entry del destinatario para ingresar el mail le agregue el combobox.
parte del código: combobox_destinatarios = ttk.Combobox
Aparte de esos cambios, también agregue en el remitente mí mail y una contraseña para que me permita poder enviar un correo en mi nombre desde el 
programa al destinatario. (no logre hacer que mandara el mail de forma anonima)
Luego de eso no realice más cambios importantes, el último cambio fue el del nombre de la ventana, antes era "ENVIAR CORREO VIA MAIL" lo cambie a
"Gmail". 

Fue un trabajo corto pero llevo más tiempo del que yo tenía planeado, ya que al cambiar algunas líneas de código me daba error en otro lado. 
