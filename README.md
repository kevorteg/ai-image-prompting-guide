# Guía de Ingeniería de Prompts para Imágenes

Esta guía está diseñada como una referencia concisa y profesional para la creación efectiva de imágenes mediante Inteligencia Artificial (Midjourney, Stable Diffusion, DALL-E).

---

## 1. ¿Qué es un Prompt?

En el contexto de la generación de imágenes, un **prompt** es la descripción textual que interpreta el modelo de IA para sintetizar una representación visual. No es simplemente una orden, sino una **especificación técnica** que define el contenido, el estilo y los atributos de la imagen resultante.

Un buen prompt elimina la ambigüedad y guía a la IA hacia un resultado predecible.

---

## 2. Estructura Fundamental

Para lograr resultados consistentes, se recomienda estructurar el prompt siguiendo esta jerarquía lógica. No es necesario usar todas las categorías, pero mantener el orden ayuda a la interpretación del modelo.

### A. Sujeto (Subject)
¿Qué es la imagen? Define el elemento central con precisión.
*   *Ejemplo:* "Un astronauta", "Un gato persa", "Un paisaje urbano cyberpunk".

### B. Medio y Estilo (Medium & Style)
¿Cómo se ve? Define la estética visual o la técnica artística.
*   *Fotografía:* "Fotografía macro 35mm", "Retrato de estudio", "Polaroid vintage".
*   *Arte:* "Pintura al óleo", "Ilustración vectorial", "Render 3D", "Estilo anime retro".

### C. Iluminación y Atmósfera (Lighting & Vibe)
Define el clima y la luz, cruciales para el realismo y la emoción.
*   *Luz:* "Iluminación cinematográfica", "Hora dorada", "Luz volumétrica", "Neón".
*   *Atmósfera:* "Etéreo", "Oscuro y lúgubre", "Vibrante", "Minimalista".

### D. Composición y Cámara (Composition)
Cómo se encuadra la imagen.
*   *Encuadres:* "Gran angular", "Primer plano (Close-up)", "Vista de pájaro".
*   *Detalles:* "Enfoque nítido", "Profundidad de campo (bokeh)", "Simétrico".

---

## 3. Galería de Ejemplos

A continuación, se presentan ejemplos desglosados para ilustrar cómo la combinación de estos elementos crea resultados específicos.

### Ejemplo 1: Fotografía de Retrato Dramático

Este prompt utiliza técnicas de iluminación específicas para crear misterio.

**Prompt:**
```text
Hyperrealistic portrait of a woman standing in a black background. Lighting is a narrow beam spotlight focused only on the face, creating high contrast and deep shadows (chiaroscuro). Long dark hair fading into the shadows. Her expression is mysterious, looking directly at the camera. Shot on 85mm lens, f/1.8 for shallow depth of field.
```

**Análisis:**
*   **Sujeto:** Retrato de mujer.
*   **Estilo:** Hiperrealista.
*   **Iluminación:** "Narrow beam spotlight", "Chiaroscuro" (define el dramatismo).
*   **Técnica:** "85mm lens, f/1.8" (lenguaje fotográfico real para desenfoque y proporción).

---

### Ejemplo 2: Arquitectura Surrealista

Este prompt mezcla elementos urbanos con fantasía, requiriendo descripciones detalladas de la interacción entre objetos.

**Prompt:**
```text
A futuristic L-shaped urban intersection in Tokyo involves a giant 3D LED screen. A giant playful kitten appears to be popping out of the screen, reaching for pedestrians with 3D depth effect. Realistic daylight, vibrant city colors, highly detailed architectural elements, 8k resolution, unreal engine 5 render style.
```

**Análisis:**
*   **Sujeto:** Intersección urbana con pantalla 3D y un gato gigante.
*   **Acción:** "Popping out of the screen" (define la dinámica 3D).
*   **Estilo:** "Unreal Engine 5 render", "8k" (indica alta fidelidad digital, no necesariamente fotografía real).

---

### Ejemplo 3: Ilustración Botánica Vintage

Un ejemplo de estilo artístico específico.

**Prompt:**
```text
Botanical illustration of a medicinal herb on parchment paper. Faded watercolor style, detailed line work, ink outlines. text labels in latin, vintage scientific diagram aesthetic, soft desaturated colors.
```

**Análisis:**
*   **Medio:** "Botanical illustration", "Watercolor".
*   **Soporte:** "Parchment paper" (papel pergamino).
*   **Atmósfera:** "Vintage scientific diagram".

---

## Consejos de Optimización

1.  **Iteración:** Rara vez el primer prompt es perfecto. Ajusta una variable a la vez (ej. cambia solo la iluminación).
2.  **Referencia de Estilos:** Mencionar directores de cine (ej. *Wes Anderson*), pintores (*Van Gogh*) o épocas (*1980s retro*) es un atajo muy potente.
3.  **Orden de Importancia:** Lo que escribes al principio del prompt tiene más peso para la IA que lo que escribes al final.
