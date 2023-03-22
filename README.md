git branch refactorizacion

echo "Refactoring is a systematic process of improving code without creating new functionality that can transform a mess into clean code and simple design." > refactorizacion.txt

git add .

git commit -m “Añadido concepto de refactorizacion”

git status

git branch patrones

echo "Los patrones de diseño (design patterns) son soluciones habituales a problemas comunes en el diseño de software." > patrones.txt

git add patrones.txt

git commit -m “Añadida primera definición de patrones de diseño”

git status

git checkout main

git merge patrones

git status

git branch -D patrones

git status

git branch patrones

git checkout patrones

echo "Cada patrón es como un plano que se puede personalizar para resolver un problema de diseño particular de tu código." > patrones.txt

git commit -a -m “Añadida definición 2 de patrones de diseño”

git checkout main

echo "Los patrones son un juego de herramientas que brindan soluciones a problemas habituales en el diseño de software. Definen un lenguaje común que ayuda a tu equipo a comunicarse con más eficiencia." > patrones.txt

git commit -a -m “Añadida definición 3.”

git checkout main

git merge patrones

vim patrones.txt

git merge patrones

git commit -a -m “Resuelto conflicto de patrones.”

git log

git branch
