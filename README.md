# ¡¡¡ Buscando un digrama conmutativo para la portada !!!

# Categorías 2024 Ejercicios


https://sites.google.com/view/categorias-uma-uab/Bienvenida?authuser=0


# Sesión 1  
Lectura recomendada: Secciones 1.1, 1.2, 1.3 de [R16].

Lista de ejercicios: 1.1.i, 1.1.ii, 1.1.iii (i), 1.2.ii, 1.2.iii, 1.2.iv, 1.2.v, 1.3.i, 1.3.ii, 1.3.iii, 1.3.viii, 1.3.ix, 1.3.x.

# Sesión 2  
Lectura recomendada: Secciones 1.4, 1.5 de [R16].

Lista de ejercicios: 1.4.ii, 1.4.iii, 1.4.iv, 1.5.i, 1.5.ii, 1.5.iv, 1.5.v, 1.5.vi, 1.5.vii, 1.5.x.


# Sesión 3 
Lectura recomendada: Sección 1.6 de [R16].

Lista de ejercicios: Los de la sección 1.6.

# Sesión 4








# Como Contribuir al LaTeX

Paquetes 
No se aceptan paquetes que intervengan el normal funcionamiento de tikz-cd.
En el documento "preamble" se definen todos los paquetes utilizados y muchos otros comentados.
Si se necesita des-comentar o añadir algún paquete y no causa ningún conflicto con paquetes exigentes se puede preceder sin ningún problema (si es posible comentarlo aun que sea en el "commit").
Si dicho paquete causa conflicto se estudiara caso por caso pero en general se priorizara no romper código existente.


Notación 

El documento "natation" se definen varios aspectos de la notación que considero conveniente pera hacer las cosas un poco mas fáciles a todos.

Fuente: 

Hay varias fuentes definidas como \cat{} y \fun{} que están directamente copiadas de varios artículos de Emily Riehl, y como su nombre indica son para categorías y functores respectivamente.
Si se prefiere otro etilo existen distintas opciones por ejemplo \Cat{} de lugar a letras caligráficas (como se suelen escribir a mano las categorías).

Lema de Yoneda:

El consenso actual es usar よ par la subversión de Yoneda, están definidas dos versiones de este símbolo \Yo y \yo las diferencias son sutiles y recomiendo usarlos en función de la situación, si en algún caso no convenza el resalado con uno lo mejor es probar el otro.

"operadores":

\restr{}{} 

\Mor{}{}

\dom{}

\cod{}

Identidad:

\Id{} 

o 

\id{}

Notación útil:

\op

Categorías:

\Sets 

\Top 

\sSet

\fVectR

\Vect{}


TFG:

He añadido algunos instrucciones que utilice en mi TFG pude que no sea la notación que vamos a usar pero se pude adaptar.

# Añadidos o Cambios en Notación:

Ya que cambios en el documento "notation" (newcommand en general) muy fácilmente pueden romper el código o crear confusión en la interpretación matemática pido que se discuta previamente cualquier cambio o añadido.


# Diagramas Conmutativos 

Como vamos a escribir muchos diagramas conmutativos recomiendo usar tikz-cd.

https://ctan.fisiquimicamente.com/graphics/pgf/contrib/tikz-cd/tikz-cd-doc.pdf

Por cualquier duda o problema no duden en contactarme.

# Recordatorio de LaTeX 

En el siguiente enlace se encurta un reclinatorio de todos los símbolos (algunos requerirán de paquetes adicionales).
https://ctan.fisiquimicamente.com/info/symbols/comprehensive/symbols-a4.pdf

En esta sección se añadirán instrucciones útiles que necesitaremos con frecuencia.

\rightrightarrows
\leftleftarrows

\leftrightarrows
\rightleftarrows





# Que programas uso:
TeXLive 2024 (actualizado)

Neovim + Lazyvim con los extras para Tex

Con varios Snippets para LuaSinp que se pueden encontrar en otro repositorio de esta misma cuenta de GitHub.

