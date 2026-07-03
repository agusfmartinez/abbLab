# 🌳 ABB Lab

**Práctica interactiva de Árboles Binarios de Búsqueda (ABB / BST).**

Aplicación web para aprender y visualizar cómo funciona un Árbol Binario de Búsqueda. Ejecutá cada operación **paso a paso**, con el árbol dibujado en vivo y una explicación de qué compara el algoritmo y por qué va a la izquierda o a la derecha.

Pensada como herramienta de estudio para la materia **Estructura de Datos**.

> ⚠️ **Fines educativos.** Este proyecto fue creado con fines exclusivamente educativos y de aprendizaje, como apoyo para el estudio de estructuras de datos. No está pensado para uso en producción.

---

## ✨ Características

- **Visualización en vivo** del árbol (SVG), se reordena solo al insertar/eliminar.
- **Ejecución paso a paso** con controles ◀ Anterior · ▶ Auto · Siguiente ▶ y control de velocidad.
- **Panel explicativo**: cada paso describe la comparación y la decisión (izquierda/derecha).
- **Colores de estado**: nodo actual, camino recorrido, encontrado, a eliminar.
- **Estadísticas en vivo**: peso, altura, hojas, mínimo y máximo.
- Cero dependencias, cero instalación: **un solo archivo HTML**.

## 🧮 Operaciones incluidas

Espejan las definidas en el archivo `arboles_binarios.py`:

| Categoría | Operaciones |
|-----------|-------------|
| **Modifican el árbol** | Insertar · Buscar · Eliminar |
| **Recorridos** | Pre-orden · In-orden · Post-orden |
| **Consultas** | Mínimo · Máximo · Peso · Altura · Cantidad de hojas · ¿Está vacío? · Predecesor · Sucesor · Lista de pares · Profundidad de un dato · Nodos en un nivel |
| **Utilidades** | Cargar ejemplo · Insertar aleatorio · Vaciar |

> Mismo comportamiento que la implementación en Python: menor → izquierda, mayor → derecha, sin duplicados; la eliminación reemplaza por el **predecesor** (máximo del subárbol izquierdo).

## 🚀 Uso

1. Abrí `index.html` en cualquier navegador (doble clic).
2. Tocá **Ejemplo** para cargar un árbol de prueba (o insertá tus propios números).
3. Elegí una operación → se genera la secuencia de pasos.
4. Recorré con **◀ / Siguiente ▶**, o dejá correr con **▶ Auto** y ajustá la velocidad.

No requiere servidor ni instalar nada.

## 🌐 Publicar en GitHub Pages

1. Subí el repo a GitHub.
2. **Settings → Pages → Branch: `main` / root**.
3. Queda online en `https://<usuario>.github.io/<repo>/` (carga `index.html` en la raíz).

## 🛠️ Stack

HTML + CSS + JavaScript puro (vanilla). Árbol renderizado con SVG. Sin frameworks ni librerías externas.

## 📂 Estructura

```
.
├── index.html     # La app (todo en un archivo)
├── arboles_binarios.py   # Implementación de referencia en Python
└── README.md
```

## 👤 Autor

Desarrollado por **Agustín Martínez** — [Portfolio](https://agusfmartinez.vercel.app/)

## 📄 Licencia

MIT
