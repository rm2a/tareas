#let palabra1 = prompt(Ingrese la primera palabra:);
let palabra2 = prompt(Ingrese la segunda palabra:);

if (palabra1.length === palabra2.length) {
  alert(Las dos palabras tienen la misma longitud de  + palabra1.length +  caracteres);
} else if (palabra1.length > palabra2.length) {
  alert(La primera palabra " + palabra1 + " es más larga con  + palabra1.length +  caracteres);
} else {
  alert(La segunda palabra " + palabra2 + " es más larga con  + palabra2.length +  caracteres);
}

let sortedWords = [palabra1, palabra2].sort();
alert(Las palabras en orden alfabético son:  + sortedWords.join(, ));

let shortestWord = (palabra1.length < palabra2.length) ? palabra1 : palabra2;
alert(La palabra más corta en mayúsculas es:  + shortestWord.toUpperCase());

