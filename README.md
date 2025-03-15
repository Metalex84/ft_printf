# 42 Cursus - FT_PRINTF

![ft_printf Score](/ft_printf_score.png)

## Información del proyecto

### Resumen
El propósito de este proyecto es replicar el comportamiento de la función `printf` del lenguaje C. La parte fundamental del proyecto se centra en manejar las **funciones variádicas** (funciones que reciben un número variable de argumentos).

### Parte obligatoria
Clonar la función `printf` según la siguiente signatura:
```
int ft_printf(char const *, ...);
```
* No se implementa la gestión del buffer del `printf()` original.
* Se debe utilizar el comando `ar` para crear la librería. El uso de `libtool` está prohibido.
* El archivo `libftprintf.a` se crea en la raíz del repositorio.

### Conversiones
* %c Imprime un solo carácter.
* %s Imprime una string (como se define por defecto en C).
* %p El puntero void * dado como argumento se imprime en formato hexadecimal.
* %d Imprime un número decimal (base 10).
* %i Imprime un entero en base 10.
* %u Imprime un número decimal (base 10) sin signo.
* %x Imprime un número hexadecimal (base 16) en minúsculas.
* %X Imprime un número hexadecimal (base 16) en mayúsculas.
* % % para imprimir el símbolo del porcentaje

## Compilación
```
make
make fclean
make clean
```
