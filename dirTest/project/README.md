# EVALUACIÓN 1

Dentro de lo modificado en el archivo wcat.c, se da un código para testear su funcionamiento.

![imagen de git bash](https://github.com/hacUPB/evaluacion-1-SheiinX/blob/main/dirTest/project/img/GitBash-GitLog.png)

![Repositorio de evaluación de Sebastián Franco](https://github.com/hacUPB/evaluacion-1-SheiinX)

Comandos utilizados para la modificación del repositorio:
- git clone {url del repositorio} (Clonar el repositorio)
- cd ./ (Ubicarme dentro de los discos)
- code . (Abrir Visual para configurar tanto el código wcat.c como el README.md)
- git status (Controlar que se ha cambiado y que está fuera)
- git add {Nombre de archivo} (Ponerl en el stage el archivo en cuestion, wcat.c)
- git commit -m "sample text" (Hacer un commit)
- git push (Sincronizar con el repositorio en linea y guardar el commit en tal)
- git log (Ver los commit hechos)

In this directory, you should write the program `wcat.c` and compile it into
the binary `wcat` (e.g., `gcc -o wcat wcat.c -Wall -Werror`).

After doing so, you can run the tests from this directory by running the
`test-wcat.sh` script. If all goes well, you will see:

```sh
prompt> ./test-wcat.sh
test 1: passed
test 2: passed
test 3: passed
test 4: passed
test 5: passed
test 6: passed
test 7: passed
prompt>
```

The `test-wcat.sh` script is just a wrapper for the `run-tests.sh` script in
the `tester` directory of this repository. This program has a few options; see
the relevant
[README](https://github.com/remzi-arpacidusseau/ostep-projects/blob/master/tester/README.md)
for details.



