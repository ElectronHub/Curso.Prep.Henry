# Homework: Javascript IV

Los 'Objetos' son contenedores de datos al igual que un array pero con la diferencia que no es estructurado como estos, 
en los objetos no estan ordenados. Esos datos se dividen en 'propiedades' cuando son valores, que serian como 
variables dentro del objeto y en 'metodos' que son funciones que estan dentro del obejto.
Un 'Bucle `for…in`' es similar a un for que usamos para recorrer los valores de un array pero como a los objetos no 
los podemos recorrer por las posiciones de las variables necesitamos otro tipo de bucle y ahi es cuando se utiliza `for…in`, 
que las propiedades del objeto.
Para tener acceso a las propiedades y metodos de los obejtos podemos utilizar un punto o corchetes, dependiendo como lo 
vayamos a utilizar nos servira uno u otro.
Por ejemplo si queres ver el valor de una propiedad de un objeto generalemnte usamos el punto, nombreObjeto.Propiedad, pero si 
estamos operando dentro de una funcion donde la propiedad es un argunmento de la funcion debemos utilizar los corchetes 
de la sigueinte manera, nombreObjeto[Propiedad] siendo 'Propiedad' una variable;