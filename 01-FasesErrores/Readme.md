*Compilador usado :MinGw
**************Preprocesador********************** 
1.- Preprocesar hello2.c, no compilar, y generar hello2.i. Analizar su contenido.
comando usado :gcc -E HELLO2.C > HELLO2.i
Me saco los comentarios y el #include,muestras las ubicaciones de las libreria estandar.
2. Investigar la semántica de la primera línea."int printf(const char *s, ...);"
La funcion printf recibe como argumento un puntero  de tipo char.
3. Preprocesar hello3.c, no compilar, y generar hello3.i. Buscar diferencias entre hello3.c y hello3.i.
---comando usado gcc -S HELLO3.c
Me salio un warning que la funcion prontf no se encuentra declarada.
---La diferencia que encuentro entre los dos archivos es que el archivo hello3.i  se le quito los espacios entre lineas .
***************Ensamblador**************************
4. Compilar el resultado y generar hello3.s, no ensamblar

*******************Objeto************************************************

comando usado : as -o HELLO4.o HELLO4.s

