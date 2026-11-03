# 💻 Programa de suma en C++

<p align="center">
  <strong>Ejercicio introductorio de programación con C++.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-11%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++ 11 o superior" />
  <img src="https://img.shields.io/badge/HTML5-Interfaz-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/Tipo-Académico-informational?style=for-the-badge" alt="Proyecto académico" />
  <img src="https://img.shields.io/badge/Estado-Funcional-success?style=for-the-badge" alt="Estado funcional" />
</p>

Repositorio de prácticas básicas para reforzar fundamentos de programación mediante un programa de consola en **C++**.

---

## 📖 Tabla de contenido

- [Acerca del proyecto](#-acerca-del-proyecto)
- [Características](#-características)
- [Tecnologías utilizadas](#-tecnologías-utilizadas)
- [Estructura del proyecto](#-estructura-del-proyecto)
- [Requisitos previos](#-requisitos-previos)
- [Instalación](#-instalación)
- [Uso](#-uso)
- [Ejemplo de ejecución](#-ejemplo-de-ejecución)
- [Conceptos practicados](#-conceptos-practicados)
- [Autor](#-autor)
- [Licencia](#-licencia)

## 🧭 Acerca del proyecto

**ProgramaC++** contiene ejercicios de aprendizaje orientados a la lógica de programación. El programa principal presenta un menú en la terminal con opciones para:

1. Calcular el cubo de un número.
2. Identificar si un número es par o impar.
3. Finalizar la ejecución.

## ✨ Características

- Menú interactivo en consola.
- Cálculo de potencias mediante `pow()`.
- Verificación de números pares e impares con el operador módulo.
- Uso de una estructura de selección múltiple con `switch`.
- Lectura de datos desde la entrada estándar.
- Código introductorio con comentarios explicativos.

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| **C++** | Desarrollo del programa de consola. |
| **`iostream`** | Lectura y escritura de datos en la terminal. |
| **`cmath` / `math.h`** | Cálculo del cubo mediante `pow()`. |
| **Git** | Control de versiones. |

## 📁 Estructura del proyecto

```text
ProgramaC/
├── Estructurascondicionales-Unmenu.cpp  # Menú y ejercicios en C++
└── README.md                            # Documentación del proyecto
```

### 📄 Archivos principales

- **`Estructurascondicionales-Unmenu.cpp`**: contiene la función `main`, el menú de opciones y la lógica para calcular el cubo o determinar la paridad de un número.

## ✅ Requisitos previos

Para ejecutar el programa de consola necesitas:

- Un compilador compatible con **C++11** o posterior, como `g++`.
- Una terminal.
- Git, si deseas clonar el repositorio.

Para comprobar que `g++` está instalado:

```bash
g++ --version
```

## 📥 Instalación

Clona el repositorio y accede a la carpeta del proyecto:

```bash
git clone https://github.com/MarioSi3ri/ProgramaC.git
cd ProgramaC
```

## ▶️ Uso

### Ejecutar el programa en C++

Compila el archivo fuente:

```bash
g++ -std=c++11 Estructurascondicionales-Unmenu.cpp -o programa
```

Ejecuta el programa:

```bash
./programa
```

En Windows, el ejecutable puede iniciarse con:

```powershell
programa.exe
```

## 🧪 Ejemplo de ejecución

```text
        MENU
1. Cubo de un numero.
2. Numero par o impar
3. Salir
Opcion: 1

Escriba un numero: 4

El cubo del numero es: 64
```

Otro ejemplo:

```text
Opcion: 2

Escriba un numero: 7

El numero es impar.
```

## 🎯 Conceptos practicados

- Declaración y uso de variables enteras.
- Función principal `main`.
- Entrada y salida estándar con `cin` y `cout`.
- Estructuras `switch`, `case` e `if/else`.
- Operadores aritméticos y operador módulo `%`.
- Funciones matemáticas con `pow()`.

## 👤 Autor

Desarrollado por **Mario Si3ri**.

- GitHub: [@ProgramaC++](https://github.com/MarioSi3ri/ProgramaC)

## 📄 Licencia

Este proyecto se distribuye bajo la **Licencia MIT**. Consulta el archivo [LICENSE](LICENSE) para conocer los términos completos.

---

<p align="center">
  Desarrollado con el lenguaje C++ como proyecto de aprendizaje e inicial de programación.
</p>
