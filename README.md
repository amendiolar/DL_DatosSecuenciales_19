# Repositorio template para un workshop en RIIAA '19

En este repositorio se encuentra el material del taller de Deep Learning para Datos Secuenciales. Su funcionamiento está orientado a que se ejecute en Colab, usando como almacenamiento google Drive. Para ejecutarlo es necesario copiar los notebook del taller a una carpeta en google drive e instalar Colab. Además deberá de configurarse el hardware para que use TPU. Se pueden cambiar las rutas de consulta de los datos y en donde guarda los vectores, diccionarios y pesos de la red neuronal.

En el notebook se exponen diferentes modelos, entrenados usando TPU, la versión de Python es 3 y la versión de tensorflow es 1.12.0 por lo que es necesario volver a instalarla.

## Organización del repositorio

La estructura del taller es la siguiente:

* **data/**: aqui está el corpus que se usó para el taller.
* **notebook/**:  notebooks donde se se muestra el codigo que se usa para entrenarlos
* **media/**: Algunos recursos visuales y articulos consultados.