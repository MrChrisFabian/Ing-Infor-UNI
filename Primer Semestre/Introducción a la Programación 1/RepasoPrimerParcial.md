# Repaso Introducción a la programación (1er Parcial-2023)
## Libreria Robot.
Es una libreria que se utiliza de forma didactica para la introducción a la programación orientada a objetos con java para los nuevos alumnos.
Utiliza el (Java Development Kit) Open JDK 1.8
Solamente importaremos las librerias que necesitamos y que son con las que estuvimos trabajando ultimamente, existen mas clases pero es de buena practica importar solo las necesarias.
``````java
import uni.robot.Robot;
import uni.robot.Mundo;
``````
### Clases Disponibles en la Libreria:
- Mundo: Clase encargada de generar el objeto mundo con todos sus metodos posee, "cuadras","avenidas", representadas en cuadriculas, en estas cuadriculas podemos agregar conos con los robots quienes se crean y viven en el contexto del mundo.
- Robot: Es el personaje principal de toda la libreria el puede moverse por todo el mundo, agregar y quitar conos, interactuar con otros robots entre otras cosas.
### Mundo
#### Constructor del Mundo.
Cuando creamos un objeto de tipo Robot deberemos asignarle los atributos necesarios los cuales estan definidos en su constructor y son:
- Nombre del Robot que aparecera en la parte superior de la ventana.
- Cantidad de Filas que poseera el mundo.
- Cantidad de Columnas que poseera el mundo.

``````java
// Constructor del Mundo Original
public Mundo(String nombre){

}
// Creación de un objeto de tipo Mundo
Mundo nombreDeLaVariable = new Mundo("Mundo de Caramelo",10,15); 
``````
#### Metodos del Mundo.
``````java
mundo.getCantidadFilas();
mundo.getCantidadColumnas();
mundo.mostrarMensaje(String mensaje);

``````
### Robot
#### Constructor del Robot.
Cuando creamos un objeto de tipo Robot deberemos asignarle los atributos necesarios los cuales estan definidos en su constructor y son:
- El mundo donde se iniciara el robot;
- La Fila del mundo donde se iniciara;
- La columna del mundo donde se iniciara el robot;
- Su dirección, la dirección tiene los puntos cardinales y cada punto cardinal tiene un numero asignado como una constante,(NORTE=0;OESTE=1;SUR=2;ESTE=3;).
- Capacidad de almacenamiento de Conos.
- Cantidad de conos disponibles en ese momento.

```java
//Constructor original del Robot
public Robot(Mundo mundo, int fila, int columna, int dirInicial, int CantMaxima, int CantConos){

}
//Utilización a la hora de Crear un objeto de tipo Robot
Robot nombreDeLaVariable = new Robot(mundo,0,0,Robot.NORTE,100,10);
```
Esto es un ejemplo Generico del uso del constructor, tu lo puedes utilizar de la manera que mas te convenga.
#### Metodos Principales del Robot.
Cuando ya creaste un objeto robot puedes usar los metodos con su nombre seguido de un punto que instancia todos los metodos 
``````java
chris.avanzar();
``````
Enlistaremos todos los metodos utilizando que el contexto sera dentro de una clase que hereda del robot.
``````java
this.ponerCono():
this.girarIzquierda();
this.girarDerecha();
this.quitarCono();
this.hayCono();
this.getFila();
this.getColumna();
this.avanzar();
this.recogerCono();
this.guardarCono();
this.ponerCono();
this.hayRecipienteCono();
this.cantidadConos();
this.getCantidadMaximaConos();
this.getDireccion();
``````
##### Herencia
cuando estas creando una nueva clase del Robot que herede metodos y aunque añadas nuevos atributos al constructor puedes usar los metodos del robot Original porque los estas heredando ejemplo de esto.
``````java
public RobotChipero extends Robot{
    public RobotChipero(Mundo m, int fila,int colum,int direc,int capbolsa,int cantbolsa, int energia){
        //el super lo que hace es conectar los atributos de la nueva clase y los conecta con los de la clase padre
        super(Mundo m, int fila, int colum, int direc, int capbolsa, int cantbolsa);
        //Asignamos que el valor de la variable que creamos luego sea igual al del atributo de la clase
        this.energia = energia;
    }
    //Si necesitamos agregar un nuevo atributo a nuestra nueva clase RobotChipero
    private int energia;
}
``````
