---
title: ¿Qué es una función?
excerpt: >-
  A partir de este capítulo comenzamos con conceptos de programación. Por eso te quiero invitar a tomarte tu tiempo para leer cada capítulo. Cada capítulo te ayudará a entender los conceptos a través de analogías del mundo real y ejemplos prácticos.
date: '2022-03-07'
thumb_image: images/miniatura-que-es-una-funcion.png
thumb_image_alt: A picture of the author of the blog, Jesús Daniel Medina Cruz
image: images/miniatura-que-es-una-funcion.png
image_alt: A picture of the author of the blog, Jesús Daniel Medina Cruz
seo:
  title: Jesús Daniel Medina Cruz
  description: >-
    A partir de este capítulo comenzamos con conceptos de programación. Por eso te quiero invitar a tomarte tu tiempo para leer cada capítulo. Cada capítulo te ayudará a entender los conceptos a través de analogías del mundo real y ejemplos prácticos.
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: The Elements of Great Workplace Design
      keyName: property
    - name: 'og:description'
      value: >-
        Vis accumsan feugiat adipiscing nisl amet adipiscing accumsan blandit
        accumsan sapien blandit
      keyName: property
    - name: 'og:image'
      value: images/11.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: The Elements of Great Workplace Design
    - name: 'twitter:description'
      value: >-
        Vis accumsan feugiat adipiscing nisl amet adipiscing accumsan blandit
        accumsan sapien blandit
    - name: 'twitter:image'
      value: images/11.jpg
      relativeUrl: true
layout: post
---

A partir de este capítulo comenzamos con conceptos de programación. Por eso te quiero invitar a tomarte tu tiempo para leer cada capítulo. Cada capítulo te ayudará a entender los conceptos a través de analogías del mundo real y ejemplos prácticos.

Empecemos con el título de este capítulo. ¿Qué es una función?

# Definición de función

💡 Rutina almacenada para ser ejecutada en cualquier momento por cualquier actor.

Sí, a mí tampoco me queda claro. Tratemos de desmenuzar la definición.

## Rutina almacenada

Imagina una acción que practicas todos los días: Caminar, hablar, respirar. Sencillo? Bien. Todas estas son rutinas de algunos seres humanos. Digo algunos porque no todos podemos hablar, caminar o incluso respirar. Pero, ¿Tú si puedes? ¿Por qué?

En algún momento de tu vida alguien te enseñó a caminar, hablar, pero, ¿Quién te enseñó a respirar? Bueno, eso viene en tu ADN. Sin entrar en detalles, tus antepasados dejaron escrito en su ADN que era necesario respirar para sobrevivir.

Todas estas rutinas están almacenadas en tu ADN y tu cerebro.

## Para ser ejecutada en cualquier momento

Retomando las rutinas. Si tú puedes caminar, no es como que todo el tiempo estés caminando. Así mismo las funciones necesitan ser ejecutadas para llevarse a cabo. Quiero decir que no caminas sin pensarlo. Tu cerebro le dice a tus pies y tu cuerpo como mantener el equilibrio.

Y ¿Qué pasa con la respiración? ¿Esa si es automática? Pues, sí y no. Por su puesto que puede ser automática, pero aún la respiración es una rutina aprendida por tus pulmones, corazón, nariz, etc. Tu cerebro le dice a tus órganos cómo y cuánto respirar. 

## Por cualquier actor

Lo venimos diciendo anteriormente, en la mayoría de los casos, nuestro cerebro sabe cómo realizar cada rutina, pero no todo el tiempo actúa sin tu permiso. Digamos que además de respirar y hacer funcionar tus órganos internos, tu cerebro necesita que tu le digas qué hacer en todo momento.

## Ejemplo completo

Imagina que te despiertas por las mañanas, ¿Quién te despertó? ¿La alarma? ¿El ruido de los vecinos? Así es, tu cerebro. Tu cerebro sabe como despertarte. Por eso, cuando tu intentas despertarte por tu propia cuenta, pero el cerebro aún no da la orden, puedes sufrir de la parálisis del sueño. Lo mejor que puedes hacer es esperar a que tu cerebro de la orden de despertar al resto de tu cuerpo.

## ¿Cómo lo hacen las computadoras?

Las computadoras también tienen memorias que utilizan como cerebros. Aunque son considerablemente más primitivos que los cerebros humanos.

Para que una computadora encienda (O despierte), necesita tener almacenada una rutina de encendido. Lo mismo con el apagado. A estas rutinas les llamamos funciones. Es por eso que decimos que una computadora no funciona cuando no prende o no se puede apagar.

# Funciones en programación

Pero, ¿Cómo le hace la computadora para saber la hora, o para imprimir mis documentos, o reproducir videos? Bueno, eso es fácil de explicar, difícil de hacer.

Las computadoras son tontas. Necesitan que se les enseñe a hacer todo. Sin intervención humana, las computadoras no pueden aprender.

Entonces, podemos decir que los programadores escriben funciones para que la computadora pueda cumplir con sus deberes.

Cuando la tarea que se quiere completar es muy grande, por ejemplo: Una calculadora, no basta con una función que haga todo. Mas bien los programadores crean una gran cantidad de funciones para que la computadora sepa calcular. A este conjunto de funciones le llaman programa de computadora o aplicación. Así es como se crean las aplicaciones de calculadora.

## Función para sumar dos números en Kotlin

Para que tú puedas probar estos ejemplos te invito a que visites el [área de juegos oficial de Kotlin](https://play.kotlinlang.org/).

Veamos el siguiente ejemplo:

<div class="centered-container">
  <a href="https://gist.github.com/jesusdmedinac/b56064721881fa9daafd121da6379f7b" target="_blank">
    <img src="../../../images/funcion-para-sumar-dos-numeros-en-kotlin.png" class="post-image">
    </img>
  </a>
  <p align="center">Función para sumar dos números en Kotlin</p>
</div>

1. Al darle click al botón de play, se ejecuta nuestra función `main`.
2. Se crean dos valores para ser sumados por nuestra función `sumOf`, `a` y `b`.
3. Se ejecuta nuestra función `sumOf` utilizando los valores `a` y `b`.
4. El resultado de la suma se guarda en `aPlusB`.
5. Imprimimos el valor en la consola.

¡Inténtalo tú mismo! Visita el area de juegos de Kotlin y copia y pega el ejemplo anterior. Dale play y mira lo que pasa.

## Anatomía de una función

Algunos lenguajes de programación son similares por la manera en la que se escriben. A esto le llamamos sintaxis. Sin embargo, las funciones no se escriben igual en todos los lenguajes de programación. La anatomía de una función es siempre la misma, pero la forma de escribirlas cambiará de lenguaje en lenguaje.

En el siguiente ejemplo veremos la anatomía de una función escrita en Kotlin:

<div class="centered-container">
  <a href="https://gist.github.com/jesusdmedinac/78c1898a3118549c5411ba2b84ac12a4" target="_blank">
    <img src="../../../images/anatomia-de-una-función-en-kotlin.png" class="post-image">
    </img>
  </a>
  <p align="center">Anatomía de una función en Kotlin</p>
</div>

### 1. Palabra clave `fun`

Cada lenguaje tiene palabras reservadas para indicar diferentes cosas. A esto le llamamos palabras claves o palabras reservadas.

Kotlin utiliza la palabra clave `fun` para indicar que lo que estás escribiendo es una función.

### 2. Nombre de la función

En Kotlin, puedes utilizar casi cualquier signo para nombrar tus funciones. Sin embargo, existen algunas convenciones de código para nombrar las variables, funciones, y otras cuestiones.

Si quieres aprender más sobre convenciones de código en kotlin, te invito a leer el [siguiente artículo](https://kotlinlang.org/docs/coding-conventions.html#overload-layout).

### 3. Paréntesis

Todas las funciones en Kotlin utilizan los paréntesis para determinar el área en donde debes defir los argumentos. Si bien, no es obligatorio que tus funciones tengan argumentos, todas las funciones necesitan llevar los paréntesis.

### 4. Argumentos de una función

Cada argumento debe de contener el nombre y el tipo de dato del argumento. Esto lo veremos en el siguiente capítulo, pero el tipo de dato define lo que es tu argumento, por ejemplo, un número o texto, etc.

### 5. Tipo de dato de retorno

Al terminar de ejecutarse, la función puede o no regresar un valor. Si la función regresa algún valor, debes indicar el tipo de dato de este valor, por ejemplo, un número o texto, etc. Si la función no indica el tipo de dato, la función regresará automáticamente un tipo de dato llamado `Unit`, el cual es utilizado para indicar que esta función no regresa nada especial al terminar su ejecución.

### 6. Llaves

Las llaves en Kotlin son utilizadas para determinar bloques de código. Algo así como párrafos al escribir.

### 7. Palabra clave `return`

Esta palabra clave se utiliza para indicar que el valor que se escriba a su derecha será devuelto por la función al terminar. Por ejemplo, la suma de nuestros argumentos.

# Conclusión

¿Muy complicado? no te preocupes, puedes repetir este capítulo cuantas veces te haga falta. Te invito a que me compartas tus dudas en los comentarios. 

Recuerda que la mejor forma de aprender a programar es practicando. Te invito a copiar y pegar el código en el área de juegos oficial de kotlin para que puedas ponerlo a prueba tú mismo.

¡Intenta modificar el código y ver qué es lo que pasa!

# Programación desde 0 – Kotlin para no programadores

<div class="centered-container">
  <a href="https://www.youtube.com/watch?v=Y0eq8x4dL00" target="_blank">
    <img src="../../../images/miniatura-que-es-una-funcion.png" class="post-image"/>
  </a>
  <p align="center">¿Qué es una función?</p>
</div>

En la siguiente lista podrás encontrar en enlace a cada uno de los videos conforme los vaya publicando.

1. [Introducción – Programación desde 0 – Kotlin para no programadores](https://www.youtube.com/watch?v=7hLysDKu814&t=1s)
2. [¿Qué es la programación?](https://www.youtube.com/watch?v=kKRW_cUl2Ro)
3. [¿Qué puedo hacer con la programación?](https://www.youtube.com/watch?v=oLiAZmoZutE&t=10s)
4. [¿Cómo puedo empezar a programar?](https://www.youtube.com/watch?v=GabLhoyijwc)
5. [Herramientas recomendadas para empezar a programar](https://www.youtube.com/watch?v=Y0eq8x4dL00)
6. [¿Qué es una función?](https://www.youtube.com/watch?v=yHGg9t3W5fA)
7. ¿Qué es un dato?
8. ¿Qué es un algoritmo?
9. ¿Qué es un operador?
10. ¿Qué es una condición?
11. ¿Qué es un ciclo?
12. ¿Qué es una estructura de datos?
13. Mi primer aplicación móvil – Kotlin para no programadores