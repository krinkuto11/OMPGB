# Documentación extra

---
  Aquí se encuentra código hecho por el grupo y que no se halla en la
  bibliografía
---


## Temporizadores

Se han usado dos tipos de temporizadores. El código paralelizado ha requerido de una solución específica, ya que usando los métodos comunes, no se obtenían resultados fiables.

#### Temporizador (Secuencial)

```c
struct timespec begin, end;
clock_gettime(CLOCK_MONOTONIC_RAW, &begin);

//código a ejecutar

clock_gettime(CLOCK_MONOTONIC_RAW, &end);
printf ("Ha tardado = %f segundos\n", (end.tv_nsec - begin.tv_nsec) / 1000000000.0 +(end.tv_sec  - begin.tv_sec));
```

#### Temporizador (Paralelo)

```c
double itime, ftime, exec_time;
itime = omp_get_wtime();

//código a ejecutar

ftime = omp_get_wtime();
exec_time = ftime - itime;
printf("\n Ha tardado %f segundos", exec_time);
```
