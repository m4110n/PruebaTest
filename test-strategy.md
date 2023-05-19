Error Numero 1 en la linea 44 se agregó el cálculo correcto para generar el número aleatorio entre 1 y 100
Error
randomNumber = Math.floor(Math.random()) + 1;

Corregido
randomNumber = Math.floor(Math.random() * 100) + 1;
---------------------------------------------------------------------------------------------
Error numero 2 en la linea 49, se agregó el punto antes de 'lowOrHi'
Error
const lowOrHi = document.querySelector('lowOrHi');

Corregido
const lowOrHi = document.querySelector('.lowOrHi');
---------------------------------------------------------------------------------------------
Error numero 3 en la linea 64, Se utilizó la comparación con '==' en lugar de '===' para permitir la comparación entre tipos de datos diferentes
Error 
if(userGuess === randomNumber) {

Corregido
if(userGuess == randomNumber) { 
---------------------------------------------------------------------------------------------
Error numero 4 en la linea 87, Se cambió 'addeventListener' a 'addEventListener'
Error
guessSubmit.addeventListener('click', checkGuess);

Corregido
guessSubmit.addEventListener('click', checkGuess);
---------------------------------------------------------------------------------------------
Error numero 5 en la linea 95, Se cambió 'addeventListener' a 'addEventListener'
Error
resetButton.addeventListener('click', resetGame);

Corregido
resetButton.addEventListener('click', resetGame);
---------------------------------------------------------------------------------------------
Error numeor 6 en la linea 114, Se agregó el cálculo correcto para generar el número aleatorio entre 1 y 100
Error
randomNumber = Math.floor(Math.random()) + 1;

Corregido
randomNumber = Math.floor(Math.random() * 100) + 1;
