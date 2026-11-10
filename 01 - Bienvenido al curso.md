Antes de escribir nuestra primera línea de código en Java y verla cobrar vida, hay un requisito indispensable que debemos cumplir: necesitamos instalar el Java Development Kit, mejor conocido como JDK.

La regla de oro para decidirnos por una versión es sencilla: intenta usar siempre una versión moderna o la más reciente disponible para no perderte ninguna de las características actuales. Eso sí, si tu entorno de trabajo te obliga a usar una versión antigua, ten en cuenta que el código moderno podría no compilar allí; aunque, a la inversa, Java destaca por su excelente compatibilidad hacia atrás, lo que permite que programas antiguos funcionen sin problema en JDKs más modernos.

¿Dónde conseguimos esta herramienta? Es muy fácil. Puedes descargar la versión oficial de [Oracle en su sitio web](https://www.oracle.com/java/technologies/downloads/#jdk25-mac), o decantarte por una alternativa libre y de código abierto como [OpenJDK](https://jdk.java.net/archive/). Una vez que descargas el instalador y sigues los pasos ya estaría completa la ambientación en la máquina.

Ahora bien, una vez instalado el JDK, ¿con qué nos vamos a encontrar? Básicamente con dos herramientas principales que serán tus mejores amigas en la terminal. La primera es ***javac***, el compilador que traduce tu código humano en algo que la máquina entiende. La segunda es ***java***, el intérprete y lanzador de aplicaciones que pone todo en marcha.

Un detalle muy importante que debes tener en cuenta si vienes de otros entornos: el JDK no es un entorno de desarrollo integrado o IDE. Más bien es un conjunto esencial de programas que permiten a una persona trabajar con el lenguaje Java. 

Para trabajar cómodamente, existen IDEs especializados como [Cursor](https://cursor.com/es/download), [IntelliJ IDEA](https://www.jetbrains.com/es-es/idea/download/?section=mac), [Eclipse IDE](https://www.eclipse.org/downloads/) y [Netbeans](https://netbeans.apache.org/front/main/download/). 

Herramientas como Cursor son totalmente funcionales en su versión gratuita, e IntelliJ IDEA ofrece una potente edición Community sin coste alguno; mientras que NetBeans y Eclipse IDE son 100% gratuitos y de código abierto.


```java
void main() {
    System.out.println("Hello, World!");
}
```