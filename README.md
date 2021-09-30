# Ejercicio 1 una apliación donde se implementen 5 pseudoclase y 5 pseudoelementos

## Pasos seguidos.
 
- cree la estructura Html basica
- Organice en divisiones el contenido.
- Encabezado y párrfos con las psuedoclases 
  1. :focus
  2. :hover
  3. :link
  4. :visited
  5. :nth-child( )
- encabezado y párrafos con los 
  1. :first-letter
  2. :before
  3. :after
  4. :selection
  5. :placehoder( )

###PSEUDO-CLASES Y PSEUDO ELEMENTOS INCLUIDOS

#### PSEUDO-ELEMENTOS
SECTION, AFTER, BEFORE, FIRST-LETTER, FIRST-LINE
```CSS
::selection {
    color: #EF4BF2;
    background-color: #0D0D0D;
}
.cards__h2::after {
    content: ".";
}
.card__h3::before {
    content: "-"
}
.card__p::first-letter {
    color: #D9042B;
}
.card__p::first-line {
    text-decoration: underline #D9042B;
}
```
Todo el texto del contenido tiene :hover

#### PSEUDO-CLASES
```CSS
.cards:active {
    transform: scale(1.1,1.1);
}
.card__h3:hover {
    color: #D9042B;
    cursor: pointer;
}
.card:first-child .card__p {
    border: none;
}
.card:last-child .card__p {
    text-align: center;
    border: none;
}
```
