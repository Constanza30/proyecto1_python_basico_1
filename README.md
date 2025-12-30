📊 #Proyecto 1: Limpieza y Preparación de Datos de Usuarios (Python Básico)

🧩 ##Descripción del proyecto

Este proyecto forma parte del Bootcamp de Análisis de Datos de TripleTen y tiene como objetivo evaluar la calidad de una muestra de datos de usuarios, identificar inconsistencias y aplicar técnicas básicas de limpieza y preparación de datos utilizando Python.

El dataset simula información de clientes de Store 1, incluyendo identificadores de usuario, nombres, edades, categorías de consumo y montos de gasto. El proyecto se enfoca en preparar estos datos para futuros análisis, asegurando coherencia, consistencia y facilidad de uso.

🎯 ##Objetivos del proyecto

Evaluar la calidad de los datos proporcionados por el cliente.

Identificar y corregir problemas comunes de datos (espacios, formatos, tipos incorrectos).

Aplicar operaciones básicas de limpieza y transformación de datos en Python.

Estructurar la información para facilitar análisis posteriores.

Practicar buenas prácticas iniciales en análisis de datos y manejo de errores.

🛠️ Herramientas y tecnologías utilizadas

Python 3

Tipos de datos básicos: listas, strings, enteros y flotantes

Métodos de strings: strip(), replace(), split(), lower()

Funciones integradas: int(), len(), sum(), sort()

Manejo de errores con try-except

Jupyter Notebook

📂 Estructura de los datos

Cada usuario está representado como una lista con los siguientes campos:

user_id: Identificador único del usuario

user_name: Nombre completo del usuario

user_age: Edad del usuario

fav_categories: Lista de categorías favoritas

total_spendings: Lista de montos gastados por categoría

🔍 Actividades principales realizadas

Identificación de problemas de calidad de datos:

Espacios innecesarios en nombres.

Uso de guiones bajos como separadores.

Tipos de datos incorrectos (edad como flotante).

Limpieza y estandarización de nombres.

Conversión de edades a tipo entero.

Separación de nombre y apellido en sublistas.

Ordenamiento de registros por ID de usuario.

Cálculo del gasto total por usuario.

Generación de mensajes formateados para reportes simples.

Creación de una nueva lista (users_clean) con los datos limpios.

📈 Hallazgos clave

Los datos crudos suelen contener inconsistencias simples pero críticas que afectan el análisis.

La estandarización temprana de formatos facilita cálculos y análisis posteriores.

El uso de try-except permite manejar errores y mejorar la robustez del código.

Incluso con estructuras de datos simples (listas), es posible aplicar principios fundamentales del análisis de datos.

✅ Buenas prácticas aplicadas

Limpieza de datos antes de cualquier análisis.

Uso de funciones y métodos nativos de Python.

Validación de tipos de datos.

Comentarios claros y código legible.

Preparación de datos orientada a escalabilidad futura.

📌 Limitaciones del proyecto

El procesamiento de usuarios se realiza de forma manual (sin bucles), ya que el objetivo del proyecto era practicar conceptos básicos de Python.

No se utilizan estructuras avanzadas como diccionarios o DataFrames (introducidos en sprints posteriores).

No se realiza análisis estadístico ni visualización en esta etapa.

🚀 Recomendaciones y siguientes pasos

Automatizar el procesamiento de usuarios mediante bucles (for).

Migrar la estructura de datos a diccionarios o Pandas DataFrames.

Aplicar funciones reutilizables para limpieza de datos.

Incorporar análisis exploratorio y visualizaciones en futuros proyectos.

📚 Recursos y referencias

Documentación oficial de Python: https://docs.python.org/3/

Python String Methods: https://docs.python.org/3/library/stdtypes.html#string-methods

TripleTen – Bootcamp de Análisis de Datos
