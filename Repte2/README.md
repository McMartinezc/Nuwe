El següent projecte s'ha realitzat per fer honor a les funcions lambda, i consta de 4 mètodes per comprovar si un número és parell, primer i palíndrom.

-El primer mètode isOdd, no s'han utilitzat lambdas, ja que amb una línia de codi fem el que es busca, comprovar si un número és parell o no, per tant, no s'ha considerat necessari.

-El segon mètode isPrime, es comprova que el número introduït sigui major a 1 i convertim un Stream ("flux de dades") del tipus Integers amb un rang a partir de 2 fins al número introduït.
Aquesta fa la comprovació la qual s'ha fet servir un noneMatch on es calcula la resta de la divisió del número dividit per ell mateix i per índex.

-El tercer mètode isPalindrome, s'ha creat una variable del tipus booleana nomenada palindrome, la qual ens serveix per guardar el resultat de l'operació que es fa amb lambda. Aquesta converteix el número a tipus String i la comparem amb el equals amb el mateix número convertit a String però girant-lo amb l'opció reverse(). Per tal de comprovar si el número és palíndrom.

I per últim, mètode checker llegeix l'ArrayList de números i crida la resta de mètodes esmentats i imprimeix el resultat. També verifica si és un nombre negatiu o 0.
