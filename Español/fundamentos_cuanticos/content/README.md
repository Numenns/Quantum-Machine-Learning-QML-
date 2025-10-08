#### Fundamentos de la Mecánica Cuántica: 

Qubit, Superposición, Entrelazamiento, Medición, Puertas y Colapso

---

### ¿Qué es un Qubit?

Un **qubit**, o bit cuántico, es la unidad básica de información en la computación cuántica, introducida por Benjamin Schumacher.  
A diferencia de un bit clásico, que solo puede ser `0` o `1`, un qubit puede existir en **superposición**, representando `0`, `1` y todos los estados intermedios simultáneamente.  

**Definición matemática:**  
Un qubit se representa como una combinación lineal de estados base:

$$
|\psi\rangle = \alpha|0\rangle + \beta|1\rangle, \quad \text{con } |\alpha|^2 + |\beta|^2 = 1
$$

Los qubits pueden implementarse usando **fotones, iones atrapados, electrones, átomos o circuitos superconductores**, pero requieren entornos altamente controlados (a menudo cerca del cero absoluto) para evitar la **decoherencia**.  

**Aplicaciones:** criptografía, medicina, investigación climática e inteligencia artificial.

[![Miniatura del video](https://img.youtube.com/vi/2pB87H3_F_c/maxresdefault.jpg)](https://www.youtube.com/watch?v=2pB87H3_F_c)

---

### Superposición Cuántica

La superposición establece que una partícula (electrón, fotón, etc.) puede existir en múltiples estados a la vez hasta que se realiza una medición.  

**Forma matemática:**

$$
|\psi\rangle = \alpha|0\rangle + \beta|1\rangle, \quad |\alpha|^2 + |\beta|^2 = 1
$$

**Representación en la Esfera de Bloch:**  
El estado de un qubit puede expresarse como:

$$
|\psi\rangle = \cos\left(\frac{\theta}{2}\right)|0\rangle + e^{i\phi}\sin\left(\frac{\theta}{2}\right)|1\rangle
$$

**Ejemplos:** el gato de Schrödinger, experimento de la doble rendija.  

[![Miniatura del video](https://img.youtube.com/vi/kmCZMLfo_ak/maxresdefault.jpg)](https://www.youtube.com/watch?v=kmCZMLfo_ak)

---

### Entrelazamiento Cuántico

El entrelazamiento ocurre cuando dos o más partículas comparten un estado de tal manera que una no puede describirse independientemente de la otra.  

**Ejemplo matemático (estado de Bell):**

$$
|\Phi^+\rangle = \frac{1}{\sqrt{2}} (|00\rangle + |11\rangle)
$$

**Aplicaciones:** criptografía cuántica, teletransportación, computación y metrología.

[![Miniatura del video](https://img.youtube.com/vi/9vDyS2_Hufk/maxresdefault.jpg)](https://www.youtube.com/watch?v=9vDyS2_Hufk)

---

### Medición Cuántica

La medición cuántica hace que el sistema colapse a un estado definido.  

**Regla matemática:**  
Al medir $|\psi\rangle = \alpha|0\rangle + \beta|1\rangle$:

- Probabilidad de $|0\rangle$: $P(0) = |\alpha|^2$  
- Probabilidad de $|1\rangle$: $P(1) = |\beta|^2$

**Interpretaciones:** Copenhague, Muchos mundos, Colapso objetivo, Hipótesis de la conciencia.

[![Miniatura del video](https://img.youtube.com/vi/mqofuYCz9gs/maxresdefault.jpg)](https://www.youtube.com/watch?v=mqofuYCz9gs)

---

### Puertas Cuánticas

Las puertas cuánticas son los bloques fundamentales de las computadoras cuánticas.  
Operan sobre qubits, que son unidades especiales de información capaces de representar tanto 0 como 1 al mismo tiempo. Esto las diferencia de las computadoras clásicas, donde cada bit es solo 0 o 1.

Cada puerta cuántica cambia el estado de un qubit de una manera muy específica — puede imaginarse como una rotación o un giro en la “dirección” del qubit dentro de un espacio tridimensional.

**Puertas cuánticas comunes**

- **Puerta X (Pauli-X)** – Funciona como una puerta NOT en la computación clásica: cambia 0 por 1 y 1 por 0.  
- **Puerta Y (Pauli-Y)** – Rota el qubit en otra dirección, combinando un giro y una torsión.  
- **Puerta Z (Pauli-Z)** – Mantiene el valor del qubit, pero cambia su “fase”, como si ajustara su sincronización interna.  
- **Puerta Hadamard (H)** – Coloca el qubit en una mezcla de 0 y 1 al mismo tiempo. Esto se llama superposición y es una de las características principales de la computación cuántica.  
- **Puertas de fase (S, T)** – Cambian la forma en que se comporta la onda del qubit sin invertir su valor.  
- **Puerta CNOT (Control-NOT)** – Actúa sobre dos qubits. Invierte el segundo solo si el primero es 1. Esto permite que los qubits se entrelacen, es decir, que sus valores queden conectados de una manera que los bits normales no pueden.  

**Aplicaciones:** algoritmo de Shor, búsqueda de Grover, corrección de errores, simulación cuántica.

[![Miniatura del video](https://img.youtube.com/vi/g_IaVepNDT4/maxresdefault.jpg)](https://www.youtube.com/watch?v=g_IaVepNDT4)

---

### Colapso Cuántico y Conciencia

El colapso es la transición de la superposición a un único resultado cuando se realiza una medición.  

**Interpretaciones:** Copenhague, Muchos mundos, Colapso objetivo, Hipótesis de la conciencia.  

**Crítica a la hipótesis de la conciencia:** no tiene respaldo empírico; la decoherencia explica el colapso de manera suficiente.  

[![Miniatura del video](https://img.youtube.com/vi/LOVHlg9tuyc/maxresdefault.jpg)](https://www.youtube.com/watch?v=LOVHlg9tuyc)

---

