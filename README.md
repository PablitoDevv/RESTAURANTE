# Universidad
University things

Bienvenido a mi proyecto de restaurante!

Cómo usar:

Requisitos: 
-Tener instalado xampp para manejar mysql

A) DESCOMPRIMIR ARCHIVO PARA USARLO EN VISUAL STUDIO CODE

1°Descomprimir archivo RESTAURANTE en carpeta htdocs de xampp para poder usarlo

Ejemplo: C:\xampp\htdocs\


B) Base de datos en mysql

1°Abrir xampp
2°Iniciar apache y MYSQL
3°Presionar ADMIN en MYSQL
4°Una vez abierto el phpMyAdmin crear base de datos. Para ello tendremos que crear la base de datos

Presionar arriba a la izquierda "Nueva", como nombre de base de datos colocaremos "restaurante" y le damos a crear.

5° Una vez creada la base de datos, importaremos su archivo SQL. Presionaremos nuestra base de datos creada, importar archiv "restaurante.sql" de winrar extraido y presionar
botón importar.

6°Abrir cmd y escribir: cd /xampp/htdocs/restaurante
y escribir code .

Ya estamos terminando, ya tenemos la base de datos creada y el visual studio code con el código fuente del sistema.

Para probar nuestro proyecto. Abriremos cualquier navegador y escribiremos: localhost/restaurante

Estas son las crédenciales de los empleados
+---------+----------+------------+--------+--------+
| staffID | username | password   | status | role   |
+---------+----------+------------+--------+--------+
|       1 | Juan     | 1234abcd.. | Online | chef   |
|       4 | Pedro    | 1234abcd.. | Online | Mesero |
|      10 | Chileno  | 1234abcd.. | Online | Mesero |
+---------+----------+------------+--------+--------+

Y estos son de los administradores

+----+----------+------------+
| ID | username | password   |
+----+----------+------------+
|  0 | admin    | 1234abcd.. |
|  1 | Chileno  | 1234       |
+----+----------+------------+

Espero que este proyecto te sea útil!












