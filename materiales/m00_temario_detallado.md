## Temario

### 1. Introducción a programación, Python y notebooks

1.  ¿Qué significa programar?
2.  ¿Qué es y cómo funciona Python? 
3.  ¿Dónde ejecutamos Python?
    - Jupyter Notebook y Google Colab
4. Celdas de texto y código
    - Orden de ejecución de las celdas
5. Primeros pasos
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


### 4. Python pre-análisis, paquetes y carga de datos

1. Reconocer diferentes formas de trabajar con Python
    - Variables: `x`
    - Funciones: `len(x)`
    - Métodos: `x.mean()`
    - Atributos: `x.shape`
2. Paquetes
   - ¿Qué es un paquete?
   - `import`
   - Alias: `import pandas as pd`
   - Instalar vs. importar
3. Trabajar con archivos en Colab
   - Subir archivos
   - Google Drive
   - Leer un CSV
4. Introducción a NumPy
   - ¿Qué es un array?
   - Diferencia conceptual entre lista y array
   - Operaciones vectorizadas


### 5. Introducción a pandas: conocer nuestros datos


1. Series y DataFrames
   - ¿Qué es una Series?
   - ¿Qué es un DataFrame?
   - Filas, columnas e índice
2. Primera exploración
   - `head()`
   - `tail()`
   - `sample()`
   - `shape`
   - `columns`
   - `info()`
   - `describe()`
3. Conocer los valores de una variable
   - `unique()`
   - `nunique()`
   - `value_counts()`
4. Seleccionar columnas
   - Una columna
   - Varias columnas
   - Series vs. DataFrame
5. Tipos de datos
   - Strings
   - `int`
   - `float`
   - Booleanos
   - `datetime`
   - Cambiar tipos


### 6. pandas: seleccionar, limpiar y transformar datos

1. Seleccionar observaciones
   - Filtrar mediante condiciones
   - Combinar condiciones
   - `loc`
   - Mención de `iloc`
2. Valores faltantes
   - ¿Qué es `NaN`?
   - `isna()`
   - `dropna()`
   - `fillna()`
3. Ordenar datos
   - `sort_values()`
4. Crear y modificar variables
   - Operaciones aritméticas
   - Comparaciones
   - Operaciones básicas con texto
   - Variables derivadas
5. Eliminar y renombrar columnas
6. Índice y `reset_index()`


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


