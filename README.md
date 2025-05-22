# Sistema Vacacional - Coca-Cola Company

Este programa en Java permite calcular los días de vacaciones a los que tiene derecho un trabajador de la empresa Coca-Cola Company. El cálculo se realiza en función de dos factores: la clave del trabajador (que representa su nivel jerárquico o departamento) y su antigüedad en años dentro de la empresa.

## 📋 ¿Cómo funciona?

1. El usuario introduce el nombre del trabajador.
2. Se solicita la antigüedad (en años) del trabajador.
3. Se solicita la clave del trabajador (1, 2 o 3).
4. El sistema muestra cuántos días de vacaciones le corresponden según los datos proporcionados.

### Reglas de vacaciones

- **Clave 1:**
  - 1 año → 6 días
  - 2 a 6 años → 14 días
  - 7 o más años → 20 días

- **Clave 2:**
  - 1 año → 7 días
  - 2 a 6 años → 15 días
  - 7 o más años → 22 días

- **Clave 3:**
  - 1 año → 10 días
  - 2 a 6 años → 20 días
  - 7 o más años → 30 días

## ✅ Requisitos

- Java JDK 8 o superior
- Compilador de Java (como `javac`)
- Consola o IDE (NetBeans, IntelliJ, Eclipse, etc.)

## 🚀 Compilación y ejecución

```bash
javac Sistema.java
java Sistema
