# 🔳 OpenGL-3D: Proyecto de Gráficos Básicos

Este repositorio contiene ejemplos y ejercicios de programación en C++ que utilizan la biblioteca de gráficos **OpenGL** para la visualización de elementos 3D y 2D.

El foco principal es entender los conceptos básicos de la librería GLut para inicialización de ventanas y el *pipeline* de renderizado.

---

## 📁 Archivo Clave: cuadro.cpp

El archivo `cuadro.cpp` implementa un algoritmo sencillo de gráficos 2D dentro de un contexto OpenGL.

### **¿Qué hace el algoritmo?**

El programa en C++:

1.  **Inicializa** una ventana de gráficos utilizando la biblioteca **GLUT**.
2.  **Define** las propiedades de la visualización (proyección ortogonal 2D).
3.  **Dibuja** un elemento gráfico básico (un "cuadro" o polígono simple) utilizando comandos de dibujo de OpenGL como `glBegin()` y `glVertex2f()`.

En esencia, es uno de los programas más fundamentales para **verificar** que la configuración de C++, OpenGL y GLUT está funcionando correctamente en un sistema, ya que produce una salida gráfica simple.

---

### **Instrucciones de Compilación (Ejemplo)**

Para compilar y ejecutar este archivo en un entorno Linux o en un entorno con las librerías GLUT y GL/GLU instaladas, se necesitaría un comando similar a este:

```bash
g++ cuadro.cpp -o cuadro -lGL -lGLU -lglut
./cuadro
