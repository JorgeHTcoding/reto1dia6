# reto1dia6
reto 1 dia 6

Hemos creado las dos ramas usando el comando git branch rama1 y git branch rama2, hemos revisado que se hayan creado con git branch y nos imprimió las 3 ramas:
main (en la que estamos en ese moment) rama 1 y rama2.

Aprovechamos para subir todo el proyecto al repositorio correspondiente de github usando el add commit y push

Usamos git checkout rama 1 para cambiarnos a la rama 1 como indica el ejercicio.

Modificamos el archivo index para borrar la función de suma y lo guardamos. Lo subimos con add commit y push desde la rama 1.

Usamos el comando git checkout para movernos a la rama main y usamos el comando git merge rama1 para fusionarlo con la rama principal. (no nos ha dado ningún conflicto).

Volvemos a hacer el mismo proceso pero despues de habernos movido a rama2, modificamos la funcion, subimos usando los mismo comandos y nos cambiamos a rama main para el merge.

En este caso nos genera un conflicto con el automergin que nos pide que solucionemos el conflicto en index y lo volvamos a subir con commit.

Lo solucionamos en el visual y lo subimos de nuevo


