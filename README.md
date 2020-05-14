# DRIVER-PARA-UN-EMISOR-LIDAR
Este driver se va a implementar sobre la herramienta de diseño LTSpice
Se adjuntan los zip de los componentes EPC2001(FET) y el amplificador de alto rendimiento LMG1020 asi como el esquematico para LTSpice.
Se adjutan tambien una serie de imagenes(cambiar de rama a imagenes) de la simulacion deseada para la obtencion de un pico de intensidad de 40 Amperios en un tiempo menor a 0.5us.
-Para poder implementar el circuito es necesario primero descomprimir dichos componentes y añadirlos a la libreria de LTSpice, un ejemplo para añadirlos: https://www.youtube.com/watch?v=Dke_-1TDZ-Q&t=119s
-Una vez añadidos puedes configurar el driver en funcion del pico de intensidad deseado en el diodo.
-Para realizar la simulacion es necesario que la fuente de voltaje V1 sea de tipo independiente y que conforme un pulso, el comando de simulacion debe ser .tran con tiempo de simulacion muy corto.
https://epc-co.com/epc/Portals/0/epc/documents/datasheets/EPC2001_datasheet.pdf
https://www.ti.com/product/LMG1020
