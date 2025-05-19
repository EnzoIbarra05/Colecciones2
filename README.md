# 🚗 Proyecto Java – Colecciones y Estadísticas de Objetos

Este proyecto está centrado en el uso de **colecciones en Java** y operaciones comunes como recorridos, sumatorias, cálculos de promedio, y determinación de valores máximos y mínimos en una lista de objetos. Los ejemplos están basados en una colección de objetos `Auto`.

## 📚 Tabla de Contenidos

- Ciclo For Each en Java
- Promedio y Sumatoria en una Colección
- Máximos y Mínimos en una Colección
- Conclusión y aprendizaje

---

## 🔁 Parte 1: Ciclo For Each en Java

Esta sección demuestra cómo recorrer una colección de objetos utilizando el bucle `for-each`, que ofrece una forma sencilla y legible de iterar sobre listas.

### ✨ Objetivo

Recorrer una lista de autos (`ArrayList<Auto>`) e imprimir su información por consola.

### 🧪 Código de ejemplo

```java
public void mostrarAutos() {
    if (autos.isEmpty()) {
        System.out.println("No hay autos");
    } else {
        // Mostrando con for-each
        for (Auto auto : autos) {
            System.out.println(auto);
        }
    }
}
