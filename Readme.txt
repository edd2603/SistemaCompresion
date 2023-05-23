Proyecto de Compresión de Texto con Algoritmo de Huffman

Este proyecto implementa el algoritmo de compresión de Huffman en Python, que permite reducir el tamaño de archivos de texto utilizando códigos Huffman.
El algoritmo asigna códigos más cortos a los caracteres más frecuentes y códigos más largos a los caracteres menos frecuentes, 
lo que resulta en una compresión eficiente.
----------------------------------------------------------------------------------------------------------------------------------------------------------

Proceso de Compresión

El proceso de compresión consta de los siguientes pasos:

* Lectura del archivo de texto: Se carga el archivo de texto de entrada.
* Cálculo de frecuencias: Se calcula la frecuencia de cada carácter en el texto.
* Construcción del árbol de Huffman: Se construye un árbol de Huffman utilizando las frecuencias de los caracteres.
* Generación de códigos Huffman: Se generan los códigos Huffman para cada carácter en el árbol.
* Codificación del texto: Se codifica el texto original utilizando los códigos Huffman.
* Cálculo de la tasa de compresión: Se calcula la tasa de compresión en porcentaje.
* Decodificación del texto: Se decodifica el texto codificado utilizando los códigos Huffman.
* Guardado del archivo codificado: Se guarda el contenido codificado en un archivo de texto.

----------------------------------------------------------------------------------------------------------------------------------------------------------
Instalación

Para utilizar este proyecto, se deben seguir los siguientes pasos:

* Clonar el repositorio, descargar los archivos del proyecto desde GitHub por medio del TAG https://github.com/edd2603/SistemaCompresion/tags, o visualizar desde el mismo repositorio

* Al descargar el tag desde GitHub, abrir el codigo en un bloc de notas y ejecutarlo en el Colab

* Asegurarse de ejecutar el proyecto en un nuevo cuaderno de Google Colab.

Instalar las dependencias necesarias ejecutando el siguiente comando:

-----------------------------
pip install bitarray
-----------------------------

----------------------------------------------------------------------------------------------------------------------------------------------------------
Uso

Para utilizar el algoritmo de compresión de Huffman, se deben seguir los siguientes pasos:

* Ejecutar el script "sistema de compresión.ipynb" en Google Colab.
* Seleccionar el archivo de texto que se desea comprimir.
* El resultado de la compresión se mostrará en la consola, incluyendo la tasa de compresión y el contenido codificado.
* El archivo codificado se guardará en el archivo texto_codificado.txt en el directorio del proyecto.

----------------------------------------------------------------------------------------------------------------------------------------------------------
Referencias

No se utilizaron referencias externas para este proyecto. 
El algoritmo de compresión de Huffman es ampliamente conocido y su implementación se basa en su descripción y lógica subyacente.
