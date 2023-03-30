# Dia_88
Encuentro Día 88 de Excepciones - Ejercicio 6-9
<dbr>
<br>
Para su ejecución, es necesario incluir la librería que se detalla a continuación, en ella se encuentra todos las Entidades (Objetos), Servicios y 
Utilidades, relacionados con los ejercicios de todas las guías.
<br>
<br>
Link Librería: https://github.com/FullStackEggDRoa/libreria_comun.git
<br>
<br>
# Desde Netbeans: 
Propiedades de Proyecto / Librerías / Class Path / Adicionar Proyecto (Add Project) / (Ubicar Directorio Librería)
# Respuestas:
<h2> Ejercicio 6:
<br>
a) Orden a1,a2, a6 -> Con Exception MioException
<br>
b) Orden a1,a2,a3,a4,a5 -> Sin Exception MioException
<br>
<h2> Ejercicio 7:
<br>
a) Orden b1,a3,b4 ->  Con Exception MioException
<br>
b) Orden b1,b2,b4 -> Sin Exception MioException
<br>
<h2> Ejercicio 8:
<h3> Clase Uno:
<br>
Valor final del try :44
<br>
Valor final del finally: 45
<br>
Valor antes del return: 46
<br>
46
<br>
<h3> Clase Dos:
<br>
Valor final del catch: 43
<br>
Valor final del finally: 44
<br>
Valor antes del return: 45
<br>
45
<h3> Clase Tres:
<br>
Valor final del finally: 2
<br>
Excepcion en metodo()
<br> 
java.lang.NumberFormatException: For input string: "W"
<br>
	at java.base/java.lang.NumberFormatException.forInputString(NumberFormatException.java:67)
<br>
	at java.base/java.lang.Integer.parseInt(Integer.java:665)
<br>
	at java.base/java.lang.Integer.parseInt(Integer.java:781)
<br>
	at Entidades.Tres.metodo(Tres.java:20)
<br>
	at Entidades.Tres.main(Tres.java:33)
<br>
<h2> Ejercicio 9:
<br>
a) Orden c1,c4,c5,c6 ->  Con Exception MioException
<br>
b) Orden c1,c2,c3,c5,c6 -> Sin Exception MioException
<br>
c) Orden ?
