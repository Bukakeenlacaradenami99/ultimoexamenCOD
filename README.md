Plantilla para el readme

***Diagrama de clases***

1. Los podemos hacer en papel o en el programa de drawio
2. En el diagrama de clases establecemos todas las clases que van a ser utilizadas en el programa
3. Dentro de las clases ponemos sus nombres, atributos con sus modificadores de acceso y lo mismo para los metodos
4. Si hay clases que heredan, como hice en el ejercicio, las señalamos con sus flechas indicando de que clase hereda
5. Lo metemos en su paquete correspondiente y le ponemos un nombre. Los nombres tiene que ser por convenio para mejor entendimiento

**Diagrama de flujo**

1. Los podemos hacer en papel o en el programa de drawio
2. tenemos que establecer un inicio e indicar como va a ser el funcionamiento
3. mostrar los bucles y demás funciones que vamos a utilizar, todo en flechas hacia abajo
4. mostramos en pantalla lo que precisamos
5. Una vez hicimos todo lo anterior, lo exportamos como png

***Nos vamos al IDE***

**realizamos el jar**

1. Nos vamos a file y luego a project structure
2. Luego nos vamos a artifacts y le damos al signo +
3. Indicamos el directiorio donde vamos a meter el jar y después aplicamos y aceptar
4. Después nos vamos a build y luego build artifacts
5. le damos a build y el jar está creado en la carpeta out con la extensión .jar
6. etiquetamos el commit en el que hicimos el jar y hacemos push

***Creamos un repositorio en el que vamos a subir todo***

1. git add a la carpeta out
2. ahora etiquetamos el commit
3. utilizamos el comando git tag -a v1.0(lo de la version es opcional, podemos poner lo que queramos) -m "nombre del commit"
4. git remote add origin y ponemos la url del directorio
5. git push a lo que queremos subir más las etiquetas

**Nos vamos a GitHub**

1. Creamos la release
2. Nos vamos a release y la creamos seleccionando la etiqueta correcta o la que haya
3. creamos la release
4. Volvemos a repetir todo el proceso con todo lo explicado anteriormente

***volvemos a hacer lo mismo y modificamos el jar***

1. hacemos una modificacion en el programa
2. build y rebuild para volver a hacer el jar
3. volvemos a hacer el add, y una etiqueta al commit que vamos a subir
4. pusheamos todo con las etiquetas
5. volvemos al github y creamos una nueva release con la segunda version de la etiqueta

***hacer el javadoc***

Lo primero será entrar en el IDE y seleccionar el programa en el cual queremos hacer el javadoc.
Una vez lo tengamos, podemos empezar con los pasos para realizar el javadoc

**Pasos para realizar el javadoc**

Utilizamos comentarios antes de las clase y de los métodos, pero estos tienen que ser de cierta manera:
1. Los comentarios empiezan con ‘/**’
2. Utilizamos etiquetas para identificar las partes de nuestro codigo:
2.1 Al autor -> @author
2.2 La versión de la clase -> @version
2.3 Los parámetros de los métodos -> @param
2.4 Lo que retorna el método -> @return
3. Una vez que escribimos todos los comentarios, para generar el HTML, desde el menú:
Tools -> Generate JavaDoc
4. Elegir el directorio destino donde se pondrá nuestro javadoc
5. Elegir para sacar todos los métodos (private, package, protected, public)
6. Ver el resultado en el navegador
Una vez hemos hecho todo lo mencionado anteriormente, tenemos que enviar nuestro javadoc a github
¿Como hacemos eso?
De la misma manera que enviamos codigo, add, commit y push, pero eso no es todo.

**Meter nuestro javadoc en gitHub**

Una vez está subido el javadoc (debemos llamarlo docs al subirlo) hacemos lo siguiente:
1. Nos vamos al repositorio donde tenemos el javadoc y todo nuestro codigo asociado a él
2. Nos vamos a setting y en settings le damos a pages
3. Hay una opcion que pone branch, le damos y seleccionamos modificacion
4. Hay otra opcion que se llama selec folder, le damos y seleccionamos docs y save despúes
5. esperamos unos minutos y tendría que salirnos un enlace en el que poder acceder para ver nuestro javadoc
6. si realizamos todo bien, ya tendríamos nuestro javadoc

***incluir imagenes en el readme***

Imagenes del diagrama de flujo y diagrama de clases:

1. Diagrama de clases
![ejercicio COD futbol drawio](https://github.com/Bukakeenlacaradenami99/ultimoexamenCOD/assets/145834795/2d6f77c1-fbf9-4715-a9d9-625a6b0defb4)

2. Diagrama de flujo
![diagrama de flujo Futbol drawio](https://github.com/Bukakeenlacaradenami99/ultimoexamenCOD/assets/145834795/1dd9374a-39ff-45c5-a75d-1508243c2600)



