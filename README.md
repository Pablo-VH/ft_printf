# FT_PRINTF ES🇪🇸

## Introducción

El proyecto `ft_printf` es parte de los proyectos de las escuelas 42, reta a los estudiantes a replicar el comportamiento de la función `printf` de la biblioteca estandar de C. Este proyecto ayuda a comprender la versátil función `printf`, muy utilizada en la programación en C para dar formato a la salida. Al recrear `printf`, los estudiantes adquieren una visión profunda de los argumentos variables, el formato y la forma de implementar una función capaz de manejar múltiples tipos de datos y opciones de formato.

## Objetivo

El objetivo principal del proyecto `ft_printf` es recrear la función `printf` de la librería estándar de C. La función recreada, `ft_printf`, debe imitar el comportamiento de la `printf` original tanto como sea posible. Esto incluye el manejo de varios especificadores de formato para imprimir diferentes tipos de datos (`d`, `i`, `u`, `x`, `X`, `c`, `s`, `p`, `%`), banderas, anchura y precisión.

## Tecnologías & Lenguajes usados

- **Lenguaje:** C
- **Conceptos clave:** Argumentos variádicos, manejo de strings.
- **Compilación:** Makefile para crear la librería

## Características

- Admite la impresión de varios tipos de datos, incluidos enteros, enteros sin signo, caracteres, arrays, punteros y valores hexadecimales.
- Maneja opciones de formato complejas como anchura de campo, precisión, banderas y modificadores de longitud.
- Imita el comportamiento original de `printf` en cuanto a valores de retorno y gestión de errores.

## Uso

1. **Compilación**: Compila `ft_printf` ejecutando `make` en la raiz del directorio del proyecto. Esto generará un fichero de librería `libftprintf.a`.
2. **Integración**: Incluye el fichero de cabecera `ft_printf.h` en tus ficheros C y utiliza `ft_printf` como lo harías con el `printf` estándar.
3. **Ejemplo**: Aquí tienes un ejemplo sencillo de cómo usar `ft_printf`:

```c
#include "ft_printf.h"

int main(void)
{
    ft_printf("Hello, %s!\n", "world");
    ft_printf("Hexadecimal for %d is %x.\n", 42, 42);
    return (0);
}
```
## Instalación
Para empezar a utilizar ft_printf en tus proyectos, sigue estos pasos:    
```c
git clone https://github.com/Pablo-VH/ft_printf.git
cd ft_printf
make
```

# FT_PRINTF EN🇬🇧

## Introduction

The `ft_printf` project is part of the curriculum at 42 schools, challenging students to reimplement the `printf` function from the C standard library. This project aids in understanding the versatile `printf` function widely used in C programming for output formatting. By recreating `printf`, students gain deep insights into variable arguments, formatting, and how to implement a function capable of handling multiple data types and formatting options.

## Objective

The primary objective of the `ft_printf` project is to recreate the `printf` function from the C standard library. The recreated function, `ft_printf`, should mimic the behavior of the original `printf` as closely as possible. This includes handling various format specifiers for printing different data types (`d`, `i`, `u`, `x`, `X`, `c`, `s`, `p`, `%`), flags, width, and precision.

## Technologies & Languages Used

- **Language:** C
- **Key Concepts:** Variable Arguments, String Formatting, Output Management
- **Compilation:** Makefile for compiling the library and testing

## Features

- Supports printing various data types, including integers, unsigned integers, characters, strings, pointers, and hexadecimal values.
- Handles complex formatting options such as field width, precision, flags, and length modifiers.
- Imitates the original `printf` behavior in terms of return values and error handling.

## Usage

1. **Compilation**: Compile `ft_printf` by running `make` in the root of the project directory. This will generate a `libftprintf.a` library file.
2. **Integration**: Include the `ft_printf.h` header file in your C files and use `ft_printf` as you would the standard `printf`.
3. **Example**: Here is a simple example of how to use `ft_printf`:

```c
#include "ft_printf.h"

int main(void)
{
    ft_printf("Hello, %s!\n", "world");
    ft_printf("Hexadecimal for %d is %x.\n", 42, 42);
    return (0);
}
```
## Installation
To start using ft_printf in your projects, follow these steps:    
```c
git clone https://github.com/Pablo-VH/ft_printf.git
cd ft_printf
make
```
