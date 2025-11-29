Proyecto: Encriptación y desencriptación básica en Java

Este proyecto consiste en la creación de un programa capaz de encriptar y desencriptar texto utilizando un método simple basado en el desplazamiento de caracteres. El objetivo es comprender de manera práctica cómo funcionan los algoritmos básicos de cifrado y aplicar la lógica dentro del lenguaje Java.

Características del programa:

– Permite ingresar un texto y cifrarlo.
– Permite también descifrar el texto encriptado.
– Utiliza un desplazamiento de caracteres tipo cifrado César.
– Es sencillo de entender y modificar.

Objetivo del proyecto:

El objetivo principal es implementar un sistema de cifrado educativo que convierta un texto legible en una versión modificada mediante desplazamiento de letras. Del mismo modo se busca revertir este proceso para obtener el mensaje original, permitiendo entender la lógica de la criptografía elemental.

Archivos incluidos:

Main.java como archivo principal donde se ejecuta la aplicación.
Cifrado.java donde se encuentra la lógica de encriptación y desencriptación.
README como documentación del proyecto.

Funcionamiento del cifrado:

El programa toma cada letra del texto y la reemplaza por otra que se encuentra varias posiciones adelante dentro del alfabeto. Por ejemplo, si se usa un desplazamiento de tres posiciones, la letra h pasará a ser k, o l pasará a ser o. Para recuperar el mensaje original se realiza el mismo proceso pero restando el desplazamiento en lugar de sumarlo.

Ejemplo de funcionamiento:

Texto ingresado: hola mundo
Texto encriptado: krod pxqgr
Texto desencriptado: hola mundo

Resultados esperados:

Al ejecutar el programa se debe mostrar primero el mensaje original ingresado por el usuario, posteriormente la versión cifrada con desplazamiento y finalmente la versión recuperada del texto original para comprobar que el proceso funciona de manera correcta.

Conclusión:

Este proyecto muestra una forma sencilla de proteger información textual mediante cifrado básico. Aunque el método no es seguro para uso avanzado, sirve como práctica para comprender la lógica de sustitución de caracteres y los principios iniciales de la criptografía. Este trabajo puede ampliarse integrando algoritmos más complejos o interfaces de usuario para mejor interacción.
