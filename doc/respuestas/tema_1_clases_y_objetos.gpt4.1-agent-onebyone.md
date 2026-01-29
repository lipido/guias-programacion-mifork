<!--
Posible prompt:
<prompt>
Tengo un cuestionario con preguntas sobre "Clases y Objetos". Debes tener en cuenta que los conocimientos previos que tengo (y por tanto tus respuestas deben ser adaptadas), son:
- C/C++ sin orientación a objetos.
- Temas de Java previos: ninguno.

Cada respuesta debe tener entre 2 - 4 párrafos de longitud (sin contar los trozos de código).

Por favor, escribe en impersonal las respuestas.

</prompt>
----
-->

# TEMA 1. Clases y objetos

## 1. ¿Cuáles son las cuatro características básicas de la programación orientada a objetos? Describe brevemente cada una

### Respuesta

Las cuatro características básicas de la programación orientada a objetos son: **abstracción**, **encapsulamiento**, **herencia** y **polimorfismo**.

La **abstracción** consiste en identificar y definir los elementos esenciales de un problema, ignorando los detalles irrelevantes. Permite modelar entidades del mundo real como objetos dentro del programa, centrándose en sus características y comportamientos principales.

El **encapsulamiento** implica agrupar los datos (atributos) y los métodos (funciones) que operan sobre esos datos dentro de una misma unidad llamada clase. Además, restringe el acceso directo a algunos componentes del objeto, protegiendo la integridad de la información y facilitando el mantenimiento del código.

La **herencia** permite crear nuevas clases a partir de clases existentes, heredando sus atributos y métodos. Esto favorece la reutilización del código y la creación de jerarquías que reflejan relaciones del mundo real.

El **polimorfismo** posibilita que diferentes objetos puedan responder a un mismo mensaje o llamada de método de distintas formas, según su tipo concreto. Así, se pueden utilizar interfaces comunes para manipular objetos de diferentes clases de manera uniforme.


## 2. Cita cuatro lenguajes populares que permitan la programación orientada a objetos

### Respuesta

Cuatro lenguajes populares que permiten la programación orientada a objetos son: **Java**, **C++**, **Python** y **C#**.

Java es ampliamente utilizado en el desarrollo de aplicaciones empresariales, móviles y web, y está diseñado desde sus inicios con un enfoque orientado a objetos. C++ extiende el lenguaje C añadiendo soporte para clases y objetos, siendo muy empleado en sistemas y aplicaciones de alto rendimiento. Python, aunque es un lenguaje multiparadigma, ofrece un soporte sencillo y flexible para la programación orientada a objetos. Por último, C# es el lenguaje principal de la plataforma .NET y está fuertemente basado en el paradigma orientado a objetos.


## 3. Los paradigmas anteriores a la POO, ¿Qué es la **programación estructurada**? y, todavía mejor, ¿Qué es la **programación modular**?

### Respuesta

La **programación estructurada** es un paradigma que organiza el código en bloques secuenciales, condicionales y repetitivos, evitando el uso excesivo de saltos incondicionales como el `goto`. Su objetivo es mejorar la claridad, calidad y desarrollo del software, facilitando la comprensión y el mantenimiento del código. En este enfoque, los programas se dividen en funciones o procedimientos que resuelven tareas específicas.

Por otro lado, la **programación modular** lleva un paso más allá la estructuración del código, dividiéndolo en módulos independientes y reutilizables. Cada módulo agrupa funciones, datos y estructuras relacionadas, permitiendo desarrollar, probar y mantener partes del programa de forma aislada. Este enfoque favorece la reutilización y la escalabilidad, ya que los módulos pueden integrarse en diferentes proyectos o ampliarse sin afectar al resto del sistema.

Ambos paradigmas sentaron las bases para la programación orientada a objetos, aportando ideas clave como la descomposición de problemas y la organización lógica del código.

## 4. ¿Qué tres elementos definen a un objeto en programación orientada a objetos?

### Respuesta

En programación orientada a objetos, un objeto se define principalmente por tres elementos: **identidad**, **estado** y **comportamiento**.

La **identidad** distingue a cada objeto de los demás, incluso si tienen el mismo estado. Es una propiedad única que permite referirse a un objeto concreto dentro del programa.

El **estado** está formado por los valores actuales de los atributos o propiedades del objeto. Este estado puede cambiar a lo largo del tiempo mediante la interacción con el objeto.

El **comportamiento** se refiere al conjunto de métodos o funciones que el objeto puede ejecutar. Estos métodos permiten modificar el estado del objeto o interactuar con otros objetos, definiendo así cómo responde ante diferentes estímulos o mensajes.

## 5. ¿Qué es una clase? ¿Es lo mismo que un objeto? ¿Qué es una instancia? ¿Todos los lenguajes orientados a objetos manejan el concepto de clase?

### Respuesta

Una **clase** es una plantilla o modelo que define las características y comportamientos que tendrán los objetos creados a partir de ella. Especifica los atributos (datos) y métodos (funciones) que compartirán todos los objetos de ese tipo.

Un **objeto** es una entidad concreta creada a partir de una clase. Mientras que la clase es la definición abstracta, el objeto es la realización concreta de esa definición, con valores propios en sus atributos.

El término **instancia** se refiere a cada uno de los objetos creados a partir de una clase. Instanciar una clase significa crear un objeto concreto de ese tipo.

No todos los lenguajes orientados a objetos manejan el concepto de clase de la misma manera. Algunos, como Java, C++ o C#, se basan en clases para crear objetos. Sin embargo, otros lenguajes como JavaScript o Python permiten la creación de objetos sin necesidad de definir clases explícitas, utilizando prototipos o estructuras dinámicas.


## 6. ¿Dónde se almacenan en memoria los objetos? ¿Es igual en todos los lenguajes? ¿Qué es la **recolección de basura**? 

### Respuesta

El lugar donde se almacenan los objetos en memoria depende del lenguaje de programación y de su modelo de gestión de memoria. En lenguajes como Java, los objetos suelen almacenarse en una zona llamada heap, que es gestionada automáticamente por el sistema de ejecución. En C++, los objetos pueden almacenarse tanto en la pila (stack) como en el heap, dependiendo de cómo se creen.

No todos los lenguajes gestionan la memoria de la misma forma. Algunos, como Java o Python, utilizan sistemas automáticos de gestión de memoria, mientras que en C++ la gestión suele ser manual, requiriendo que el programador libere la memoria cuando ya no es necesaria.

La **recolección de basura** (garbage collection) es un proceso automático mediante el cual el sistema identifica y libera la memoria ocupada por objetos que ya no son accesibles o utilizados por el programa. Esto ayuda a evitar fugas de memoria y simplifica el desarrollo, aunque puede tener un impacto en el rendimiento en ciertos momentos.


## 7. ¿Qué es un método? ¿Qué es la **sobrecarga de métodos**? 

### Respuesta

Un **método** es una función definida dentro de una clase que describe una acción o comportamiento que pueden realizar los objetos de esa clase. Los métodos permiten manipular los atributos del objeto y definir cómo interactúa con otros objetos o con el entorno del programa.

La **sobrecarga de métodos** es una característica que permite definir varios métodos con el mismo nombre dentro de una clase, pero que se diferencian en el número o tipo de sus parámetros. Esto facilita el uso de un mismo nombre para operaciones similares, adaptándose a diferentes situaciones según los argumentos proporcionados.

En lenguajes como Java, la sobrecarga de métodos mejora la legibilidad y flexibilidad del código, ya que permite ofrecer distintas formas de invocar una acción sin necesidad de crear nombres diferentes para cada variante.


## 8. Ejemplo mínimo de clase en Java, que se llame Punto, con dos atributos, x e y, con un método que se llame `calculaDistanciaAOrigen`, que calcule la distancia a la posición 0,0. Por sencillez, los atributos deben tener visibilidad por defecto. Crea además un ejemplo de uso con una instancia y uso del método. 

### Respuesta

A continuación se muestra un ejemplo mínimo de una clase en Java llamada `Punto`, que tiene dos atributos (`x` e `y`) y un método para calcular la distancia al origen (0,0):

```java
class Punto {
	int x;
	int y;

	double calculaDistanciaAOrigen() {
		return Math.sqrt(x * x + y * y);
	}
}
```

Ejemplo de uso de la clase `Punto`:

```java
public class Ejemplo {
	public static void main(String[] args) {
		Punto p = new Punto();
		p.x = 3;
		p.y = 4;
		double distancia = p.calculaDistanciaAOrigen();
		System.out.println("Distancia al origen: " + distancia);
	}
}
```

En este ejemplo, se crea una instancia de la clase `Punto`, se asignan valores a sus atributos y se utiliza el método para calcular la distancia al origen. El resultado mostrado será 5.0, que corresponde a la distancia euclídea desde el punto (3,4) al origen (0,0).


## 9. ¿Cuál es el punto de entrada en un programa en Java? ¿Qué es `static` y para qué vale? ¿Sólo se emplea para ese método `main`? ¿Para qué se combina con `final`?

### Respuesta

El punto de entrada en un programa en Java es el método `main`, que debe tener la siguiente firma: `public static void main(String[] args)`. Este método es el primero que se ejecuta al iniciar el programa y es necesario para que la aplicación arranque correctamente.

La palabra clave `static` indica que el método o atributo pertenece a la clase y no a una instancia concreta. Esto significa que se puede invocar el método `main` sin necesidad de crear un objeto de la clase. `static` también se utiliza para definir variables y otros métodos que deben ser accesibles a nivel de clase.

El modificador `static` no se emplea únicamente en el método `main`, sino que puede aplicarse a cualquier método o atributo que deba ser compartido por todas las instancias de la clase o que deba poder usarse sin crear objetos.

Cuando se combina `static` con `final`, se indica que el valor de ese atributo es constante y pertenece a la clase, no a las instancias. Por ejemplo, `static final double PI = 3.1416;` define una constante accesible desde cualquier parte del programa sin necesidad de crear objetos.

## 10. Intenta ejecutar un poco de Java de forma básica, con los comandos `javac` y `java`. ¿Cómo podemos compilar el programa y ejecutarlo desde linea de comandos? ¿Java es compilado? ¿Qué es la **máquina virtual**? ¿Qué es el *byte-code* y los ficheros `.class`?

### Respuesta

Para compilar un programa en Java desde la línea de comandos, se utiliza el comando `javac NombreArchivo.java`, que genera un archivo con extensión `.class`. Este archivo contiene el *byte-code*, una representación intermedia del programa. Para ejecutar el programa, se emplea el comando `java NombreDeLaClase`, que inicia la aplicación usando la máquina virtual de Java.

Java es un lenguaje compilado e interpretado. El código fuente se compila a *byte-code*, que no es código máquina específico de un sistema operativo, sino un formato intermedio portátil. Este *byte-code* es interpretado o compilado en tiempo de ejecución por la **máquina virtual de Java** (JVM), lo que permite que el mismo programa se ejecute en diferentes sistemas sin modificaciones.

La **máquina virtual de Java** es un entorno de ejecución que se encarga de interpretar o compilar el *byte-code* a instrucciones comprensibles por el sistema operativo y el hardware. Esto proporciona portabilidad y seguridad al programa.

Los archivos `.class` contienen el *byte-code* generado por el compilador. Estos archivos son los que la JVM utiliza para ejecutar el programa, y pueden distribuirse y ejecutarse en cualquier sistema que tenga instalada una máquina virtual de Java compatible.


## 11. En el código anterior de la clase `Punto` ¿Qué es `new`? ¿Qué es un **constructor**? Pon un ejemplo de constructor en una clase `Empleado` que tenga DNI, nombre y apellidos.

### Respuesta

La palabra clave `new` en Java se utiliza para crear un nuevo objeto, es decir, una instancia de una clase. Al emplear `new`, se reserva memoria para el objeto y se invoca su constructor para inicializarlo.

Un **constructor** es un método especial de una clase que se llama automáticamente al crear un objeto con `new`. Su función principal es inicializar los atributos del objeto. El constructor tiene el mismo nombre que la clase y no devuelve ningún valor.

A continuación se muestra un ejemplo de clase `Empleado` con un constructor que recibe el DNI, el nombre y los apellidos:

```java
class Empleado {
	String dni;
	String nombre;
	String apellidos;

	Empleado(String dni, String nombre, String apellidos) {
		this.dni = dni;
		this.nombre = nombre;
		this.apellidos = apellidos;
	}
}
```

En este ejemplo, el constructor permite crear objetos de tipo `Empleado` inicializando sus atributos desde el momento de la creación.


## 12. ¿Qué es la referencia `this`? ¿Se llama igual en todos los lenguajes? Pon un ejemplo del uso de `this` en la clase `Punto`.

### Respuesta

La referencia `this` en Java se utiliza dentro de los métodos de una clase para referirse al objeto actual, es decir, a la instancia sobre la que se está ejecutando el método. Permite distinguir entre los atributos del objeto y los parámetros o variables locales que puedan tener el mismo nombre.

El nombre de esta referencia puede variar según el lenguaje. En Java, C++ y C# se utiliza `this`, mientras que en Python se emplea `self` y en otros lenguajes puede recibir nombres distintos o no existir como tal.

Ejemplo de uso de `this` en la clase `Punto`:

```java
class Punto {
	int x;
	int y;

	void setXY(int x, int y) {
		this.x = x;
		this.y = y;
	}
}
```

En este ejemplo, `this.x` y `this.y` hacen referencia a los atributos del objeto, mientras que `x` e `y` son los parámetros del método.


## 13. Añade ahora otro nuevo método que se llame `distanciaA`, que reciba un `Punto` como parámetro y calcule la distancia entre `this` y el punto proporcionado.

### Respuesta

Para calcular la distancia entre el objeto actual y otro punto, se puede añadir un método llamado `distanciaA` en la clase `Punto`. Este método recibirá como parámetro otro objeto de tipo `Punto` y utilizará la referencia `this` para acceder a los atributos del objeto actual.

Ejemplo de implementación en Java:

```java
class Punto {
	int x;
	int y;

	double distanciaA(Punto otro) {
		int dx = this.x - otro.x;
		int dy = this.y - otro.y;
		return Math.sqrt(dx * dx + dy * dy);
	}
}
```

En este ejemplo, el método `distanciaA` calcula la distancia euclídea entre el punto actual (`this`) y el punto recibido como argumento. Así, se puede comparar la posición de dos puntos en el plano.


## 14. El paso del `Punto` como parámetro a un método, es **por copia** o **por referencia**, es decir, si se cambia el valor de algún atributo del punto pasado como parámetro, dichos cambios afectan al objeto fuera del método? ¿Qué ocurre si en vez de un `Punto`, se recibiese un entero (`int`) y dicho entero se modificase dentro de la función? 

### Respuesta

En Java, cuando se pasa un objeto como parámetro a un método, lo que realmente se pasa es una copia de la referencia al objeto, no el objeto en sí. Esto significa que si se modifica algún atributo del objeto dentro del método, esos cambios afectan al objeto original fuera del método, ya que ambos (el parámetro y el original) apuntan al mismo espacio de memoria.

Sin embargo, si se asigna una nueva referencia al parámetro dentro del método, esa asignación solo afecta al parámetro local y no al objeto original. Por tanto, los cambios en los atributos sí se reflejan fuera, pero no así el cambio de referencia.

En el caso de los tipos primitivos, como `int`, el valor se pasa por copia. Si se modifica el valor del entero dentro del método, ese cambio no afecta a la variable original fuera del método, ya que se trabaja con una copia independiente del valor.


## 15. ¿Qué es el método `toString()` en Java? ¿Existe en otros lenguajes? Pon un ejemplo de `toString()` en la clase `Punto` en Java. 

### Respuesta

El método `toString()` en Java es un método especial que permite obtener una representación en forma de cadena de texto de un objeto. Por defecto, devuelve una cadena que incluye el nombre de la clase y un identificador interno, pero se puede sobrescribir para mostrar información más útil y legible sobre el estado del objeto.

Métodos similares existen en otros lenguajes orientados a objetos. Por ejemplo, en Python se utiliza `__str__`, en C# también existe `ToString()`, y en otros lenguajes se pueden definir funciones equivalentes para obtener una representación textual de los objetos.

Ejemplo de implementación de `toString()` en la clase `Punto` en Java:

```java
class Punto {
	int x;
	int y;

	@Override
	public String toString() {
		return "Punto(" + x + ", " + y + ")";
	}
}
```

Con esta implementación, al imprimir un objeto de tipo `Punto` con `System.out.println(p)`, se mostrará una cadena como `Punto(3, 4)` en lugar de la representación por defecto.


## 16. Reflexiona: ¿una clase es como un `struct` en C? ¿Qué le falta al `struct` para ser como una clase y las variables de ese tipo ser instancias?


### Respuesta

Una clase y un `struct` en C comparten la idea de agrupar datos bajo un mismo tipo, pero existen diferencias fundamentales. Un `struct` en C solo permite definir un conjunto de variables (campos) agrupadas, sin asociarles funciones o comportamientos.

Para que un `struct` sea como una clase, le faltan varias características clave: la posibilidad de asociar métodos (funciones miembro), mecanismos de encapsulamiento (control de acceso a los datos), herencia y polimorfismo. Además, en C no existe el concepto de instancia con identidad y comportamiento propio, ya que los `struct` son simplemente bloques de datos.

En la programación orientada a objetos, una clase define tanto los datos como los métodos que operan sobre ellos, permitiendo crear instancias (objetos) con identidad, estado y comportamiento. En cambio, los `struct` en C solo permiten crear variables que agrupan datos, sin las capacidades avanzadas de las clases.


## 17. Quitemos un poco de magia a todo esto: ¿Como se podría “emular”, con `struct` en C, la clase `Punto`, con su función para calcular la distancia al origen? ¿Qué ha pasado con `this`?

### Respuesta

En C, se puede emular una clase `Punto` utilizando un `struct` para los datos y una función aparte para calcular la distancia al origen. No existe el concepto de métodos asociados directamente al `struct`, ni la referencia `this`.

Ejemplo en C:

```c
typedef struct {
	int x;
	int y;
} Punto;

double calculaDistanciaAOrigen(Punto p) {
	return sqrt(p.x * p.x + p.y * p.y);
}

// Uso:
// Punto p = {3, 4};
// double d = calculaDistanciaAOrigen(p);
```

En este caso, la función recibe el `struct` como argumento y opera sobre sus campos. No existe la referencia `this`, ya que en C no hay métodos asociados a los datos, sino funciones externas que reciben el `struct` como parámetro. Esto limita la encapsulación y la integración de datos y comportamientos que sí ofrece la programación orientada a objetos.
