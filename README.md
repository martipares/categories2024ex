

# [Ejercicios PDF](https://github.com/martipares/categories2024ex/blob/main/Ejercicios.pdf)

# [Apéndice PDF](https://github.com/martipares/categories2024ex/blob/main/apendice.pdf)

# [Categorías 2024 Web](https://sites.google.com/view/categorias-uma-uab/Bienvenida?authuser=0)

# Categorías 2024 Ejercicios



# Sesión 1  
2024-04-25

Lectura recomendada: Secciones 1.1, 1.2, 1.3 de [R16].

Lista de ejercicios: 1.1.i, 1.1.ii, 1.1.iii (i), 1.2.ii, 1.2.iii, 1.2.iv, 1.2.v, 1.3.i, 1.3.ii, 1.3.iii, 1.3.viii, 1.3.ix, 1.3.x.

# Sesión 2  
2024-05-02

Lectura recomendada: Secciones 1.4, 1.5 de [R16].

Lista de ejercicios: 1.4.ii, 1.4.iii, 1.4.iv, 1.5.i, 1.5.ii, 1.5.iv, 1.5.v, 1.5.vi, 1.5.vii, 1.5.x.


# Sesión 3 
2024-05-07

Lectura recomendada: Sección 1.6 de [R16].

Lista de ejercicios: Los de la sección 1.6.

# Sesión 4
2024-05-14

Lectura recomendada: Sección 1.5 de [R16], subsección 2.1.1 de V. Muñoz et al. (2020). Geometry and Topology of Manifolds y tercer capítulo de E. H. Spanier (1966). Algebraic Topology, en especial las secciones 1 y 5.

# Sesión 5
2024-05-21

Lectura recomendada: Sección 2.1 de [R16].

Lista de ejercicios: Los de la sección 2.1. Aparte, en esta [lista](https://drive.google.com/file/d/1czX5pz7UBUCK1PBvdKEApN8LClhzQdvL/view) encontraréis ejercicios adicionales relacionados con las preguntas que han surgido a lo largo del seminario. Por otro lado, pensaremos qué propiedad universal verifican las representaciones de un functor.



# Sesión 6
2024-05-28

Lectura recomendada: Sección 2.2 de [R16].

Lista de ejercicios: 2.2.iv, 2.2.v, 2.2.vi, 2.2.viii.


# Sesión 7
2024-06-


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

[documentacion oficial](https://ctan.fisiquimicamente.com/graphics/pgf/contrib/tikz-cd/tikz-cd-doc.pdf)

Por cualquier duda o problema no duden en contactarme.

# Recordatorio de LaTeX 

En el siguiente enlace se encurta un [recopilatorio de todos los símbolos](https://ctan.fisiquimicamente.com/info/symbols/comprehensive/symbols-a4.pdf) (algunos requerirán de paquetes adicionales).


En esta sección se añadirán instrucciones útiles que necesitaremos con frecuencia.

\rightrightarrows
\leftleftarrows

\leftrightarrows
\rightleftarrows





# Que programas uso:
TeXLive 2024 (actualizado)

Neovim + Lazyvim con los extras para Tex y luasnip

Con varios Snippets para LuaSinp que se pueden encontrar en otro [repositorio](https://github.com/martipares/LuaSnip_01) de esta misma cuenta de GitHub.

