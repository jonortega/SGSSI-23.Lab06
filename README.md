# SGSSI-23.Lab06.Actividad1

## Función
Toma como entrada dos ficheros de texto y obtiene como salida el resultado de comprobar las siguientes condiciones:
- El segundo de los dos ficheros de texto de entrada comienza exactamente por los mismos contenidos que el primero.
- El segundo fichero finaliza con una línea que concatena:
  - Una secuencia de 8 caracteres en hexadecimal (minúscula)
  - Un separador (\t)
  - El identificador público del estudiante (fe)
  - Un separador (\t)
  - La secuencia "100"
- El resumen SHA-256 del segundo fichero en versión hex tiene como prefijo una secuencia de 0’s.

## Cómo usar
1. Clonar el repositorio mediante la URL.
   ```
    git clone https://github.com/jonortega/SGSSI-23.Lab05.A3.git
   ```
2. Entrar en la carpeta y ejecutar el fichero `Actividad3.py` usando Python3:
   ```{python}
    # Windows
    python .\Actividad3.py

    # Mac o Linux
    python3 ./Actividad3.py
   ```
3. Hacer pruebas con los diferentes ficheros que se encuentran en la carpeta. Deberían de salir los siguientes resultados:
   | Fichero 1          | Fichero 2       | Resultado |
   | :----------------- | :-------------- | :-------: |
   | SGSSI-23.CB.02.txt | Output.txt      |   True    |
   | SGSSI-23.CB.02.txt | FakeOutput1.txt |   False   |
   | SGSSI-23.CB.02.txt | FakeOutput2.txt |   False   |