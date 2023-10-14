# Proyecto Chat
Programación paralela y distribuida  
Autores:
- Oscar Estrada 20565
- Axel López 20768

## Instrucciones de compilación y ejecución
Compilar

```bash
mpicc -g -Wall -o mpi_trap4 mpi_trap4_do.c

Ejecutar
```bash
mpiexec -n <número de procesos> ./mpi_trap4

Ejemplo
```bash
mpiexec -n 4 ./mpi_trap4