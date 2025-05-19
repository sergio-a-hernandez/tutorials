### Introducción a la programación con Java, C# y PHP: 3 en 1

1. Introducción a la programación
2. Variables y tipos de datos
3. Estructuras de control (if, else, switch)
4. Bucles (for, while, do-while)
5. Funciones y procedimientos
6. Arreglos y listas
7. Programación orientada a objetos (clases y objetos, herencia, polimorfismo)
8. Manejo de excepciones
9. Entrada y salida de datos (lectura desde teclado, escritura en archivos)
10. Manipulación de cadenas de texto
11. Trabajo con fechas y horas
12. Manipulación de archivos
13. Interacción con bases de datos

### Introducción a la programación

La programación es el arte de crear instrucciones que una computadora puede entender y ejecutar para realizar tareas específicas. A través de la programación, puedes dar vida a tus ideas, resolver problemas y crear herramientas útiles.

#### ¿Qué es la programación?

En su esencia, la programación consiste en escribir un conjunto de instrucciones paso a paso que le dicen a una computadora qué hacer. Estas instrucciones se escriben en lenguajes de programación, que son idiomas específicos diseñados para comunicarse con las computadoras de manera eficiente.

La programación es una habilidad poderosa y versátil que se utiliza en una amplia variedad de campos, desde el desarrollo de software hasta la ciencia de datos, la inteligencia artificial, el diseño web y mucho más.

#### ¿Por qué aprender a programar?

Aprender a programar ofrece una serie de beneficios:

1. **Resolución de problemas**: La programación te enseña a descomponer problemas complejos en pasos más pequeños y manejables, lo que facilita su resolución.

2. **Creatividad**: La programación te brinda la capacidad de crear nuevas aplicaciones, juegos, herramientas y más. Es una forma de expresión creativa donde tu imaginación es el límite.

3. **Oportunidades profesionales**: La demanda de profesionales de la programación sigue creciendo en una variedad de industrias. Aprender a programar puede abrirte puertas a emocionantes oportunidades laborales.

4. **Autonomía**: Con conocimientos de programación, puedes crear tus propias soluciones a problemas, en lugar de depender de herramientas preexistentes.

#### ¿Qué necesitas para empezar?

Para comenzar a programar, necesitas:

- Una computadora con acceso a internet.
- Un editor de texto o un entorno de desarrollo integrado (IDE) para escribir y ejecutar tu código.
- Determinación y paciencia. La programación puede ser desafiante en ocasiones, pero con práctica y perseverancia, puedes superar cualquier obstáculo.

En este tutorial, exploraremos los conceptos fundamentales de la programación utilizando tres lenguajes populares: Java, C# y PHP. Estos lenguajes son ampliamente utilizados en la industria y proporcionan una base sólida para aprender a programar.

### Variables y Tipos de Datos

Las variables son elementos fundamentales en la programación, utilizadas para almacenar y manipular datos en un programa. Cada variable tiene un nombre único y un tipo de datos asociado que determina qué tipo de valores puede contener.

#### Variables

En programación, una variable es un contenedor con un nombre que se utiliza para almacenar datos. Puedes pensar en una variable como una caja etiquetada donde puedes guardar diferentes tipos de información.

#### Declaración de Variables

Para declarar una variable, debes especificar su tipo de datos y su nombre. Dependiendo del lenguaje de programación que estés utilizando, puede haber diferencias en la sintaxis, pero el concepto básico es el mismo.

**Ejemplo en código:**

```java
// Java
int edad; // Declaración de una variable de tipo entero llamada "edad"
double altura; // Declaración de una variable de tipo decimal llamada "altura"
String nombre; // Declaración de una variable de tipo texto llamada "nombre"
```

```csharp
// C#
int edad; // Declaración de una variable de tipo entero llamada "edad"
double altura; // Declaración de una variable de tipo decimal llamada "altura"
string nombre; // Declaración de una variable de tipo texto llamada "nombre"
```

```php
// PHP
$edad; // Declaración de una variable llamada "edad"
$altura; // Declaración de una variable llamada "altura"
$nombre; // Declaración de una variable llamada "nombre"
```

#### Tipos de Datos

Los tipos de datos definen qué tipo de valores puede contener una variable. Los lenguajes de programación suelen tener una variedad de tipos de datos integrados, como enteros, decimales, texto y booleanos.

**Algunos tipos de datos comunes incluyen:**

- **Enteros (int o integer)**: Números enteros sin parte decimal, como -1, 0, 1, 2, etc.
- **Decimales (float o double)**: Números con parte decimal, como 3.14, 2.5, -0.75, etc.
- **Texto (string)**: Secuencias de caracteres, como "Hola mundo", "123", "texto", etc.
- **Booleanos (bool)**: Valores que representan verdadero (true) o falso (false).

#### Asignación de Valores a Variables

Una vez que has declarado una variable, puedes asignarle un valor utilizando el operador de asignación (=).

**Ejemplo en código:**

```java
// Java
edad = 25; // Asignación de un valor de tipo entero a la variable "edad"
altura = 1.75; // Asignación de un valor de tipo decimal a la variable "altura"
nombre = "Juan"; // Asignación de un valor de tipo texto a la variable "nombre"
```

```csharp
// C#
edad = 25; // Asignación de un valor de tipo entero a la variable "edad"
altura = 1.75; // Asignación de un valor de tipo decimal a la variable "altura"
nombre = "Juan"; // Asignación de un valor de tipo texto a la variable "nombre"
```

```php
// PHP
$edad = 25; // Asignación de un valor a la variable "edad"
$altura = 1.75; // Asignación de un valor a la variable "altura"
$nombre = "Juan"; // Asignación de un valor a la variable "nombre"
```

En este tutorial, hemos aprendido sobre variables y tipos de datos en programación. Las variables nos permiten almacenar y manipular datos en nuestros programas, mientras que los tipos de datos determinan qué tipo de valores pueden contener estas variables. ¡Continuemos nuestro viaje de aprendizaje de programación!

### Estructuras de Control (if, else, switch)

Las estructuras de control son herramientas fundamentales en programación que te permiten controlar el flujo de ejecución de un programa. Las estructuras de control más comunes son las instrucciones condicionales, como `if`, `else` y `switch`, que te permiten tomar decisiones basadas en condiciones específicas.

#### Instrucción `if`

La instrucción `if` te permite ejecutar un bloque de código si se cumple una condición determinada.

**Sintaxis:**
```java
// Java
if (condicion) {
    // Bloque de código que se ejecuta si la condición es verdadera
}
```
```csharp
// C#
if (condicion) {
    // Bloque de código que se ejecuta si la condición es verdadera
}
```
```php
// PHP
if (condicion) {
    // Bloque de código que se ejecuta si la condición es verdadera
}
```

#### Instrucción `else`

La instrucción `else` te permite ejecutar un bloque de código alternativo si la condición del `if` no se cumple.

**Sintaxis:**
```java
// Java
if (condicion) {
    // Bloque de código que se ejecuta si la condición es verdadera
} else {
    // Bloque de código que se ejecuta si la condición es falsa
}
```
```csharp
// C#
if (condicion) {
    // Bloque de código que se ejecuta si la condición es verdadera
} else {
    // Bloque de código que se ejecuta si la condición es falsa
}
```
```php
// PHP
if (condicion) {
    // Bloque de código que se ejecuta si la condición es verdadera
} else {
    // Bloque de código que se ejecuta si la condición es falsa
}
```

#### Instrucción `switch`

La instrucción `switch` te permite seleccionar uno de varios bloques de código para ejecutar, según el valor de una expresión.

**Sintaxis:**
```java
// Java
switch (expresion) {
    case valor1:
        // Bloque de código para el valor1
        break;
    case valor2:
        // Bloque de código para el valor2
        break;
    default:
        // Bloque de código por defecto
}
```
```csharp
// C#
switch (expresion) {
    case valor1:
        // Bloque de código para el valor1
        break;
    case valor2:
        // Bloque de código para el valor2
        break;
    default:
        // Bloque de código por defecto
}
```
```php
// PHP
switch ($expresion) {
    case $valor1:
        // Bloque de código para el valor1
        break;
    case $valor2:
        // Bloque de código para el valor2
        break;
    default:
        // Bloque de código por defecto
}
```

En este tutorial, hemos explorado las estructuras de control `if`, `else` y `switch`, que te permiten tomar decisiones en tus programas en función de condiciones específicas. Estas estructuras son esenciales para el desarrollo de software y te ayudarán a escribir programas más dinámicos y flexibles. ¡Sigue practicando y experimentando con estas herramientas!

### Bucles (for, while, do-while)

Los bucles son estructuras de control que te permiten repetir un bloque de código múltiples veces. Son útiles cuando necesitas ejecutar una tarea varias veces sin tener que repetir el código manualmente.

#### Bucle `for`

El bucle `for` es útil cuando sabes exactamente cuántas veces quieres repetir una acción. 


**Sintaxis:**
```java
// Java
for (inicio; condicion; incremento) {
    // Bloque de código a repetir
}
```
```csharp
// C#
for (inicio; condicion; incremento) {
    // Bloque de código a repetir
}
```
```php
// PHP
for (inicio; condicion; incremento) {
    // Bloque de código a repetir
}
```

#### Bucle `while`

El bucle `while` se ejecuta mientras una condición dada sea verdadera.

**Sintaxis:**
```java
// Java
while (condicion) {
    // Bloque de código a repetir
}
```
```csharp
// C#
while (condicion) {
    // Bloque de código a repetir
}
```
```php
// PHP
while (condicion) {
    // Bloque de código a repetir
}
```

#### Bucle `do-while`

El bucle `do-while` es similar al bucle `while`, pero la condición se evalúa al final del bucle, lo que garantiza que el bloque de código se ejecute al menos una vez.

**Sintaxis:**
```java
// Java
do {
    // Bloque de código a repetir
} while (condicion);
```
```csharp
// C#
do {
    // Bloque de código a repetir
} while (condicion);
```
```php
// PHP
do {
    // Bloque de código a repetir
} while (condicion);
```

#### Ejemplo de Uso

Veamos un ejemplo simple de cómo se puede utilizar un bucle para imprimir los números del 1 al 5:

**Ejemplo en código:**
```java
// Java
for (int i = 1; i <= 5; i++) {
    System.out.println(i);
}
```
```csharp
// C#
for (int i = 1; i <= 5; i++) {
    Console.WriteLine(i);
}
```
```php
// PHP
for ($i = 1; $i <= 5; $i++) {
    echo $i . "\n";
}
```

En este ejemplo, utilizamos un bucle `for` para imprimir los números del 1 al 5 en cada uno de los lenguajes. Sin embargo, la sintaxis puede variar ligeramente entre los lenguajes, pero el concepto básico sigue siendo el mismo: ejecutar un bloque de código repetidamente según una condición dada. Los bucles son herramientas poderosas que te permiten automatizar tareas repetitivas en tus programas.

### Funciones y Procedimientos

Las funciones y los procedimientos son bloques de código reutilizables que realizan una tarea específica. Permiten modularizar el código y dividirlo en partes más pequeñas y manejables.

#### Funciones

Una función es un bloque de código que realiza una tarea específica cuando es llamado. Puede aceptar datos de entrada (parámetros) y opcionalmente devolver un resultado.

**Sintaxis:**
```java
// Java
tipo_de_retorno nombre_de_funcion(parámetros) {
    // Bloque de código
    return resultado;
}
```
```csharp
// C#
tipo_de_retorno NombreDeFuncion(parámetros) {
    // Bloque de código
    return resultado;
}
```
```php
// PHP
function nombre_de_funcion(parámetros) {
    // Bloque de código
    return $resultado;
}
```

#### Procedimientos

Un procedimiento es similar a una función, pero no devuelve ningún valor. Se utiliza para realizar una tarea sin necesidad de devolver un resultado.

**Sintaxis:**
```java
// Java
void nombre_de_procedimiento(parámetros) {
    // Bloque de código
}
```
```csharp
// C#
void NombreDeProcedimiento(parámetros) {
    // Bloque de código
}
```
```php
// PHP
function nombre_de_procedimiento(parámetros) {
    // Bloque de código
}
```

Aquí tienes la implementación de la función suma en Java, C# y PHP:

#### Java
```java
// Definición de la función suma
public static int suma(int a, int b) {
    return a + b;
}
```

#### C#
```csharp
// Definición de la función Suma
public static int Suma(int a, int b) {
    return a + b;
}
```

#### PHP
```php
// Definición de la función suma
function suma($a, $b) {
    return $a + $b;
}
```

En cada caso, la función toma dos parámetros enteros, realiza la operación de suma y devuelve el resultado. Puedes llamar a estas funciones en tu código principal para sumar dos números.

#### Llamando a Funciones y Procedimientos

Para utilizar una función o procedimiento, simplemente la llamas por su nombre y proporcionas los argumentos necesarios.

**Ejemplo en código:**
```java
// Java
int resultado = suma(3, 5);
```
```csharp
// C#
int resultado = Suma(3, 5);
```
```php
// PHP
$resultado = suma(3, 5);
```

En este ejemplo, estamos llamando a una función llamada `suma` que toma dos números como parámetros y devuelve su suma. La función se llama de la misma manera en los tres lenguajes, pero la sintaxis de declaración puede variar ligeramente.

#### Ventajas de las Funciones y Procedimientos

- **Reutilización de código**: Puedes escribir una vez y utilizar múltiples veces.
- **Modularidad**: Divide tu código en partes más pequeñas y manejables.
- **Abstracción**: Oculta los detalles de implementación, lo que facilita la comprensión del código.

En resumen, las funciones y los procedimientos son herramientas poderosas que te permiten escribir código modular y reutilizable. Utilízalos para organizar tu código de manera eficiente y facilitar el mantenimiento a largo plazo.

### Arreglos y Listas

Los arreglos y las listas son estructuras de datos fundamentales que te permiten almacenar múltiples valores bajo un mismo nombre. Son especialmente útiles cuando necesitas manejar colecciones de datos de manera eficiente en tus programas.

#### Arreglos

Un arreglo es una colección ordenada de elementos del mismo tipo. Cada elemento en un arreglo tiene un índice numérico que indica su posición en el arreglo.

**Declaración de Arreglos:**
```java
// Java
tipo[] nombre_del_arreglo = new tipo[tamaño];
```
```csharp
// C#
tipo[] nombre_del_arreglo = new tipo[tamaño];
```
```php
// PHP
$nombre_del_arreglo = array();
```

**Acceso a Elementos del Arreglo:**
```java
// Java
valor = nombre_del_arreglo[indice];
```
```csharp
// C#
valor = nombre_del_arreglo[indice];
```
```php
// PHP
$valor = $nombre_del_arreglo[indice];
```

#### Listas

Una lista es una estructura de datos dinámica que puede crecer o disminuir en tamaño según sea necesario. A diferencia de los arreglos, las listas no tienen un tamaño fijo y pueden contener elementos de diferentes tipos.

**Declaración de Listas:**
```java
// Java
List<tipo> nombre_de_la_lista = new ArrayList<>();
```
```csharp
// C#
List<tipo> nombre_de_la_lista = new List<tipo>();
```
```php
// PHP
$nombre_de_la_lista = array();
```

**Agregar Elementos a una Lista:**
```java
// Java
nombre_de_la_lista.add(elemento);
```
```csharp
// C#
nombre_de_la_lista.Add(elemento);
```
```php
// PHP
array_push($nombre_de_la_lista, $elemento);
```

**Acceso a Elementos de una Lista:**
```java
// Java
valor = nombre_de_la_lista.get(indice);
```
```csharp
// C#
valor = nombre_de_la_lista[indice];
```
```php
// PHP
$valor = $nombre_de_la_lista[indice];
```

En resumen, los arreglos y las listas son herramientas esenciales para trabajar con colecciones de datos en programación. Los arreglos son ideales cuando conoces el tamaño exacto de la colección y los tipos de datos que contendrá, mientras que las listas son más flexibles y pueden crecer dinámicamente según sea necesario. Utiliza la estructura que mejor se adapte a tus necesidades específicas en cada situación.

Aquí tienes un ejemplo que combina arreglos o listas con un bucle para imprimir su contenido en Java, C# y PHP:

#### Java
```java
import java.util.Arrays;

public class Main {
    public static void main(String[] args) {
        // Declaración e inicialización de un arreglo
        int[] arreglo = {1, 2, 3, 4, 5};

        // Iteración sobre el arreglo e impresión de su contenido
        for (int i = 0; i < arreglo.length; i++) {
            System.out.println(arreglo[i]);
        }
    }
}
```

#### C#
```csharp
using System;

class Program {
    static void Main(string[] args) {
        // Declaración e inicialización de un arreglo
        int[] arreglo = {1, 2, 3, 4, 5};

        // Iteración sobre el arreglo e impresión de su contenido
        foreach (int valor in arreglo) {
            Console.WriteLine(valor);
        }
    }
}
```

#### PHP
```php
<?php
// Declaración e inicialización de una lista
$lista = array(1, 2, 3, 4, 5);

// Iteración sobre la lista e impresión de su contenido
foreach ($lista as $valor) {
    echo $valor . "\n";
}
?>
```

En cada ejemplo, declaramos e inicializamos un arreglo o lista con algunos valores. Luego, utilizamos un bucle (en este caso, un bucle `for` en Java y C#, y un bucle `foreach` en PHP) para iterar sobre cada elemento del arreglo o lista e imprimir su contenido. Este es un ejemplo básico para mostrar cómo puedes combinar arreglos o listas con bucles para trabajar con colecciones de datos en tus programas.

### Programación Orientada a Objetos (POO)

La Programación Orientada a Objetos (POO) es un paradigma de programación que se basa en el concepto de "objetos", los cuales son entidades que pueden contener datos (atributos) y comportamientos (métodos). La POO proporciona una forma organizada y modular de escribir código, lo que facilita la reutilización y el mantenimiento del mismo.

#### Clases y Objetos

- **Clase**: Una clase es una plantilla que define la estructura y el comportamiento de los objetos. Contiene atributos (variables) y métodos (funciones).
- **Objeto**: Un objeto es una instancia de una clase. Representa una entidad concreta y puede interactuar con otros objetos y el entorno.

**Ejemplo en código (Java):**
```java
// Definición de una clase
class Persona {
    // Atributos
    String nombre;
    int edad;
    
    // Método constructor
    public Persona(String nombre, int edad) {
        this.nombre = nombre;
        this.edad = edad;
    }
    
    // Método
    public void saludar() {
        System.out.println("Hola, soy " + nombre);
    }
}

// Creación de objetos
Persona persona1 = new Persona("Juan", 25);
Persona persona2 = new Persona("María", 30);

// Uso de métodos
persona1.saludar();
persona2.saludar();
```

#### Herencia

La herencia es un concepto en POO que permite crear nuevas clases basadas en clases existentes. La clase que se hereda se denomina clase base o superclase, y la clase que hereda se denomina clase derivada o subclase. La herencia permite reutilizar el código y establecer relaciones entre clases.

**Ejemplo en código (Java):**
```java
// Definición de una clase base
class Animal {
    public void sonido() {
        System.out.println("Hace un sonido.");
    }
}

// Definición de una subclase que hereda de la clase base
class Perro extends Animal {
    @Override
    public void sonido() {
        System.out.println("El perro ladra.");
    }
}

// Creación de objetos
Animal animal = new Animal();
Perro perro = new Perro();

// Uso de métodos
animal.sonido(); // Salida: Hace un sonido.
perro.sonido();  // Salida: El perro ladra.
```

#### Polimorfismo

El polimorfismo es la capacidad de los objetos de una clase para tomar varias formas. Esto se puede lograr mediante la implementación de métodos con el mismo nombre pero con diferentes comportamientos en diferentes clases. El polimorfismo permite tratar objetos de diferentes clases de manera uniforme.

**Ejemplo en código (Java):**
```java
// Definición de una clase base
class Animal {
    public void sonido() {
        System.out.println("Hace un sonido.");
    }
}

// Definición de una subclase con un comportamiento diferente
class Perro extends Animal {
    @Override
    public void sonido() {
        System.out.println("El perro ladra.");
    }
}

// Uso de polimorfismo
Animal animal = new Perro(); // Referencia de tipo Animal apunta a un objeto de tipo Perro
animal.sonido(); // Salida: El perro ladra.
```

En resumen, la Programación Orientada a Objetos es un enfoque de programación poderoso que se basa en el concepto de objetos y clases. La herencia y el polimorfismo son características importantes de la POO que permiten la reutilización de código y la creación de relaciones entre clases.

Aquí tienes los mismos ejemplos pero en C# y PHP:

#### C#

```csharp
using System;

// Definición de una clase
class Persona {
    // Atributos
    public string nombre;
    public int edad;
    
    // Constructor
    public Persona(string nombre, int edad) {
        this.nombre = nombre;
        this.edad = edad;
    }
    
    // Método
    public void Saludar() {
        Console.WriteLine("Hola, soy " + nombre);
    }
}

// Creación de objetos
Persona persona1 = new Persona("Juan", 25);
Persona persona2 = new Persona("María", 30);

// Uso de métodos
persona1.Saludar();
persona2.Saludar();
```

#### PHP

```php
<?php
// Definición de una clase
class Persona {
    // Atributos
    public $nombre;
    public $edad;
    
    // Constructor
    public function __construct($nombre, $edad) {
        $this->nombre = $nombre;
        $this->edad = $edad;
    }
    
    // Método
    public function saludar() {
        echo "Hola, soy " . $this->nombre . "\n";
    }
}

// Creación de objetos
$persona1 = new Persona("Juan", 25);
$persona2 = new Persona("María", 30);

// Uso de métodos
$persona1->saludar();
$persona2->saludar();
?>
```

En ambos ejemplos, definimos una clase llamada `Persona` con atributos (en C#, los atributos se declaran como públicos, mientras que en PHP utilizamos la palabra clave `public` para especificar la visibilidad) y métodos. Luego creamos objetos de esta clase y llamamos a sus métodos para mostrar un saludo personalizado. La sintaxis puede variar ligeramente entre los lenguajes, pero el concepto básico es el mismo.

### Manejo de Excepciones

El manejo de excepciones es una técnica en programación que te permite manejar situaciones excepcionales o errores durante la ejecución de un programa. Las excepciones pueden surgir por diversas razones, como errores de sintaxis, acceso a datos inexistentes, división por cero, entre otros. Es importante manejar estas excepciones de manera adecuada para garantizar que tu programa se ejecute de manera segura y controlada.

#### Bloque Try-Catch

En la mayoría de los lenguajes de programación, incluyendo Java, C# y PHP, el manejo de excepciones se realiza utilizando un bloque `try-catch`. Dentro del bloque `try`, colocas el código que puede lanzar una excepción, y dentro del bloque `catch`, manejas la excepción si ocurre.

**Sintaxis (Java):**
```java
try {
    // Bloque de código que puede lanzar una excepción
} catch (TipoDeExcepcion nombreDeExcepcion) {
    // Manejo de la excepción
}
```

**Sintaxis (C#):**
```csharp
try {
    // Bloque de código que puede lanzar una excepción
} catch (TipoDeExcepcion nombreDeExcepcion) {
    // Manejo de la excepción
}
```

**Sintaxis (PHP):**
```php
try {
    // Bloque de código que puede lanzar una excepción
} catch (TipoDeExcepcion $nombreDeExcepcion) {
    // Manejo de la excepción
}
```

#### Tipos de Excepciones

Cada lenguaje de programación tiene su propio conjunto de excepciones predefinidas, pero generalmente incluyen excepciones comunes como `NullPointerException`, `ArithmeticException`, `FileNotFoundException`, entre otras.

#### Ejemplo de Manejo de Excepciones

**Java:**
```java
try {
    int resultado = 10 / 0; // Esto lanzará una ArithmeticException
} catch (ArithmeticException e) {
    System.out.println("Error: División por cero");
}
```

**C#:**
```csharp
try {
    int resultado = 10 / 0; // Esto lanzará una DivideByZeroException
} catch (DivideByZeroException e) {
    Console.WriteLine("Error: División por cero");
}
```

**PHP:**
```php
try {
    $resultado = 10 / 0; // Esto lanzará una DivisionByZeroError
} catch (DivisionByZeroError $e) {
    echo "Error: División por cero";
}
```

En estos ejemplos, el código dentro del bloque `try` intenta realizar una operación aritmética inválida (división por cero), lo que provoca que se lance una excepción. El bloque `catch` maneja la excepción mostrando un mensaje de error adecuado. Esto garantiza que el programa no se detenga abruptamente y que el usuario reciba información sobre el problema ocurrido.

### Entrada y Salida de Datos

La entrada y salida de datos son operaciones fundamentales en programación que te permiten interactuar con el usuario y con archivos en el sistema de archivos. A continuación, te mostraré cómo realizar la lectura desde el teclado y la escritura en archivos en Java, C# y PHP.

#### Lectura desde Teclado

**Java:**
```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Ingrese su nombre: ");
        String nombre = scanner.nextLine();
        System.out.println("Hola, " + nombre);
    }
}
```

**C#:**
```csharp
using System;

class Program {
    static void Main(string[] args) {
        Console.Write("Ingrese su nombre: ");
        string nombre = Console.ReadLine();
        Console.WriteLine("Hola, " + nombre);
    }
}
```

**PHP:**
```php
<?php
echo "Ingrese su nombre: ";
$nombre = readline();
echo "Hola, $nombre";
?>
```

#### Escritura en Archivos

**Java:**
```java
import java.io.FileWriter;
import java.io.IOException;

public class Main {
    public static void main(String[] args) {
        try {
            FileWriter writer = new FileWriter("archivo.txt");
            writer.write("Hola mundo!");
            writer.close();
        } catch (IOException e) {
            System.out.println("Error al escribir en el archivo");
            e.printStackTrace();
        }
    }
}
```

**C#:**
```csharp
using System;
using System.IO;

class Program {
    static void Main(string[] args) {
        try {
            File.WriteAllText("archivo.txt", "Hola mundo!");
        } catch (IOException e) {
            Console.WriteLine("Error al escribir en el archivo");
            Console.WriteLine(e.Message);
        }
    }
}
```

**PHP:**
```php
<?php
$file = fopen("archivo.txt", "w");
if ($file) {
    fwrite($file, "Hola mundo!");
    fclose($file);
} else {
    echo "Error al escribir en el archivo";
}
?>
```

En cada ejemplo, se muestra cómo realizar la lectura desde el teclado y la escritura en archivos en los tres lenguajes. La sintaxis puede variar ligeramente entre los lenguajes, pero el concepto básico es el mismo. ¡Espero que encuentres útiles estos ejemplos para tus proyectos de programación!

### Manipulación de Cadenas de Texto

La manipulación de cadenas de texto es una tarea común en programación que implica realizar operaciones como concatenación, búsqueda, reemplazo, extracción de subcadenas, entre otros. A continuación, te mostraré cómo realizar algunas operaciones básicas de manipulación de cadenas en Java, C# y PHP.

#### Concatenación de Cadenas

**Java:**
```java
String str1 = "Hola";
String str2 = " mundo";
String resultado = str1 + str2;
System.out.println(resultado); // Salida: Hola mundo
```

**C#:**
```csharp
string str1 = "Hola";
string str2 = " mundo";
string resultado = str1 + str2;
Console.WriteLine(resultado); // Salida: Hola mundo
```

**PHP:**
```php
$str1 = "Hola";
$str2 = " mundo";
$resultado = $str1 . $str2;
echo $resultado; // Salida: Hola mundo
```

#### Búsqueda de Subcadenas

**Java:**
```java
String frase = "Hola mundo";
int indice = frase.indexOf("mundo");
System.out.println(indice); // Salida: 5
```

**C#:**
```csharp
string frase = "Hola mundo";
int indice = frase.IndexOf("mundo");
Console.WriteLine(indice); // Salida: 5
```

**PHP:**
```php
$frase = "Hola mundo";
$indice = strpos($frase, "mundo");
echo $indice; // Salida: 5
```

#### Reemplazo de Subcadenas

**Java:**
```java
String frase = "Hola mundo";
String nuevaFrase = frase.replace("mundo", "amigo");
System.out.println(nuevaFrase); // Salida: Hola amigo
```

**C#:**
```csharp
string frase = "Hola mundo";
string nuevaFrase = frase.Replace("mundo", "amigo");
Console.WriteLine(nuevaFrase); // Salida: Hola amigo
```

**PHP:**
```php
$frase = "Hola mundo";
$nuevaFrase = str_replace("mundo", "amigo", $frase);
echo $nuevaFrase; // Salida: Hola amigo
```

En estos ejemplos, se muestran algunas operaciones básicas de manipulación de cadenas como la concatenación, búsqueda y reemplazo de subcadenas. La sintaxis puede variar ligeramente entre los lenguajes, pero el concepto básico es el mismo. ¡Espero que encuentres útiles estos ejemplos para trabajar con cadenas de texto en tus proyectos!

### Trabajo con Fechas y Horas

El trabajo con fechas y horas es una tarea común en programación, especialmente al desarrollar aplicaciones que necesitan manejar eventos temporales. A continuación, te mostraré cómo trabajar con fechas y horas en Java, C# y PHP.

#### Obtener la Fecha y Hora Actual

**Java:**
```java
import java.util.Date;

public class Main {
    public static void main(String[] args) {
        Date fechaActual = new Date();
        System.out.println(fechaActual); // Muestra la fecha y hora actual
    }
}
```

**C#:**
```csharp
using System;

class Program {
    static void Main(string[] args) {
        DateTime fechaActual = DateTime.Now;
        Console.WriteLine(fechaActual); // Muestra la fecha y hora actual
    }
}
```

**PHP:**
```php
<?php
$fechaActual = new DateTime();
echo $fechaActual->format('Y-m-d H:i:s'); // Muestra la fecha y hora actual
?>
```

#### Formatear Fechas

**Java:**
```java
import java.text.SimpleDateFormat;
import java.util.Date;

public class Main {
    public static void main(String[] args) {
        Date fecha = new Date();
        SimpleDateFormat formato = new SimpleDateFormat("dd/MM/yyyy HH:mm:ss");
        String fechaFormateada = formato.format(fecha);
        System.out.println(fechaFormateada); // Muestra la fecha y hora formateada
    }
}
```

**C#:**
```csharp
using System;

class Program {
    static void Main(string[] args) {
        DateTime fecha = DateTime.Now;
        string fechaFormateada = fecha.ToString("dd/MM/yyyy HH:mm:ss");
        Console.WriteLine(fechaFormateada); // Muestra la fecha y hora formateada
    }
}
```

**PHP:**
```php
<?php
$fecha = new DateTime();
$fechaFormateada = $fecha->format('d/m/Y H:i:s');
echo $fechaFormateada; // Muestra la fecha y hora formateada
?>
```

#### Operaciones con Fechas

**Java:**
```java
import java.util.Calendar;
import java.util.Date;

public class Main {
    public static void main(String[] args) {
        Calendar calendario = Calendar.getInstance();
        calendario.setTime(new Date());
        calendario.add(Calendar.DAY_OF_YEAR, 7); // Añade 7 días a la fecha actual
        Date nuevaFecha = calendario.getTime();
        System.out.println(nuevaFecha); // Muestra la nueva fecha
    }
}
```

**C#:**
```csharp
using System;

class Program {
    static void Main(string[] args) {
        DateTime fechaActual = DateTime.Now;
        DateTime nuevaFecha = fechaActual.AddDays(7); // Añade 7 días a la fecha actual
        Console.WriteLine(nuevaFecha); // Muestra la nueva fecha
    }
}
```

**PHP:**
```php
<?php
$fecha = new DateTime();
$fecha->modify('+7 days'); // Añade 7 días a la fecha actual
$nuevaFecha = $fecha->format('Y-m-d H:i:s');
echo $nuevaFecha; // Muestra la nueva fecha
?>
```

Estos son algunos ejemplos básicos de cómo trabajar con fechas y horas en Java, C# y PHP. Puedes realizar operaciones como obtener la fecha y hora actual, formatear fechas según tus necesidades y realizar cálculos con fechas, como agregar días o meses. ¡Espero que encuentres útiles estos ejemplos para manejar fechas y horas en tus proyectos!

La manipulación de archivos es una tarea esencial en la programación, ya que te permite leer y escribir datos en archivos en el sistema de archivos del dispositivo. A continuación, te mostraré cómo manipular archivos en Java, C# y PHP para realizar operaciones como leer, escribir, crear y eliminar archivos.

### Java

#### Lectura desde un Archivo

```java
import java.io.File;
import java.io.FileNotFoundException;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        try {
            File archivo = new File("archivo.txt");
            Scanner lector = new Scanner(archivo);
            while (lector.hasNextLine()) {
                String linea = lector.nextLine();
                System.out.println(linea);
            }
            lector.close();
        } catch (FileNotFoundException e) {
            System.out.println("No se encontró el archivo");
            e.printStackTrace();
        }
    }
}
```

#### Escritura en un Archivo

```java
import java.io.FileWriter;
import java.io.IOException;

public class Main {
    public static void main(String[] args) {
        try {
            FileWriter escritor = new FileWriter("archivo.txt");
            escritor.write("Hola mundo!");
            escritor.close();
            System.out.println("Se escribió en el archivo correctamente");
        } catch (IOException e) {
            System.out.println("Ocurrió un error al escribir en el archivo");
            e.printStackTrace();
        }
    }
}
```

### C#

#### Lectura desde un Archivo

```csharp
using System;
using System.IO;

class Program {
    static void Main(string[] args) {
        try {
            string[] lineas = File.ReadAllLines("archivo.txt");
            foreach (string linea in lineas) {
                Console.WriteLine(linea);
            }
        } catch (FileNotFoundException e) {
            Console.WriteLine("No se encontró el archivo");
            Console.WriteLine(e.Message);
        }
    }
}
```

#### Escritura en un Archivo

```csharp
using System;
using System.IO;

class Program {
    static void Main(string[] args) {
        try {
            string texto = "Hola mundo!";
            File.WriteAllText("archivo.txt", texto);
            Console.WriteLine("Se escribió en el archivo correctamente");
        } catch (IOException e) {
            Console.WriteLine("Ocurrió un error al escribir en el archivo");
            Console.WriteLine(e.Message);
        }
    }
}
```

### PHP

#### Lectura desde un Archivo

```php
<?php
$archivo = fopen("archivo.txt", "r") or die("No se pudo abrir el archivo");
while (!feof($archivo)) {
    echo fgets($archivo) . "<br>";
}
fclose($archivo);
?>
```

#### Escritura en un Archivo

```php
<?php
$archivo = fopen("archivo.txt", "w") or die("No se pudo abrir el archivo");
$txt = "Hola mundo!";
fwrite($archivo, $txt);
fclose($archivo);
echo "Se escribió en el archivo correctamente";
?>
```

Estos ejemplos te permitirán realizar operaciones básicas de manipulación de archivos en Java, C# y PHP. Recuerda siempre manejar las excepciones adecuadamente para garantizar la integridad y la seguridad de tus operaciones de archivo. ¡Espero que encuentres útiles estos ejemplos para tus proyectos!

La interacción con bases de datos es una parte fundamental en el desarrollo de aplicaciones, ya que te permite almacenar, recuperar y manipular datos de manera eficiente. A continuación, te mostraré cómo interactuar con bases de datos en Java, C# y PHP utilizando ejemplos básicos de conexión, consulta y manipulación de datos.

### Java

#### Conexión a una Base de Datos MySQL

```java
import java.sql.Connection;
import java.sql.DriverManager;
import java.sql.SQLException;

public class Main {
    public static void main(String[] args) {
        Connection conexion = null;
        try {
            // Conexión a la base de datos MySQL
            String url = "jdbc:mysql://localhost:3306/nombre_basedatos";
            String usuario = "usuario";
            String contraseña = "contraseña";
            conexion = DriverManager.getConnection(url, usuario, contraseña);
            if (conexion != null) {
                System.out.println("Conexión exitosa");
            }
        } catch (SQLException e) {
            System.out.println("Error al conectar a la base de datos");
            e.printStackTrace();
        } finally {
            try {
                if (conexion != null) {
                    conexion.close();
                }
            } catch (SQLException e) {
                e.printStackTrace();
            }
        }
    }
}
```

#### Consulta a una Base de Datos MySQL

```java
import java.sql.Connection;
import java.sql.DriverManager;
import java.sql.ResultSet;
import java.sql.SQLException;
import java.sql.Statement;

public class Main {
    public static void main(String[] args) {
        Connection conexion = null;
        try {
            String url = "jdbc:mysql://localhost:3306/nombre_basedatos";
            String usuario = "usuario";
            String contraseña = "contraseña";
            conexion = DriverManager.getConnection(url, usuario, contraseña);
            if (conexion != null) {
                System.out.println("Conexión exitosa");
                
                // Ejecución de consulta
                Statement statement = conexion.createStatement();
                String consulta = "SELECT * FROM tabla";
                ResultSet resultado = statement.executeQuery(consulta);
                while (resultado.next()) {
                    String columna1 = resultado.getString("columna1");
                    int columna2 = resultado.getInt("columna2");
                    System.out.println(columna1 + " - " + columna2);
                }
            }
        } catch (SQLException e) {
            System.out.println("Error al conectar a la base de datos");
            e.printStackTrace();
        } finally {
            try {
                if (conexion != null) {
                    conexion.close();
                }
            } catch (SQLException e) {
                e.printStackTrace();
            }
        }
    }
}
```

### C#

#### Conexión a una Base de Datos SQL Server

```csharp
using System;
using System.Data.SqlClient;

class Program {
    static void Main(string[] args) {
        SqlConnection conexion = null;
        try {
            // Conexión a la base de datos SQL Server
            string connectionString = "Data Source=nombre_servidor;Initial Catalog=nombre_basedatos;User ID=usuario;Password=contraseña";
            conexion = new SqlConnection(connectionString);
            conexion.Open();
            Console.WriteLine("Conexión exitosa");
        } catch (SqlException e) {
            Console.WriteLine("Error al conectar a la base de datos");
            Console.WriteLine(e.Message);
        } finally {
            if (conexion != null && conexion.State == System.Data.ConnectionState.Open) {
                conexion.Close();
            }
        }
    }
}
```

#### Consulta a una Base de Datos SQL Server

```csharp
using System;
using System.Data.SqlClient;

class Program {
    static void Main(string[] args) {
        SqlConnection conexion = null;
        try {
            string connectionString = "Data Source=nombre_servidor;Initial Catalog=nombre_basedatos;User ID=usuario;Password=contraseña";
            conexion = new SqlConnection(connectionString);
            conexion.Open();
            Console.WriteLine("Conexión exitosa");

            // Ejecución de consulta
            string consulta = "SELECT * FROM tabla";
            SqlCommand comando = new SqlCommand(consulta, conexion);
            SqlDataReader resultado = comando.ExecuteReader();
            while (resultado.Read()) {
                string columna1 = resultado.GetString(0);
                int columna2 = resultado.GetInt32(1);
                Console.WriteLine(columna1 + " - " + columna2);
            }
        } catch (SqlException e) {
            Console.WriteLine("Error al conectar a la base de datos");
            Console.WriteLine(e.Message);
        } finally {
            if (conexion != null && conexion.State == System.Data.ConnectionState.Open) {
                conexion.Close();
            }
        }
    }
}
```

### PHP

#### Conexión a una Base de Datos MySQL

```php
<?php
$servername = "localhost";
$username = "usuario";
$password = "contraseña";
$dbname = "nombre_basedatos";

// Crear conexión
$conexion = new mysqli($servername, $username, $password, $dbname);

// Verificar conexión
if ($conexion->connect_error) {
  die("Error de conexión: " . $conexion->connect_error);
}
echo "Conexión exitosa";
$conexion->close();
?>
```

#### Consulta a una Base de Datos MySQL

```php
<?php
$servername = "localhost";
$username = "usuario";
$password = "contraseña";
$dbname = "nombre_basedatos";

// Crear conexión
$conexion = new mysqli($servername, $username, $password, $dbname);

// Verificar conexión
if ($conexion->connect_error) {
  die("Error de conexión: " . $conexion->connect_error);
}

// Ejecución de consulta
$consulta = "SELECT columna1, columna2 FROM tabla";
$resultado = $conexion->query($consulta);

if ($resultado->num_rows > 0) {
  // Mostrar datos de cada fila
  while($fila = $resultado->fetch_assoc()) {
    echo "Columna1: " . $fila["columna1"]. " - Columna2: " . $fila["columna2"]. "<br>";
  }
} else {
  echo "0 resultados";
}
$conexion->close();
?>
```

Estos son ejemplos básicos de cómo interactuar con bases de datos en Java, C# y PHP. Puedes utilizar estos ejemplos como punto de partida y adaptarlos según tus necesidades específicas y el tipo de base de datos que estés utilizando. ¡Espero que te sean útiles para trabajar con bases de datos en tus proyectos!