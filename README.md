

En este documento se explica el funcionamiento del proyecto “Trayectorias”, el      
cual funciona con un programa en C++ que cuenta con un ambiente gráfico y una       
librería desarrollada en C que realiza todo el procesamiento de los datos, basada  
en el programa desarrollado por Miguel Eduardo Venegas Monroy en Matlab.              


El objetivo de este proyecto es el desarrollo de un software que provea la capacidad  
de que un usuario pueda ingresar ciertos puntos en un plano (X,Y) por medio de una  
interfaz gráfica y, que por medio de unos cálculos de interpolación, te retorne   
la misma gráfica pero con curvas más suaves.

Este proyecto consta de dos partes:

● C++: La primera parte esta desarrollada en el lenguaje C++, es la encargada
de proveer   
la interfaz gráfica con la que el usuario interactúa. Donde esté
ingresa los datos y muestra los resultados.

● C: La segunda parte es desarrollada en el lenguaje C, esta es la encargada
de la realización  
de todos los cálculos que se requieren, Como lo son los
cálculos de la interpolación, primera y    
segunda derivada. Para mayor
practicidad esta parte se implementó como una librería .h para   
ser incluida en
la parte del programa en C++.