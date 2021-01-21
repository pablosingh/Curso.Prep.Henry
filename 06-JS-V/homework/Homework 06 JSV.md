Homework 06 JSV

Prototype:
El Prototipo es el objeto padre de otro objeto, todos tienen un objeto padre, hasta llegar al máximo que es Object que no tiene prototipo. Los prototipos heredan funciones y propiedades, cuando buscamos en un objeto algún método o propiedad y no esta, el interprete sigue buscando en su prototipo y si aún no la encuentra sigue buscando en prototipos superiores hasta llegar al Object (que tiene prototype=null). Una de las ventajas es que evita repetir código en todos los objetos hijos.

Constructors:
Son funciones que crean objetos, instancian objetos de una clase e inicializan las propiedades del mismo (o no uno decide).  