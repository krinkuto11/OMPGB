---
description: En esta sección se pueden encontrar los ejemplos utilizados en la presentación
---

# Ejemplos de programas

{% hint style="info" %}
Hace falta configurar la propiedad numeroHilos en cada programa (Excepto Hola Hilos) acorde a la cantidad de hilos que tiene el sistema en el que se va a ejecutar
{% endhint %}

### Hola Hilos

[Descargar](https://github.com/krinkuto11/EjemplosOMP/blob/87a143515858a6d2da2c393250c3fa0ff42ad5d5/Hola%20Hilos/1.Hola%20Hilos.c)

### Series de Leibniz (Interacciones de PI)

* [Secuencial](https://github.com/krinkuto11/EjemplosOMP/blob/87a143515858a6d2da2c393250c3fa0ff42ad5d5/Leibniz/2.Leibniz%20Secuencial.c)
* [Paralela](https://github.com/krinkuto11/EjemplosOMP/blob/87a143515858a6d2da2c393250c3fa0ff42ad5d5/Leibniz/2.Leibniz%20Paralela.c)
* [Paralela Optimizada](https://github.com/krinkuto11/EjemplosOMP/blob/87a143515858a6d2da2c393250c3fa0ff42ad5d5/Leibniz/2.Leibniz%20Paralela%20Optimizado.c)

### Sucesión de Fibonacci

{% hint style="info" %}
Es necesario usar la flag -lm para compilar con éxito los programas "Secuencial Matemática" y "Paralela Matemática"
{% endhint %}

* [Secuencial Recursiva](https://github.com/krinkuto11/EjemplosOMP/blob/87a143515858a6d2da2c393250c3fa0ff42ad5d5/Fibonacci/3%20Fibonacci%20Secuencial%20Recursiva.c)
* [Paralela Recursiva](https://github.com/krinkuto11/EjemplosOMP/blob/87a143515858a6d2da2c393250c3fa0ff42ad5d5/Fibonacci/3%20Fibonacci%20Paralela%20Recursiva.c)
* [Secuencial Matemática](https://github.com/krinkuto11/EjemplosOMP/blob/87a143515858a6d2da2c393250c3fa0ff42ad5d5/Fibonacci/3%20Fibonacci%20Secuencial%20F%20Matema%CC%81tica.c)
* [Paralela Matemática](https://github.com/krinkuto11/EjemplosOMP/blob/87a143515858a6d2da2c393250c3fa0ff42ad5d5/Fibonacci/3%20Fibonacci%20Paralela%20F%20Matema%CC%81tica.c)

### Multiplicación de Matrices

{% hint style="info" %}
Es necesario definir el rango de las matrices dentro del programa antes de compilarlo
{% endhint %}

* [Multiplicación Secuencial](https://github.com/krinkuto11/EjemplosOMP/blob/a0602f43da71ad96756d537354c183e26e1ee583/Multiplicacio%CC%81n%20Matrices/mulMatSec.c)
* [Multiplicación Paralela](https://github.com/krinkuto11/EjemplosOMP/blob/a0602f43da71ad96756d537354c183e26e1ee583/Multiplicacio%CC%81n%20Matrices/mulMatParalelo2.c)
