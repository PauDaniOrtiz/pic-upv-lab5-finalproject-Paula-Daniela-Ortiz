# Proyecto final Diseño de circuitos PIC

Este trabajo se basa en recrear el diseño del artpiculo titulado "Fabrication-Tolerant CWDM (de)Multiplexer Based on Cascaded Mach–Zehnder Interferometers on Silicon-on-Insulator", para ello se desarrollaron 5 archivos de Python.

1. Test de convergencia, este como busca los mejores parámetros de simulación para que con las guias de onda que se manejan en el trabajo (una ancha y una delgada) su indice efectivo sea el más estable. 

2. Distancia de seguridad, en este codigo se desarrollo una simulación para encontrar la distancia minima entre dos guias paralelas que no queremos que haga crosstalk. Esta distancia es de 1 um para las guias con las guias de 450 nm de ancho de SOI. 

3. Codigo principal (Main), aqui se realizo realmente la simulación de cada uno de los componentes y del dispositivo final, en donde se pudo realizar la demultiplexacion/multiplexación de los canales. 

4. Acoples DC proyecto, en este codigo se realizo la optimización de la longitud para tener los acoples que se solicitaban en el artículo. Así que sirve como soporte para las simulaciones del código principal.

5. Layout proyecto, en ese se realizo lodo el dibujo de los dispositivos del proyecto, obteniendo el layout final de este. Aqui no solo se dibujo uno de ellos, sino que se pusieron varios cwdm con variaciones en sus longitudes, así como tambien diferentes estructuras de test. 

