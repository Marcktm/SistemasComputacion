# TP1 - Performance y Rendimiento

Este proyecto contiene el código fuente para medir el rendimiento con gprof.

## Estructura

- `/src/`: Código fuente en C.
- `/resultados/`: Resultados individuales de cada integrante.
- `informe.md`: Documento del informe a completar.

## Instrucciones para correr

```bash
cd src
gcc -Wall -pg test_gprof.c test_gprof_new.c -o test_gprof
./test_gprof
gprof test_gprof gmon.out > resultado.txt
