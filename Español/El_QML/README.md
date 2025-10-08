# ¿Qué Aporta la Computación Cuántica al Machine Learning?

* **Superposición y entrelazamiento:** permiten representar muchos estados al mismo tiempo, ampliando el espacio de datos.
* **Interferencia cuántica:** ayuda a resaltar patrones significativos y reducir el ruido.
* **Ventajas potenciales:** mayor velocidad de cómputo, representaciones de datos más ricas y nuevos métodos de aprendizaje.
* **Limitaciones actuales:** los computadores cuánticos aún son pequeños y ruidosos (estamos en la era **NISQ** — *Noisy Intermediate-Scale Quantum* o “Cuántica de Escala Intermedia Ruidosa”).

---

## Tipos de Modelos de QML

| Tipo                                             | Descripción Breve                                                                                                                                |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Híbrido Clásico–Cuántico**                     | Combinan componentes clásicos (como la optimización y el entrenamiento) con circuitos cuánticos parametrizados. Son los más comunes actualmente. |
| **Kernels Cuánticos**                            | Transforman datos clásicos en estados cuánticos y usan productos internos cuánticos para realizar clasificación.                                 |
| **VQC (Clasificadores Cuánticos Variacionales)** | Circuitos cuánticos con parámetros ajustables que aprenden a clasificar datos a partir de mediciones.                                            |

---

## Objetivo Práctico

Familiarizarse con herramientas como **Qiskit**, **PennyLane** o **TensorFlow Quantum**, y realizar experimentos sencillos usando **simuladores cuánticos**.
Estos experimentos permiten comprender cómo interactúan los componentes clásicos y cuánticos en los modelos híbridos.

---

## Video Recomendado

[![Quantum Machine Learning Tutorial](https://img.youtube.com/vi/ckJMylEYgIw/maxresdefault.jpg)](https://www.youtube.com/watch?v=tM53iQhI0yM)

(imagen no es la miniatura del video)
---
Este código organiza y separa datos de clientes utilizando una combinación de aprendizaje automático clásico y computación cuántica.

Paso a paso:

Carga los datos de clientes — por ejemplo, ingresos, gastos e historial crediticio.
También incluye una columna que indica si cada cliente incumplió (no pagó) o no incumplió (pagó normalmente).

Prepara los datos — los limpia, los normaliza y los divide en dos partes:

una parte para entrenar el modelo,

otra parte para probarlo.

Reduce la información (usando PCA) para quedarse solo con las características más importantes que ayudan a distinguir a los clientes.

Utiliza un modelo cuántico — este modelo convierte los datos en una representación cuántica y aprende a dividir a los clientes en dos grupos:

los que probablemente incumplan,

y los que probablemente paguen.

Evalúa qué tan bien el modelo aprendió a separar los grupos.
Los resultados (94 % de exactitud, 0.96 de AUC) muestran que el modelo divide eficazmente los datos entre los dos tipos de clientes.

En resumen, este programa toma los datos de los clientes, los analiza y usa un modelo cuántico para aprender a separar quién pagará y quién no pagará. No ordena los datos como una lista, sino que los divide en grupos claros según su comportamiento.
