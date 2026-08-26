# Propedeutico de Programación para el Análisis de Datos

### EGobiernoyTP, Verano 2026

¡Bienvenid@s!

El objetivo de este propedéutico es familiarizarlos con los fundamentos de la programación y brindarles las herramientas necesarias para comenzar a trabajar con datos de manera autónoma.

El curso estará enfocado en **Python**, un lenguaje muy versátil y ampliamente utilizado para el análisis de datos. No se requiere experiencia previa en programación. La idea es que, al finalizar el propedéutico, puedan sentirse cómodos trabajando con Python y sean capaces de cargar, explorar, transformar y analizar sus propias bases de datos.

Comenzaremos trabajando en Google Colab y posteriormente aprenderemos a configurar y utilizar Python directamente en sus computadoras.

### Horarios y modalidades

- **Modalidad virtual:** 6:30 a 8:00
- **Modalidad presencial (Mixcoac):** 8:00 a 9:30

**IMPORTANTE:** La modalidad asignada deberá mantenerse durante todo el propedéutico. Si están inscritos en modalidad virtual, deberán asistir de manera virtual; si están inscritos en modalidad presencial, deberán asistir presencialmente.

### Asistencia y puntualidad

- La asistencia se registrará **todos los días y es obligatoria**.

    - En la modalidad virtual, el pase de lista se realizará en un **momento aleatorio durante la sesión**, por lo que es importante conectarse puntualmente y permanecer presentes durante toda la clase.

    - Para la modalidad presencial también se requiere puntualidad y asistencia durante la sesión completa.

### Material del curso

Todo el material, ejercicios, notebooks, bases de datos e instrucciones del propedéutico estarán disponibles en este repositorio.

Es importante revisar el repositorio regularmente, ya que será nuestro principal medio para organizar y distribuir los materiales del curso.

## Temario

### 1. Introducción a programación, Python y notebooks

1.  ¿Qué significa programar?
    - Instrucciones, datos y resultados
    - ¿Qué es y por qué Python? 
    - Código, intérprete y ejecución
2.  ¿Dónde ejecutamos Python?
    - Google Colab
    - Jupyter Notebook
    - Diferencias entre Python, Jupyter y Colab
    - Celdas de código y texto
    - Orden de ejecución de las celdas
3. Primeros pasos
    - `print()`
    - Comentarios
    - Errores como parte de la programación
    - Cómo leer un mensaje de error

### 2. Fundamentos de Python

1.  Variables y asignación
    - Crear y modificar variables
    - Asignación `=`
    - Comparación `==`
    - Nombres de variables
2.  Tipos de datos
    - Booleanos
    - Númericos: `int`y `float`
    - Strings
    - `None`
    - `type()`
    - Conversión entre tipos
3. Operadores
    - Aritméticos
    - Comparación
    - Lógicos
4. Strings
    - Operaciones básicas
    - Indexación
    - Slicing
    - Métodos básicos
    - f-strings
7. Estructuras de datos
    - Listas
    - Diccionarios
    - Tuplas y sets
    - Indexación y acceso a elementos

### 3. Control y flujo de funciones

1. Condicionales
    - `if`
    - `elif`
    - `else`
    - Combinar condiciones con `and`, `or` y `not`
2. Loops
   - `for`
   - `range()` y `enumerate()`
   - Mención de `while`
3. Funciones
   - ¿Por qué crear funciones?
   - Parámetros y argumentos
   - `return`
4. Reconocer diferentes formas de trabajar con Python
    - Variables: `x`
    - Funciones: `len(x)`
    - Métodos: `x.mean()`
    - Atributos: `x.shape`


### 4. Archivos, carpetas y paquetes

1. Archivos y carpetas
   - ¿Qué es una ruta?
   - Directorio de trabajo
   - Rutas absolutas y relativas, y extensiones de archivos
   - ¿Dónde está buscando Python mi archivo?
2. Trabajar con archivos en Colab
   - Subir archivos
   - Google Drive
   - Leer un CSV
3. Paquetes
   - ¿Qué es un paquete?
   - `import`
   - Alias: `import pandas as pd`
   - Instalar vs. importar
   - ¿Por qué algunas funciones requieren paquetes?
4. Introducción a NumPy
   - ¿Qué es un array?
   - Diferencia conceptual entre lista y array
   - Operaciones vectorizadas


### 5. Introducción a pandas: conocer nuestros datos

1. ¿Qué es una base de datos?
   - Observaciones y variables
   - Tablas
   - Diccionario de variables
   - Datos tidy
2. Series y DataFrames
   - ¿Qué es una Series?
   - ¿Qué es un DataFrame?
   - Filas, columnas e índice
3. Cargar datos
   - `pd.read_csv()`
   - Mención de Excel y otros formatos
4. Primera exploración
   - `head()`
   - `tail()`
   - `sample()`
   - `shape`
   - `columns`
   - `info()`
   - `describe()`
5. Conocer los valores de una variable
   - `unique()`
   - `nunique()`
   - `value_counts()`


### 6. pandas: seleccionar, limpiar y transformar datos

1. Seleccionar columnas
   - Una columna
   - Varias columnas
   - Series vs. DataFrame
2. Seleccionar observaciones
   - Filtrar mediante condiciones
   - Combinar condiciones
   - `loc`
   - Mención de `iloc`
3. Tipos de datos
   - Strings
   - `int`
   - `float`
   - Booleanos
   - `datetime`
   - Cambiar tipos
4. Valores faltantes
   - ¿Qué es `NaN`?
   - `isna()`
   - `dropna()`
   - `fillna()`
5. Ordenar datos
   - `sort_values()`
6. Crear y modificar variables
   - Operaciones aritméticas
   - Comparaciones
   - Operaciones básicas con texto
   - Variables derivadas
7. Eliminar y renombrar columnas
8. Índice y `reset_index()`


### 7. pandas: resumir y combinar información

1. Estadística descriptiva básica
   - Media
   - Mediana
   - Mínimo y máximo
   - Conteos
   - Proporciones
2. Agrupar información
   - `groupby()`
   - `agg()`
   - Agrupar por una o más variables
3. Combinar bases de datos
   - ¿Por qué tenemos información en diferentes tablas?
   - Llaves o identificadores
   - Tipos de joins
   - `merge()`
   - Identificar observaciones que no hicieron match


### 8. Exploración descriptiva y visualización de datos

1. Introducción al análisis exploratorio de datos
   - ¿Qué queremos conocer de nuestros datos?
   - EDA y GEDA
   - Análisis univariado y bivariado
2. Tipos de variables
   - Categóricas
   - Numéricas
   - Temporales
   - Texto
   - Mención de datos geográficos
3. Elegir una visualización
   - Barras
   - Histogramas
   - Boxplots
   - Scatterplots
   - Series de tiempo
4. Principios básicos de visualización
   - Elegir la gráfica según la pregunta
   - Ejes y escalas
   - Etiquetas
   - Evitar gráficas innecesariamente complejas
5. Ejercicio de análisis
   - Formular una pregunta
   - Explorar los datos
   - Obtener un resultado
   - Visualizarlo
   - Interpretarlo

### 9. De Colab a mi computadora: Python local

1. ¿Qué cambia al dejar Colab?
   - Python ahora corre en mi computadora
   - Los archivos están en mi computadora
   - Los paquetes están instalados en mi ambiente
2. La terminal
   - ¿Qué es?
   - `pwd`
   - `ls`
   - `cd`
   - `mkdir`
   - Diferencia entre comandos de terminal y código Python
3. Instalación de Python y herramientas
   - Python
   - Editor/Jupyter
   - Verificar la instalación
4. Ambientes virtuales
   - ¿Qué problema resuelven?
   - Crear un ambiente
   - Activarlo
   - Instalar paquetes
5. Jupyter local
   - Abrir un notebook
   - Seleccionar el kernel
   - Ejecutar el mismo notebook utilizado en Colab
6. Estructura mínima de un proyecto


### 10. SQL básico desde Python

1. ¿Por qué existen las bases de datos?
   - CSV/Excel vs. bases de datos
   - Tablas
   - Filas y columnas
   - Llaves
2. SQL básico
   - `SELECT`
   - `FROM`
   - `WHERE`
   - `GROUP BY`
   - `ORDER BY`
   - `LIMIT`
   - Mención de `JOIN`
3. SQL desde Python
   - SQLite
   - Ejecutar una consulta
   - Cargar el resultado como DataFrame de pandas



### 11. Errores, debugging, documentación e IA

1. Errores comunes
   - `SyntaxError`
   - `NameError`
   - `TypeError`
   - `KeyError`
   - `FileNotFoundError`
   - Indentación
2. Cómo leer un traceback
   - Identificar dónde ocurrió el error
   - Leer la última línea
   - Identificar el tipo de error
3. Estrategias de debugging
   - Ejecutar código por partes
   - Inspeccionar variables
   - Revisar tipos
   - Revisar dimensiones
   - Probar ejemplos pequeños
4. Buscar ayuda
   - `help()`
   - Documentación oficial
   - Búsquedas en internet
5. IA como apoyo para programar
   - Compartir contexto, código y error
   - Pedir explicación, no sólo una solución
   - Ejecutar y verificar el código sugerido
   - No asumir que el código generado es correcto


