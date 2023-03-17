# Semáforos en sistemas operativos
* Los semáforos son una herramienta fundamental en los sistemas operativos para coordinar el acceso a recursos compartidos entre procesos o hilos. A continuación, se explican los conceptos básicos de los semáforos en sistemas operativos.

 <br>
 

## Definición de semáforo
* Un **semáforo** es una variable global que se utiliza para controlar el acceso a un recurso compartido en un sistema operativo. Los semáforos permiten que los procesos o hilos coordinen el acceso a los recursos compartidos de manera que no se produzcan condiciones de carrera, en las que dos o más procesos o hilos intenten acceder simultáneamente a un mismo recurso compartido.
<br>
<br>

# Tipos de semáforos
Existen dos tipos principales de semáforos: semáforos binarios y semáforos enteros.

1. ## **Semáforos binarios**
* Los semáforos binarios sólo pueden tomar dos valores: 0 o 1. Se utilizan para indicar si un recurso está disponible o no. Si el semáforo está en 0, significa que el recurso está ocupado y no puede ser utilizado, mientras que si está en 1, el recurso está disponible y se puede utilizar.
<br>

2. ## **Semáforos enteros**
* Los semáforos enteros pueden tomar valores enteros positivos o cero. Se utilizan para controlar el acceso a un recurso compartido que puede ser utilizado por un número limitado de procesos o hilos al mismo tiempo. Cada proceso o hilo que quiera acceder al recurso debe decrementar el semáforo, y si el valor resultante es negativo, se bloquea y queda en espera hasta que el semáforo vuelva a ser incrementado por otro proceso o hilo que libere el recurso.
<br>
<br>
# Relación entre semáforos y sincronización
* La relación entre los semáforos y la sincronización radica en que los semáforos son una herramienta fundamental para asegurar la sincronización entre procesos o hilos en un sistema operativo. Los semáforos permiten a los procesos o hilos coordinar el acceso a recursos compartidos de manera que no se produzcan condiciones de carrera, en las que dos o más procesos o hilos intenten acceder simultáneamente a un mismo recurso compartido. De esta manera, los semáforos aseguran que los procesos o hilos accedan a los recursos de manera ordenada y controlada, evitando errores y garantizando la integridad de los datos.