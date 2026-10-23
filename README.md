# Proyecto: (Hola Mundo) — LPR 2026

**Escuela de Educación Secundaria Técnica N° 1 — Vicente López**  
**Curso:** 5° Año 3° División — Especialidad Informática / Programación  
**Materia:** Laboratorio de Programación (LPR)  
**Profesor:** Prof. York Mansilla Muñoz  
**Estudiante:** Alexander Luca Veit

## 📌 Descripción de la Actividad

Esta actividad corresponde a la configuración inicial del Entorno de Desarrollo Integrado (IDE) y la primera compilación nativa en C++. Los estudiantes configuran su espacio de trabajo en Visual Studio Code, estructuran el repositorio profesionalmente con control de versiones en Git, y compilan su primer binario de consola (`holamundo.exe`) utilizando el compilador GCC/G++ en Windows 10/11.

El objetivo es crear y compilar el programa clásico "Hola Mundo" en lenguaje C++, verificando la correcta instalación del compilador MinGW, las extensiones necesarias en VS Code y el flujo completo de compilación y ejecución.

## 🗂 Estructura del Repositorio

```text
holamundo/
├── scr/                # Código fuente y binario compilado
│   ├── holamundo.cpp   # Código fuente en C++
│   └── holamundo.exe   # Ejecutable generado
├── capturas/           # Capturas de pantalla del proceso
│   ├── gpp_version.png
│   ├── extensiones_vscode.png
│   └── ejecucion_hola_mundo.png
├── docs/               # Documentación
│   └── InformeProyectoHOLAMUNDO.pdf
├── .gitignore
├── LICENSE             # Licencia MIT
└── README.md
```

## 💻 Código Fuente

El programa se encuentra en `scr/holamundo.cpp`. Muestra un mensaje de bienvenida en consola e incluye el nombre del estudiante. Según la consigna, debe modificarse con el nombre y apellido real antes de compilar.

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "=====================================================" << endl;
    cout << "  Hola Mundo! Bienvenido al Taller de LPR 2026.      " << endl;
    cout << "  Estudiante: Alexander Veit   " << endl;
    cout << "=====================================================" << endl;
    return 0;
}
```

## 🛠️ Requisitos e Instalación

Para compilar y ejecutar este proyecto en tu computadora con Windows 10/11, necesitas contar con:

- **Visual Studio Code:** Con las extensiones oficiales C/C++ (Microsoft) y C/C++ Extension Pack.
- **Compilador MinGW (GCC/G++):** Configurado correctamente en las variables de entorno (`PATH` del sistema).
- **Git for Windows:** Para la gestión del repositorio y sincronización con GitHub.

## ▶️ Comandos para compilar y ejecutar (PowerShell - VS Code)

Asegurate de abrir la terminal integrada de VS Code (`Ctrl + Ñ`) y estar parado en la raíz de la carpeta `holamundo`.

### Verificar el compilador

```bash
g++ --version
```

### Compilar el código fuente

```bash
g++ ./scr/holamundo.cpp -o ./scr/holamundo.exe
```

### Ejecutar la aplicación

```bash
./scr/holamundo.exe
```

## 🧪 Evidencias

El repositorio incluye capturas del proceso en la carpeta `capturas/`:

- Verificación de la versión de `g++`
- Instalación/configuración de las extensiones de C/C++ en VS Code
- Ejecución exitosa del programa "Hola Mundo"

## 👤 Autor

- **Alexander Luca Veit** — Programador / Estudiante  
  GitHub: [Xen-alt10](https://github.com/Xen-alt10)  
  Repositorio: [holamundo](https://github.com/Xen-alt10/holamundo)

## 📄 Licencia

Este proyecto está bajo licencia [MIT](LICENSE). Copyright (c) 2026 Xen-alt10.
