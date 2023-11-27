# Im-gen-Panor-mica
Una imagen panorámica puede ser una vista amplia y expansiva de un paisaje o escena que abarca un amplio campo visual. Puede capturar una extensión considerable de terreno, ya sea natural o urbano. 
<img width="562" alt="1111" src="https://github.com/PeluffoS/Im-gen-Panor-mica/assets/150092739/2d063f11-52ca-4c6c-af11-15c352374780">

 ¿Alguna vez te has preguntado cómo funciona este método de edición de fotografías? Bueno, lo descubrirás pronto, solo continúa leyendo esta publicación. Le mostraremos cómo crear una imagen panorámica en Python usando OpenCV.
# 1. ¿Qué es una imagen panorámica?
   
La fotografía panorámica es una técnica que combina varias imágenes de la misma cámara giratoria para formar una única fotografía amplia. Captura imágenes con campos alargados horizontal o verticalmente. Este proceso de combinar varias fotografías para producir un panorama se llama unión de imágenes. Entonces, después de rotar una cámara para producir un efecto completo de 360 ​​grados o menos, uniremos esas imágenes para obtener una foto panorámica.

#¿Qué es la unión de imágenes?

Al inicio del proceso de costura, como entrada, tenemos varias imágenes con áreas superpuestas. El resultado es una unificación de estas imágenes. Es importante tener en cuenta que durante el proceso se debe conservar una escena completa de la imagen de entrada.

# 2. ¿Cómo crear una imagen panorámica – descripción general?

El proceso de creación de una imagen panorámica consta de los siguientes pasos. 

Detectar puntos clave y descriptores
Detectar un conjunto de puntos coincidentes que está presente en ambas imágenes (área superpuesta)
Aplicar el método RANSAC para mejorar la detección del proceso de coincidencia.
Aplicar transformación de perspectiva en una imagen usando la otra imagen como marco de referencia
Unir imágenes
Para una mejor comprensión ilustramos todos estos pasos en el siguiente gráfico.

![Picture2-794x1024](https://github.com/PeluffoS/Im-gen-Panor-mica/assets/150092739/ec5d284a-11b1-4df3-aa35-66feff8d8819)

# Referencias

[1]Alineación de imágenes (basada en funciones) usando OpenCV (C++/Python) por Satya Mallick
