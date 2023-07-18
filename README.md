# CPAR (Curso 1) - Ejemplo de Evaluacion Practica

Esta evaluación examina algunas habilidades en el manejo básico de la plataforma DevCloud.

## Puntaje

| Ejercicio | Puntaje  |
|:-------|:--------:|
| 1       | 5 |
| 2       | 5 |
| 3       | 5 |
| 4       | 5 |
| ======= |======  |
| Total   | 20 |

## Ejercicios

### Ejercicio 1
Ingresar a DevCloud y clonar el siguiente repositorio:

```
https://github.com/<Example_Repository>/<Example_Project>.git
```

- **Pregunta 1.1.** Listar el/los comando(s) utilizado(s) y su salida correspondiente en la consola

### Ejercicio 2
Moverse al directorio del repositorio `<Example_Directory>`.

- **Pregunta 2.1.** Listar el/los comando(s) utilizado(s) y su salida correspondiente en la consola

### Ejercicio 3
Crear un bash script `build.sh` con el siguiente contenido:

```
Ejemplo de código del bash script
```

- **Pregunta 3.1.** Listar el/los comando(s) utilizado(s) y su salida correspondiente en la consola

### Ejercicio 4
Compilar programa usando el bash script creado en el [Ejercicio 3](#ejercicio-3) y el siguiente comando:

```
$ qsub -l nodes=1:xeon:ppn=2 -d . build.sh
```

- **Pregunta 4.1.** Indicar el job ID correspondiente al comando `qsub`
- **Pregunta 4.2.** Listar los archivos _error_ y _output_ stream (`*.e*` y `*.o*`) generados durante la ejecución del job en DevCloud
- **Pregunta 4.3.** Mostrar el contenido de ambos archivos _error_ y _output_ stream (`*.e*` y `*.o*`) generados








