Ejercicio 1
git config --global user.email "sergio.m20@myyahoo.com"
mkdir capitulos
cd capitulos
echo "Git es un sistema de control de versiones ideado por Linus Torvalds"> capitulo1.txt
git add .
git log

Ejercicio 2
echo "El flujo de trabajo básico con Git consiste en: 1- Hacer cambios en el repositiorio. 2-Añadir los cambios a la zona de intercambio temporal. 3- Hacer un commit de los cambios"> capitulo2.txt
git add capitulo2.txt
git commit -m "Añadido capítulo 2"
git diff HEAD~2..HEAD

Ejercicio 3
Git echo "permite la creación de ramas lo que permite tener distintas versiones del mismo proyecto y trabajar de manera simultanea en ellas"> capitulo3.txt
git add capitulo3.txt
git commit -m "Añadido capítulo 3"
git log
git diff bd7f f17a

Ejercicio 4
echo "Capítulo 5: Conceptos avanzados"> indice.txt
git commit -m "Añadido capítulo 5"
git add indice.txt
git show indice.txt
