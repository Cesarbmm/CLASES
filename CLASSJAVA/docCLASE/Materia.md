# <span style = "color: darkred">CLASE 03</span>
# Programación Orientada a Objetos (POO)

La Programación Orientada a Objetos (POO) es un paradigma de programación que se basa en el concepto de "objetos", los cuales pueden contener datos en forma de campos y métodos para manipular esos datos. Los objetos interactúan entre sí a través de mensajes.

## Características de la POO:

- **Abstracción:** Permite representar entidades del mundo real como objetos con características y comportamientos.
- **Encapsulamiento:** Oculta los detalles internos de un objeto y expone solo la interfaz para interactuar con él.
- **Herencia:** Permite que una clase herede atributos y métodos de otra clase.
- **Polimorfismo:** Permite que objetos de diferentes clases se comporten de manera similar a través de una interfaz común.

# Historia de Java

Java es un lenguaje de programación desarrollado por Sun Microsystems en 1995. Fue creado por James Gosling y su equipo con el objetivo de ser un lenguaje simple, robusto y portátil. Algunos hitos importantes en la historia de Java incluyen:

- 1991: Inicio del proyecto Green para desarrollar un lenguaje de programación para dispositivos electrónicos.
- 1995: Lanzamiento oficial de Java 1.0.
- 2009: Adquisición de Sun Microsystems por parte de Oracle Corporation.
- Actualmente, Java es uno de los lenguajes de programación más populares y ampliamente utilizados en el mundo, especialmente en el desarrollo de aplicaciones empresariales y en la programación para dispositivos móviles con Android.

# ¿Cómo funciona JAVA?

Java es un lenguaje de programación de alto nivel y orientado a objetos, diseñado para ser portátil, seguro y robusto.
Java utiliza un enfoque de compilación y ejecución. El código fuente escrito en archivos ".java" se compila a bytecode, que es un formato de código de máquina para la plataforma Java. Luego, este bytecode puede ser ejecutado en cualquier entorno que tenga una implementación de la máquina virtual Java (JVM).

### Aplicaciones de Java

Java se utiliza en una amplia variedad de aplicaciones, desde el desarrollo de aplicaciones web hasta aplicaciones de escritorio y móviles. Su capacidad de ejecutarse en múltiples plataformas lo hace popular en empresas y proyectos de software.

### Sintaxis de Java

La sintaxis de Java es similar a la de otros lenguajes como C++ y C#, lo que facilita la transición para los desarrolladores familiarizados con estos lenguajes. Java utiliza llaves "{}" para delimitar bloques de código y punto y coma ";" al final de las declaraciones.

### Tipos de Datos y Reglas del Lenguaje Java

Java tiene tipos de datos primitivos como `int`, `double`, `boolean`, etc., y tipos de datos de referencia como clases y arrays. 

# Estructura del Código Java

Un programa en Java está compuesto por una serie de elementos, entre los que se incluyen:

- **Clases y Objetos:** Las clases son la base de la programación en Java y se utilizan para definir objetos y sus comportamientos.
- **Métodos:** Los métodos son bloques de código que realizan una tarea específica y pueden ser invocados desde otros lugares del programa.
- **Ámbitos:** Mas utilizados public, private.
- **Variables:** Se utilizan para almacenar datos temporales dentro del programa.
- **Sentencias de Control:** Como `if`, `else`, `for`, `while`, que permiten controlar el flujo de ejecución del programa.
- **Paquetes:** Se utilizan para organizar y agrupar clases relacionadas en Java.
- **Comentarios:** Se pueden agregar comentarios en el código para documentar su funcionamiento.
 
![Estructura](https://edteam-media.s3.amazonaws.com/community/original/5d5f1dcf-05cd-438f-9279-e185a7523ee1.jpg)

## <spa style = "color: green">Códigos</span>
### Hola mundo

```
public class App {
    public static void main(String[] args){
        System.out.println("Hello, World!");
    }
}
```
### Uso del for
 - for (inicio;condicion;incremental){}
# 1
```
public class App {
    public static void main(String[] args) {
        int n= 10;
        for (int i=0; i<10; i++)
        System.out.println(i);
    }
}

```
# 2
```
public class App {
    public static void main(String[] args) {
        int n= 10;
        for (int i=2; i<10; i+=2)
        System.out.println(i);
    }
}

```
# 3
```
public class App {
    public static void main(String[] args) {
        int n=10;
        for(int i=2;i<10;i+=2)
        if (i==6) {System.out.println("Hay un seis");
        }else{
            System.out.println(i);
        }
        
    }
}

```
### Operador ternario: Ahorra lineas de codigo
```
public class App {
    public static void main(String[] args) {
        int n=10;
        for(int i=2;i<10;i+=2)
        System.out.println((i==6)?"hay un seis":i);
        
    }
}
```
# <span style = "color: darkred">CLASE 04</span>

## Bucles 
Siempre se crea un readme por defecto para documentar nuestro codigo.
El archivo App.java sale por defecto.
Aplicacion: Buclefor.java
            BucleWhile.java
            BucleDoWhile.java
Java projects: version java, librerias, librerias externas, src, archivo java.
Aqui puedo crear una clasem interfaz, record, paquete, etc
Crear clase: BucleFor.java
Bucle que haga: +-+-+-+-+
```
public class BucleFor {
    public void SignoAlterno(){
        for(int i=1;i<=15;i++){
            if (i%2==0) {
                System.out.println("-");
            }else{
                System.out.println("+");
                
            }
        }
    }

}
```
Para llamar al bucle, se llama instansacion, creo mi variable e instacio con la palabra reservada NEW (esto es dar vida a nuestro tipo de dato) pido un nuevo espacio de memoria, nos sirve para no tener que gastar memoria mientras continuamos con nuestro codigo base.
#### Poner siempre el nombre de la variable adecuadamente
Powermode
javac App.java -d 'C:\Users\pc\OneDrive - Escuela Politécnica Nacional\Escritorio\U\2. SEMESTRE\PROGRA II\Work directory\CLASSJAVA1\TWO\bin' 
// para mandar a la bin

# <span style = "color: darkred">CLASE 05</span>

## Bucles 02

Son bloques que se deben ejecutar en la App.

Camellito: signoAlterno //metodo
Ola: BucleFor   //nombre clase
- Metodo
```
public class BucleFor {
    //metodo: + - + - + - + - + - + -
    public void signoAlterno(){
        for(int i=1;i<10;i++){
            if(i%2==0){
                System.out.println("-");
            }else{
                System.out.println("+");
            }
        }

    }

}
```
Luego debo llamar en el main
S+ALT+ABAJO DUPLICO LA LINEA
- Funcion principal main
```
public class App {
    public static void main(String[] args) throws Exception {
        BucleFor bf; //declare la variable
        bf = new BucleFor(); //instanciar la variable

        bf.signoAlterno(); //llamo al metodo a traves de la variable
        
    }
}
```




