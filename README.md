# Glosario de programación

## 1. Algoritmo
Es una serie de pasos con la finalidad de resolver un problema.

**Ejemplo:** Las instrucciones para llegar a un lugar.

## 2. Programa
Es un conjunto de instrucciones escritas en un lenguaje de programación que una computadora necesita para realizar tareas.

**Ejemplo:** Escribir código en Python, JavaScript, etc.

## 3. Código fuente
Es el conjunto de archivos que contienen las instrucciones para hacer funcionar aplicaciones y programas en un lenguaje de programación.

**Ejemplo:** Son las líneas que escribes y guardas en un archivo (en Python sería algo como `programa.py`).

## 4. Lenguaje de programación
Es un lenguaje compuesto por símbolos y reglas de sintaxis y semántica bien definidas para escribir instrucciones que se utilizan para controlar las máquinas.

**Ejemplo:** Java, Python, C++, etc.

## 5. Sintaxis
Es el conjunto de reglas que definen las secuencias correctas de símbolos y elementos de un lenguaje de programación.

**Ejemplo:** Escribir en Python `println(Hola mundo)` en lugar de `println('Hola mundo')` (sin comillas) causará un error de sintaxis al no seguir las reglas del lenguaje.

## 6. Variable
Es un espacio en la memoria de la computadora identificado por un nombre único que almacena un valor capaz de cambiar al ejecutar un programa.

**Ejemplo:** Se puede utilizar la edad y un nombre para declararlas en las variables:

```python
edad = 21
nombre = "Juan"
```

## 7. Constante
Es un valor fijo que se asigna al inicio de un programa y no puede ser modificado durante su ejecución.

**Ejemplo:** El valor de `PI = 3.1416`

## 8. Tipo de dato
Es una clasificación o atributo que define el conjunto de valores posibles que puede almacenar una variable o estructura de datos, y qué operaciones se pueden realizar con el dato al que acompaña.

**Ejemplo:** Entero (`int`), flotante (`float`), cadena de texto (`str`), booleano (`bool`), ninguno / nulo (`None`).

## 9. Operador
Es un símbolo o palabra reservada que realiza cálculos aritméticos, comparaciones lógicas o asignaciones de valores dentro de un código.

**Ejemplo:** `+`, `-`, `*`, `/`, `**`, etc.

## 10. Expresión
Es una combinación de constantes, variables, operadores y funciones que se evalúa para producir un valor.

**Ejemplo:** `5 + 3` → `8`, `"hola" + "mundo"` → `"holamundo"`

## 11. Condicional
Son comandos del lenguaje de programación para la toma de decisiones. Específicamente, los condicionales realizan diferentes cálculos o acciones dependiendo de si una condición booleana es verdadera o falsa.

**Ejemplo:** `if` es usado para una condición, `else` es usado si esa condición no cumple con el resultado esperado.

```python
edad = 15
if edad >= 18:
    print("Eres mayor de edad")
else:
    print("Eres menor de edad")
```

## 12. Bucle
Es una estructura que permite repetir un bloque de código varias veces, sin tener que escribirlo una y otra vez.

**Ejemplo:** El bucle `for` (repite un número específico de veces, o recorre una colección):

```python
for i in range(5):
```

## 13. Función
Una función en programación es un bloque de código reutilizable con un nombre único diseñado para realizar una tarea específica.

**Ejemplo:**

```python
def saludar(nombre, idioma="español"):
    if idioma == "español":
        return f"Hola, {nombre}"
    elif idioma == "inglés":
        return f"Hello, {nombre}"
    else:
        return f"No conozco ese idioma"
```

## 14. Parámetro
Un parámetro es una variable que una función usa para recibir información de entrada.

**Ejemplo:**

```python
def saludar(nombre):
    print(f"Hola, {nombre}")
```

`nombre` es el parámetro.

## 15. Argumento
Un argumento es el valor real que le pasas a una función cuando la llamas o ejecutas.

**Ejemplo:**

```python
presentar("Juan", 21, "Mérida")
```

`"Juan"` es un argumento real.

## 16. Retorno
Un retorno es el valor que una función entrega como resultado después de terminar su ejecución.

**Ejemplo (en Python):**

```python
def sumar(a, b):
    resultado = a + b
    return resultado

total = sumar(3, 5)
print(total)  # 8
```

## 17. Arreglo
Un arreglo es una estructura de datos que almacena una colección de elementos, organizados en un orden específico y accesibles mediante un índice numérico.

**Ejemplo:**

```python
frutas = ["manzana", "plátano", "naranja", "uva"]
```

## 18. Objeto
Un objeto representa algo del mundo real o conceptual.

**Ejemplo:** Un carro, una persona o una cuenta bancaria.

## 19. Método
Un método es una función que pertenece a un objeto y que puede usar o modificar los datos de ese objeto.

**Ejemplo (Python):**

```python
frutas = ["manzana", "plátano"]
frutas.append("naranja")  # append es un método de la lista "frutas"
```

## 20. Evento
Un evento es una acción o suceso que ocurre en un programa y que el código puede "escuchar" y responder.

**Ejemplo (HTML/JavaScript):**

```html
<button onclick="saludar()">Saluda</button>

<script>
function saludar() {
    alert("¡Hola!");
}
</script>
```

---

## 21. Compilador
Es un programa capaz de traducir código legible por humanos a código de máquina legible por la computadora.

**Ejemplo:** GCC (GNU Compiler Collection).

## 22. Intérprete
Es un programa capaz de analizar y ejecutar otros programas de manera directa en tiempo real.

**Ejemplo:** CPython es el motor de ejecución estándar para el lenguaje Python.

## 23. Depurador (Debugger)
Es una herramienta utilizada para detectar, analizar y corregir errores (bugs) en otros programas.

**Ejemplo:** GDB (GNU Debugger), utilizado principalmente para lenguajes como C y C++, y el depurador de Python (PDB) para scripts en Python.

## 24. IDE (Integrated Development Environment)
Es una aplicación para facilitar el desarrollo de aplicaciones, juegos y sitios web.

**Ejemplo:** Eclipse y Visual Studio.

## 25. Editor de código
Es una herramienta diseñada para escribir, editar y organizar código fuente de programas.

**Ejemplo:** Visual Studio Code (VS Code).

## 26. Biblioteca (Library)
Es un conjunto de funciones, clases y rutinas prescritas que pueden ser utilizadas y reutilizadas por otros programas.

**Ejemplo:** NumPy (Python), una librería para cálculos numéricos, manejo de matrices y ciencia de datos.

## 27. Framework
Es una estructura predefinida que sirve de base para desarrollar software.

**Ejemplo:** Django y Flask para desarrollo web en Python.

## 28. API
Es un conjunto de reglas o protocolos que permiten que las aplicaciones de software se comuniquen entre sí para intercambiar datos, características y funcionalidades.

**Ejemplo:** Uso de Google Maps en Uber o Airbnb.

## 29. Repositorio
Es un almacén digital donde se almacena, organiza y gestiona el código fuente de un proyecto.

**Ejemplo:** Un repositorio en GitHub.

## 30. Control de versiones
Consiste en rastrear y gestionar los cambios realizados en archivos a lo largo del tiempo.

**Ejemplo:** Git, Subversion (SVN).

## 31. Git
Es un software de control de versiones.

**Ejemplo:** Permite guardar un historial de repositorios.

## 32. GitHub
Es una plataforma de desarrollo colaborativo para alojar proyectos y códigos fuente.

**Ejemplo:** Es usado principalmente para desarrollar software.

## 33. Rama (Branch)
Se refiere a una versión independiente del código del proyecto en la que se puede trabajar para corregir errores o experimentar sin afectar el código principal (`main` o `master`).

**Ejemplo:** En Git se usa para modificar código sin afectar al código principal.

## 34. Commit
Es una operación en la cual se confirman un conjunto de cambios provisionales de forma permanente.

**Ejemplo:** Al final de una transacción de base de datos.

## 35. Merge
Es el proceso de combinar cambios de diferentes ramas o versiones de un código base en una sola versión unificada.

**Ejemplo:** Un "merge" en Git:

```bash
# Empezar un nuevo feature branch desde main
git checkout -b new-feature main

# Editar archivos y hacer "commit" a los cambios
git add .
git commit -m "Start a feature"

# Cambiar de vuelta a main y combinar el feature
git checkout main
git merge new-feature

# Borrar el feature branch después de combinar (merge)
git branch -d new-feature
```

## 36. Callback
Es una función que se pasa como argumento a otra función para ser ejecutada después de que esta complete una tarea o evento.

**Ejemplo (JavaScript):**

```javascript
function loadData(callback) {
    // Simulate asynchronous data fetching
    setTimeout(() => {
        const data = "User Data";
        callback(data); // Invoke the callback with the result
    }, 1000);
}

// Pass a function as a callback
loadData((result) => {
    console.log("Loaded: " + result); // Runs after loadData completes
});
```

## 37. Programación síncrona
Es un modelo de programación en el que las operaciones se ejecutan de forma secuencial. Mientras una tarea está en curso, las demás se pausan, esperando su turno.

**Ejemplo:** Es ideal para herramientas de línea de comandos sencillas, como la manipulación de archivos o las operaciones aritméticas básicas en una aplicación de calculadora.

## 38. Programación asíncrona
Es un modelo de programación que permite ejecutar múltiples operaciones simultáneamente sin bloquear la ejecución de otras tareas.

**Ejemplo:** En lugar de esperar, puede seguir trabajando en una aplicación mientras se carga el cursor. Esto permite que la aplicación sea más receptiva.

## 39. JavaScript
Es un lenguaje de programación mayormente enfocado en crear interactividad y comportamiento dinámico en páginas web.

**Ejemplo:** Es usado en desarrollo web, aplicaciones móviles y de escritorio.

## 40. TypeScript
Es un superconjunto de JavaScript que añade tipado estático y se compila a JavaScript. Sirve para detectar errores en tiempo de desarrollo en lugar del tiempo de ejecución.

**Ejemplo:** TypeScript compila a JavaScript. El navegador nunca ve TypeScript; ve el resultado compilado en `.js`.

```typescript
function greet(name: string): string {
  return "Hello, " + name;
}

greet(42); // Error: Argument of type 'number' is not assignable to parameter of type 'string'
```

---

# Referencias

1. <https://universidadeuropea.com/blog/que-es-algoritmo/>
2. <https://phoenixnap.mx/glossary/what-is-a-program/>
3. <https://www.arimetrics.com/glosario-digital/codigo-fuente>
4. <https://www.lenovo.com/es/es/glossary/programming-language/>
5. <https://es.wikipedia.org/wiki/Lenguaje_de_programaci%C3%B3n>
6. <https://definicion.de/sintaxis/>
7. <https://www.lawebdelprogramador.com/diccionario/Variable/>
8. <https://www.carlospes.com/minidiccionario/constante.php>
9. <https://opencontent.upct.es/f0fc64e3b2d34f3a872a841a9c37b249/ad51b9751d8c4f83b7c4a500e0c4e80e/>
10. <https://www.adrformacion.com/knowledge/programacion/_que_es_un_operador_en_programacion_.html>
11. <https://www.luisllamas.es/programacion-operadores-y-expresiones/>
12. <https://academia-lab.com/enciclopedia/condicional-programacion-informatica/>
13. <https://phoenixnap.mx/glossary/what-is-a-loop/>
14. <https://newsletter.cuarzo.dev/p/que-es-una-funcion-en-programacion>
15. <https://www.alegsa.com.ar/Dic/parametro.php#gsc.tab=0>
16. <https://www.alegsa.com.ar/Dic/argumento.php#gsc.tab=0>
17. <https://oregoom.com/java/return/>
18. <https://programacion.top/conceptos/que-es-un-arreglo/>
19. <https://repositorio-uapa.cuaed.unam.mx/repositorio/moodle/pluginfile.php/3068/mod_resource/content/1/UAPA-Clases-Objetos/index.html>
20. <https://www.techtarget.com/whatis/definition/method>
21. <https://www.alegsa.com.ar/Dic/evento.php#gsc.tab=0>
22. <https://phoenixnap.mx/glosario/que-es-un-compilador>
23. <https://es.scribd.com/document/558890184/GNU-Compiler-Collection>
24. <https://www.alegsa.com.ar/Dic/interprete.php#gsc.tab=0>
25. <https://es.wikipedia.org/wiki/Depurador>
26. <https://pablogarciajc.com/blog/fundamentos-de-programacion/que-es-ide/>
27. <https://universidadeuropea.com/blog/editor-codigo/>
28. <https://www.inabaweb.com/que-es-una-biblioteca-en-programacion/>
29. <https://ebac.mx/blog/frameworks>
30. <https://www.ibm.com/mx-es/think/topics/api>
31. <https://aws.amazon.com/es/what-is/repo/>
32. <https://www.atlassian.com/es/git/tutorials/what-is-version-control>
33. <https://git-scm.com/>
34. <https://github.com/about?locale=es-419>
35. <https://www.codecademy.com/resources/docs/git/branch>
36. <https://es.wikipedia.org/wiki/Commit>
37. <https://teamhub.com/blog/understanding-code-merge-a-crucial-aspect-of-software-development/>
38. <https://msmk.university/que-es-un-callback/>
39. <https://clickup.com/es-ES/blog/236044/programacion-sincrona-frente-a-programacion-asincrona>
40. <https://charisma.edu.eu/insight/what-is-javascript-used-for/>
41. <https://www.mindstudio.ai/blog/what-is-typescript>
