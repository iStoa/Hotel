En las situaciones de las PYME suele suceder que no tienen los ingresos o la innovación tecnología que necesitan para agilizar sus procesos, llega a suceder que esto bloquea ventajas competitivas contra otros servicios similares en el área- Lo que se propuso es el desarrollo de una un programa para gestionar las habitaciones de hotel “el fresno” En valle de bravo. Lo que permitirá tener un control mas simple y visual que el que ahora tienen. Se pretendió el desarrollo de la aplicación web con una arquitectura MVC que es común utilizar para los sistemas de información para la gestión de recursos en las distintas áreas. 

Requerimientos.
-Apache Tomcat 8.0.1
-MySql
-Utilizar JDK 11

Instalación
Buscar JDK 11 para el entorno de desarrollo
Instalar JDK 11
Descargar apache NetBeans desde el sitio oficial . https://netbeans.apache.org/
Buscar la versión más reciente e instalar .
Configurar el entorno

Pruebas manuales 
1.	Lo primero que se debe hacer es incluir como dependencia a JUnit 5 en el código, dentro del scope de “test”, para que cuando este se empaquete la dependencia no sea incluida, ya que solo será requerida para los test. 
2.	Una vez hecho eso genera un paquete y ponle el nombre que consideres, por ejemplo: prueba unitaria #1.
3.	Dentro del mismo genera una clase que se llame ‘Operation Test’, el cual se encargará de hacer la prueba unitaria que necesites.
4.	Como en este ejemplo, vamos a hacer una prueba unitaria acerca de la suma de dos valores, debes generar un método que no regresará nada (should return sum two numbers). 
5.	Luego, hay que seguir la estructura When-Given-Then. En donde: en When debes poner las condiciones que debe cumplir el código. En Given debes poner cuál es la operación que se va a medir. Y en Then pruebas que el código llega al resultado esperado.

6.	Y cuando ya tengas listo todo el código de la prueba unitaria, ejecutas el test unitario.

7.	Si el código que fue puesto a prueba está bien, el resultado debe tener un chulo verde.


Configuración 
Revisar que tengan el servidor en línea
JDK 11


Uso
El sistema abrira un login de inicio
Al iniciar sesión abrirá la vista de reservaciones, huéspedes, habitaciones, personal.
Cada una de las opciones a seleccionar tienen campos distintos para manipular
Cada registro se guardará
Cada vista tendrá información relevante a la clase
El usuario podrá navegar por la aplicación entre clases y haciendo uso de cada acción 

Contribución 
Clonar repositorio 
1.	GitHub.com, visita la página principal del repositorio.
2.	Sobre la lista de archivos, da clic en  Código.
3.	abre la Git Bash.
4.	Cambia el directorio de trabajo actual a la ubicación en donde quieres clonar el directorio.
5.	Escribe git clone, y luego pega la URL que copiaste antes.
6.	Copia la URL del repositorio.
7.	Presiona Enter para crear tu clon local.

Nuevo Branch 
Comando git git checkout -b ＜new-branch＞


Roadmap
Si el negocio llegara aumentar las áreas del servicio ocupara una nueva intergacion de clase y modificación de base de datos 
