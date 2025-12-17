# lab-py-advan

## Laboratorio 5 – Paralelismo en Python
Este repositorio contiene la entrega del **Laboratorio 5**.  
Incluye los ejercicios sobre paralelización con **multiprocessing**, **Numba** y ejecución en el clúster **mendel**.

## Contenido
- **primes-par-alumno05.ipynb** – Suma de números primos con versión secuencial, Numba, Pool y Numba paralela.  
- **reduc-operation-array-par-alumno05.ipynb** – Reducción de arrays grandes usando naive, multiprocessing y Numba (sec. y paralelo).  
- **pi-par-solution-alumno05.ipynb** – Actividad extra para calcular π con distintos métodos paralelos.  

### Scripts SLURM
- `submit_Primes_mendel-alumno05.sb`  
- `submit_Reduc_mendel-alumno05.sb`  
- `submit_PI_extra_mendel-alumno05.sb`

- **Informe_lab5.pdf** – Comentarios y conclusiones del laboratorio.

## Objetivo
Aprender a comparar distintos métodos de paralelismo en CPU, medir rendimiento en un entorno HPC real y ejecutar notebooks mediante SLURM.
