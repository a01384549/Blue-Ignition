# Instrucciones para Operar el Router

## Primera vez usando el Router

### Requisitos
- Usar Google Chrome
- Descargar los drivers

---

### **Drivers**

Para descargar los drivers hay que entrar a la [pagina de inventables de descargas](https://easel.inventables.com/downloads).

![Vista de la pagina de descarga de drivers de inventables](img/drivers.png)

Dar click en descargar y ejecutar el archivo.

---

### **Easel**

El softare para el router se llama [Easel](https://www.inventables.com/technologies/easel). Para usarlo hay que entrar con una cuenta en el siguiente link. https://easel.inventables.com/users/sign_in

Una vez en la pagina hay que crear una nueva cuenta

![Vista de la pagina para crear una nueva cuenta](img/createAcc.png)

Ya creada la pagina nos encontramos con el siguiente menu. Seleccionamos proyectos y creamos uno nuevo.

![Vista de la pagina de inicio despues de crear una cuenta](img/selectProjects.png)
![Vista de la pagina de proyectos](img/newProject.png)

Despues de crear el proyecto nos encontramos con la pagina "principal" por asi decirlo. Aqui es donde se configura el router y el diseño.

![Pagina principal de un proyecto de easel](img/dashboard.png)

Hay que seguir varios pasos antes de poder empezar a cortar una pieza

1. Cambiar las unidades de pulgadas a milimetros
![Vista de pagina para cambiar las medidas de pulgadas a milimetros](img/changeMeasure.png)

2. Configurar el Router. Para eso entramos en el menu de **"Machine"** >  **"Set up new machine"**
![Vista de pagina para seleccionar el menu de Machine](img/clickMachine.png)
![Boton para set up new machine](img/setupMachine.png)

3. Seleccionar el modelo de router. En este caso el modelo del router es el ***X-Carve (pre-November 2021)***.
![Modelo del router](img/machineModel.png)

4. Ingresar las especificaciones del router. El router tiene las siguientes especificaciones:
- Motion **Controller: X-Controller**
- Rail size: **1000mm x 1000mm**
- Z Axis: **Belt Drive w/ ACME threaded rod**
- Spindle: **Dewalt 611**
- Belts: **2GT 6mm**
- No cuenta con **"Dust shoe"**
![Detalles del router](img/machineSettings.png)

5. Despues de cofirmar las configuraciones hay que conectar el _X-Controller_ del router a la computadora. Para esto usamos un cable de ***USB tipo B***
![Vista de la pagina esperando la coneccion con el router](img/connectingXcarve.png)
![Vista del X-Controller de frente](img/xControllerOff.jpeg)

6. Una vez que se conecta la maquina, puede que aparezca este menu. Seleccionas la opcion de ***New Machine***

![Vista de la pagina para seleccionar la opcion de New Machine](img/newMachine.png)

7. Luego, hay que confirmar que la configuracion este correcta, para eso utilizamos los botones para mover el router en todos sus ejes y confirmar que funcione de manera correcta.

![Vista de la pagina para confirmar los ejes](img/testAxis.png)
![Vista del Router](img/moverEjes.jpeg)

8. Una vez confirmado que los ejes se mueven de manera correcta, confirmas que todos esten funcionando y continuas.

![Pantalla de confirmacion de los Ejes](img/confirmAxis.png)

9. El router si cuenta con **"Homing Switches"**. Son switches que detectan cuando el taladro ha llegado a un extremo del eje y automaticamente lo detiene. 
Despues de confirmar que si cuenta con switches, hay que asegurarse que en la secuencia de **"Homing"** todo salga bien.

![Pagina para seleccionar la opcion de homing switches](img/homingConfirm.png)

En el caso de alguna situacion con el router durante esta secuencia ***SE DEBE DETENER EL ROUTER TANTO EN LA PAGINA COMO EN EL PARO DE EMERGENCIA Y SOLUCIONAR EL PROBLEMA ANTES DE PROBAR DE NUEVO.***. 

![Cuadro y boton donde se puede cancelar el proceso de homing](img/homingCancel.png)

Una vez terminada la secuencia, el taladrio estaria posicionado en la esquina inferior izquierda.

![Vista del router en persona una vez que la secuencia de homing haya terminado](img/homePosition.jpeg)

10. El router ***NO*** cuenta con el **"Z-Probe"**. 

![Imagen del sitio para confirmar si se cuenta con un Z-Probe](img/zProbe.png)

11. Terminado el proceso de configuración, seleccionamos **"Finish"**. Para despues abrir el proyecto que ya se habia creado.

![Boton para finalizar el setup](img/finishSetup.png)
![Vista de la pagina para abrir un nuevo proyecto](img/openProject.png)

- Dentro del proyecto encontramos varias herramientas las cuales se pueden dividir en 3 categorias:
  - La barra de figuras
  - La barra de menu
  - La barra de corte

![Alt text](img/projectView.png)

## Pasos para cortar
