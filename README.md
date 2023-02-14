```bash
	rm -rf examenGIT
	mkdir examenGIT
	cd examenGIT/

	git init .
	touch nombre.txt && echo "Marcos" >> nombre.txt
	git add . -A
	git commit -m "Confirmado el nombre"

	git branch apellidos
	git checkout apellidos
	echo "Dominguez Vega" >> nombre.txt
	touch curso.txt && echo "1ºDAW" >> curso.txt
	git add . -A
	git commit -m "Añadido curso y apellidos"

	echo " "
	echo " "

	git branch -av
	git checkout master
	touch modulo.txt && echo "Desarrollo de aplicaciones web" >> modulo.txt

	git add . -A && git commit -m "Añadido modulo"
	git merge apellidos

	git log --oneline --all
	git log --graph --all
```
![Ejecucion](./media/ejercicio1.png)
