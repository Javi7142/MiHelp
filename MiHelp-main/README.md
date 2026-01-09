# MiHelp
Formato Markdown

## Índice
### [Encabezados](#encabezados-1)
### [Cambios tipográficos](#cambios-tipográficos-1)
### [Listas ordenadas y sin orden](#listas-ordenadas-y-sin-orden-1)
### [Snippets de código](#snippets-de-código-1)
### [Citas](#citas-1)
### [Enlaces a páginas, elementos externos y a elementos del mismo documento](#enlaces-a-páginas-elementos-externos-y-a-elementos-del-mismo-documento-1)
### [Imágenes externas y con enlace](#imágenes-externas-y-con-enlace-1)
### [Tablas](#tablas-1)
### [Líneas horizontales](#lineas-horizontales-1)
### [Saltos de línea](#saltos-de-línea-1)
### [Lista de tareas](#lista-de-tareas-1)
### [Emojis](#emojis-1)
### [Fórmulas matemáticas](#fórmulas-matemáticas-1)
### [Referencias y referencias al pie](#referencias-y-referencias-al-pie-1)

## Encabezados
### ¿Como realizar un encabezado en MarkDown?
para realizar un encabezado utilizando el formato MarkDown **bastará con poner uno o varios #** delante del texto que usarás como encabezado (# Encabezado 1), siendo el número de # el equivalente a los h1, h2, h3, h4, h5 y h6 de HTML, significando que un # es el encabezado más grande y los seis # el encabezado más pequeño.

## Cambios tipográficos
En MarkDown, puedes realizar cambios tipográficos a las palabras que tú quieras estando disponible poner la palabra en **negrita**, _cursiva_, ~~tachada~~ y las combinaciones entre ellas (**_negrita y cursiva_**, **~~negrita y tachada~~**, _~~cursiva y tachada~~_ y **_~~negrita, cursiva y tachada~~_**)
### ¿Cómo se realizan cada uno de estos cambios tipográficos?
#### **Negrita**
Para escribir palabras en **negrita** tendrás que colocar dos * al principio y al final de la/s palabras que quieras resaltar.
#### **Cursiva**
Para escribir palabras en _cursiva_ tendrás que colocar una _ al principio y al final de la/s palabras que quieras poner en cursiva. También sirve si colocas un solo * al inicio y al final.
#### **Tachada**
Para escribir palabras ~~Tachada~~ tendrás que colocar dos ~ al principio y al final de la/s palabras que quieras tachar.

#### **Combinación de ellas**
Para escribir palabras que estén en negrita y cursiva, negrita y tachada, cursiva y tachada o todas ellas a la vez bastará con combinar las diferentes formas de hacer cada una. **Diferentes posibilidades:** \*\*\_negrita y cursiva_**, \*\*\~~negrita y tachada~~**,     \_\~~cursiva y tachada~~_ y \*\*\_\~~negrita, cursiva y tachada~~_**

## Listas ordenadas y sin orden
### ¿Cómo se realiza una lista en MarkDown?
En el formato MarkDown podrás realizar tanto listas ordenadas como listas sin orden.
#### **Listas ordenadas**
Para relizar una lista ordenada solo tendrás que poner la númeracion de la lista al inicio de cada elemento que quieras listar junto a un punto y añadiendo un espacio para empezar a escribir (1. [texto]), teniendo que empezar por el número uno pero, a partir de ahí dará igual los números siguientes que utilices que la lista se ordenará automáticamente. **Ejemplo de lista ordenada:**
1. Este es el primer elemento de mi lista
2. Este es el segundo elemento de mi lista
3. Este es el tercer elemento de mi lista

#### **Listas sin orden**
Para realizar una lista sin orden solo tendrás que colocar un signo -, + o * delante de cada elemento de la lista, siendo indiferente el signo que utilices. **Ejemplo de lista sin orden:**
- Este es el primer elemento de mi lista
- Este es el segundo elemento de mi lista
- Este es el tercer elemento de mi lista
## Snippets de código
### ¿Cómo puedes escribir un snippet de codigo en MarkDown?
Para escribir snippets de código en formato MarkDown tendrás que utilizar tres \`\`\` delante del codigo a mostrar, indicando el lenguje de programación usado al inicio. Para terminar el bloque de código tendrás que poner otra vez \`\`\` en una linea nueva. **Una vez realizado, quedaría de esta forma:**

``` Java
public class helloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

## Citas
### ¿Cómo se realiza una cita en MarkDown?
Para realizar un cita en MarkDown tendrás que poner > delante del parrafo. **Ejemplo de cita:**
>Esta es una cita simple en una sola línea

Si quieres realizar una cita que englobe diferentes parrafos tendrás que colocar un > en la línea vacia entre los parrafos. **Ejemplo de cita con multiples parrafos:**
> Este es el primer párrafo de una cita.
>
> Este es el segundo párrafo, también parte de la cita.
## Enlaces a páginas o elementos externos y a elementos del mismo documento
En MarkDown puedes dejar enlaces a páginas o a elementos externos al igual que a elementos del propio documento.
### ¿Cómo se realizan estos enlaces?
#### **Enlaces a páginas o elementos externos**
Para realizar un enlace a una página o elemento externo tendrás que colocar entre [] el texto que ocupará el enlace y pegado a este mismo, tendrás que colocar entre () el enlace, quedando de la  siguiente forma: [texto del enlace]\(link) **Ejemplo:**
[Este enlace lleva a la página principal de Google](https://google.com). Además, podrás añadir un titulo al link el cual se mostrará al pasar el raton por encima, para hacerlo tendrás que añadirlo entre "" después de escribir el link, dentro del propio paréntesis quedando de esta forma: [texto del enlace]\(link "titulo del link") **Ejemplo:** [Página de Google](https://google.com "Este enlace te llevará a la página principal de Google").

#### **Enlaces a elementos del mismo documento**
Si queremos realizar un enlace a un elemento del mismo documento lo realizaremos igual que a un enlace externo pero añadiendo un # delante del elemento al que quieres referenciar. Este elemento a referenciar sería el contenido dentro del (), mientras que el texto entre [] funcionara igual que en los enlaces a páginas o elementos externos, es decir, será el texto que se mostrará. []
## Imágenes externas y con enlace
### ¿Cómo se añade una imagen a tu documento con MarkDown?
Para añadir una imagen, lo realizarás de la misma manera que al añadir un enlace solo que al inicio del [] pondrás una ! y dejando dentro del () la URL o la dirección de la imagen. En este caso, dentro del [] pondrás el texto alternativo de la imagen, quedando tal que así: ![Texto alternativo]\(link de la imagen). **Ejemplo:**
![imagen1](https://img.freepik.com/vector-gratis/acuarela-pintada-mano-fondo-acuarela-abstracto_23-2149012404.jpg?semt=ais_hybrid&w=740&q=80)
![imagen2](/Imagenes/ImagenFondo.jpg)
## Tablas
### ¿Cómo se realiza una tabla en MarkDown?
Para realizar una tabla en markdown simplemente se utilizan guiones (-) para definir las cabeceras de las columnas y barras verticales (|) para separar las columnas. ![Imagen-ejemplo-tabla](/Imagenes/EjemploTabla.png)
**Ejemplo:**
| Encabezado 1 | Encabezado 2 | Encabezado 3 |
|--------------|--------------|--------------|
| Dato 1       | Dato 2       | Dato 3       |
| Dato 4       | Dato 5       | Dato 6       |

## Líneas horizontales
### ¿Cómo se realiza una línea horizontal en MarkDown?
Para crear una linea horizontal en MarkDown bastará con colocar en una línea nueva ***, --- o ___
**Ejemplo:**

---

## Saltos de línea
### ¿Cómo se realiza un salto de línea en MarkDown?
Para hacer un salto de línea en Markdown, puedes terminar una línea con dos espacios y luego presionar Enter, o simplemente presionar Enter dos veces para un nuevo párrafo.
## Lista de tareas
Para crear una lista de tareas en Markdown, usa un guion (-), un espacio, y luego corchetes con una 'x' si está completa ([x]) o un espacio si está pendiente ([ ]), seguido del texto de la tarea, como como - [ ] Tarea 1 o - [x] Tarea 2. **Ejemplo:**
- [ ] Tarea sin completar
- [x] Tarea completada
## Emojis
Para poner emojis en Markdown, puedes copiar y pegar directamente el emoji (😃) o usar códigos cortos como :codigo del emoji: que se convierten en emojis en plataformas compatibles
## Fórmulas matemáticas
### ¿Cómo se escribe una formula matemática en MarkDown
Para usar fórmulas matemáticas en Markdown, se emplea la sintaxis LaTeX, encerrando las expresiones con un solo dólar para fórmulas en línea ($x^2$) y con doble dólar para bloques centrados ($$ \int_0^1 x \,dx $$)
## Referencias y referencias al pie
Markdown permite definir referencias de enlaces en una parte del documento y luego referenciarlas en el texto. En ocasiones esto puede ser es útil para manejar múltiples enlaces y mantener el documento limpio.

Para ello, en primer lugar, definimos la URL con el enlace, en una sección de referencias (por ejemplo): Para ello usamos un identificador entre corchetes, así \[1]. **Ejemplo de referencia:**

la [sintaxis básica][1] de MarkDown es esencial para poder utilizar este lenguaje correctamente

[1]: https://www.markdownguide.org/basic-syntax/#overview

Por otro lado, Markdown soporta notas al pie a través de una sintaxis específica. Para crear una nota al pie, añadimos la nota con identificador de nota al pie entre corchetes seguido de un signo de adición (^) para insertar una referencia en el texto.

Por otro lado, definimos el contenido de la nota al pie, usando el mismo identificador. Esta definición puede estar en cualquier parte del documento. Normalmente inmediatamente después de su uso, o al final. **Ejemplo:**

Markdown es un lenguaje de marcado ligero[^2] que facilita la escritura de texto con formato.

[^2]: Markdown es un lenguaje creado por John Gruber y Aaron Swartz que se utiliza para formatear texto de manera sencilla y legible.
