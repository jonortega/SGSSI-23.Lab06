# SGSSI-23.Lab06.Actividad1

## Función
Toma como entrada un fichero base y una carpeta con ficheros candidatos. Obtiene como salida el fichero condidato que tenga como resumen SHA-256 con más ceros como prefijo y además cumpla las siguientes condiciones:
- El segundo de los dos ficheros de texto de entrada comienza exactamente por los mismos contenidos que el primero.
- El segundo fichero finaliza con una línea que concatena:
  - Una secuencia de 8 caracteres en hexadecimal (minúscula)
  - Un separador (\t)
  - El identificador público del estudiante ([0-9a-f]{2})
  - Un separador (\t)
  - La secuencia "100"
- El resumen SHA-256 del segundo fichero en versión hex tiene como prefijo una secuencia de 0’s.

## Cómo usar
1. Clonar el repositorio mediante la URL.
   ```
    git clone https://github.com/jonortega/SGSSI-23.Lab06.git
   ```
2. Entrar en la carpeta y ejecutar el fichero `Actividad1.py` usando Python3:
   ```{python}
    # Windows
    python .\Actividad1.py

    # Mac o Linux
    python3 ./Actividad1.py
   ```
3. Comprobar los resultados devueltos por la terminal.