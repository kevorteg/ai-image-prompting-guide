# Awesome Nano Banana Pro 🍌

> **Guía Definitiva de Ingeniería de Prompts**

Bienvenido a la guía profesional de *Prompt Engineering*. Este documento sirve como una referencia completa para entender, clasificar y dominar el arte de comunicarse con IAs generativas.

---

## 📘 1) ¿Qué es un Prompt?

**Definición:**
Un prompt es una instrucción o conjunto de instrucciones que le das a una IA para generar una respuesta deseada.

**Ejemplo sencillo:**
> "Describe la historia de David y Goliat en un tono inspirador y breve."

---

## 🧠 2) CLASIFICACIÓN DE PROMPTS

Los prompts se pueden agrupar por formato, objetivo y estructura avanzada.

### � A. Por formato

#### 🔹 1. Prompt de Texto Plano
El más común. Usado cuando quieres respuestas en lenguaje natural.

*Ejemplo:*
> "Escribe un poema sobre esperanza sin mencionar la palabra esperanza."

#### 🔹 2. Prompt Estructurado (JSON)
Usado cuando necesitas que la IA responda con un formato predecible y parseable. Ideal para automatización e integración con código.

*Ejemplo:*
```json
{
  "question": "¿Cuál es la capital de Francia?",
  "language": "español"
}
```

#### 🔹 3. Prompt por Bloques
Divide la instrucción en partes para guiar a la IA paso a paso.

*Ejemplo:*
1. Describe qué es la fotosíntesis.
2. Dame un ejemplo aplicado a la vida diaria.

#### 🔹 4. Prompt con Roles
Le das a la IA un rol específico para ajustar el tono y la autoridad.

*Ejemplo:*
> "Eres un profesor de física con 10 años de experiencia. Explica la relatividad a un estudiante de secundaria."

#### 🔹 5. Prompt con Restricciones
Para explicitar lo que **no** quieres.

*Ejemplo:*
> "Describe una receta de pizza que no incluya queso ni tomate."

### 📍 B. Por objetivo

*   🟢 **Prompts descriptivos:** Buscan que la IA describa algo. ("Describe…")
*   🟡 **Prompts comparativos:** Comparan dos o más cosas. ("Compara X y Y…")
*   🔵 **Prompts instructivos:** Dan instrucciones paso por paso. ("Cómo hacer…")
*   🔴 **Prompts opinativos:** Piden opinión o juicio simulado. ("¿Cuál es la mejor…")

### 📍 C. Avanzados

#### 💡 1. Prompts con contexto
Incluyen información previa para que la IA “entienda el marco”.

*Ejemplo:*
> "Tengo 25 años, vivo en Cali y estoy aprendiendo IA. Recomiéndame recursos para comenzar en machine learning."

#### 🔁 2. Prompts iterativos
Solicitan a la IA que refine su respuesta.

*Ejemplo:*
> "Escribe un ensayo de 200 palabras. Ahora revísalo para que sea más claro."

#### 🧩 3. Prompts en cadena o "chain-of-thought"
Guían a la IA paso a paso mentalmente, ideal para tareas complejas.

---

## 📘 3) PROMPTS ESTRUCTURADOS — CUÁNDO USAR JSON

JSON se usa cuando:
*   ✔ Necesitas respuestas formateadas
*   ✔ Vas a extraer información automáticamente
*   ✔ Quieres que la IA responda como objeto de datos
*   ✔ Estás trabajando con código, bots o sistemas automatizados

*Ejemplo de JSON para resumen:*
```json
{
  "title": "Resumen del Génesis 1",
  "summary": "string"
}
```

---

## 🧠 4) JSON VS TEXTO PLANO

| Situación | Mejor usar |
| :--- | :--- |
| Generar un artículo | **Texto plano** |
| Integrar IA a una API | **JSON** |
| Hacer imagen con especificaciones | **Texto concreto** |
| Hacer diálogo estructurado | **JSON** |

---

## 📘 5) PROMPTS PARA IA DE IMÁGENES

Aquí hay subtipos:

*   🎨 **a) Prompt Descriptivo:** Describe lo que quieres ver.
    *   *"Un paisaje surrealista con montañas flotantes y un río violeta."*
*   � **b) Prompt Técnico:** Incluye parámetros de cámara, luz, color, etc.
    *   *"Fotografía 35mm, luz dorada al atardecer, enfoque suave."*
*   📊 **c) Prompt Referencial:** Incluye referencias de estilo.
    *   *"En el estilo visual de Studio Ghibli, con colores pastel y luz suave."*

---

## 📘 6) RECOMENDACIONES PRÁCTICAS
1.  ✅ **Sé específico:** Cuanto más claro, mejor.
2.  ✅ **Usa contexto:** La IA no “sabe” sin contexto.
3.  ❌ **Evita ambigüedades:** "No lo hagas feo" → ¿qué es “feo”?

---

## 📘 7) ERRORES COMUNES Y CÓMO EVITARLOS

*   ❌ **“Sé más creativo”**
    *   👉 **Mejor:** "Sé creativo con metáforas poéticas, evitando clichés."
*   ❌ **“Hazlo bonito”**
    *   👉 **Mejor:** "Aplica lenguaje cinematográfico con foco en emoción y tono."

---

## 📘 8) CASOS PRÁCTICOS (TEMPLATES)

### 📍 A) TEMPLATE PARA PROMPT DE TEXTO
> Eres un experto en [ÁREA]. Explica [TEMA] en un lenguaje para [AUDIENCIA], con ejemplos y pasos claros.

### 📍 B) TEMPLATE PARA PROMPT DE IMAGEN
> Un [TEMA] en estilo [ESTILO VISUAL], con [ATMÓSFERA], [LUCES], [CÁMARA], [COLOR].

### 📍 C) TEMPLATE PARA PROMPT JSON
```json
{
  "task": "string",
  "input": "string",
  "format": "string",
  "language": "string"
}
```

---

## 🧠 9) EXTENSIONES Y RICH PROMPTS

Las APIs modernas (OpenAI, Gemini) aceptan instrucciones múltiples, persona/rol, indicaciones de tono, restricciones, prioridades y formatos de salida específicos.

---

## 📘 10) EJEMPLOS EN DISTINTOS DOMINIOS

*   🎓 **Educadores:** "Explica fotosíntesis a un estudiante de 15 años usando analogías de la vida diaria."
*   💻 **Programadores:** "Genera un script Python que extraiga datos de un CSV y muestre gráficas de tendencias."
*   🎨 **Diseño:** "Un póster minimalista con color azul y mensaje de esperanza."

---

## 🧭 11) FUTURO DEL PROMPTING

Con la IA multimodal veremos más prompts para imágenes, combinados (texto + imagen) y JSON + texto explicado.

---

## 📘 12) EJEMPLOS AVANZADOS EN README

**📌 Prompt con persona + restricciones:**
> "Eres un entrenador de salud. Da planes de ejercicio evitando dietas ricas en azúcar."

**📌 Prompt con código esperado:**
```json
{
  "language": "python",
  "task": "data_analysis",
  "output": ["summary","chart"],
  "constraints": {"no_gui": true}
}
```

---

## 🧠 13) RECOMENDACIONES FINALES

*   ✦ Usa contexto siempre
*   ✦ Define qué quieres, no solo qué no quieres
*   ✦ Lectura previa antes de enviar
*   ✦ Si cambia el objetivo, reformula el prompt

---

## � Galería de Ejemplos: Prompt vs. Imagen

A continuación se muestran ejemplos visuales de cómo un prompt estructurado se traduce en una imagen final.

### 🏙️ 1. Pantalla LED 3D Urbana

**Prompt:**
```text
An enormous L-shaped glasses-free 3D LED screen situated prominently at a bustling urban intersection, designed in an iconic architectural style reminiscent of Shinjuku in Tokyo or Taikoo Li in Chengdu. The screen displays a captivating glasses-free 3D animation featuring [scene description]. The characters and objects possess striking depth and appear to break through the screen's boundaries, extending outward or floating vividly in mid-air. Under realistic daylight conditions, these elements cast lifelike shadows onto the screen's surface and surrounding buildings. Rich in intricate detail and vibrant colors, the animation seamlessly integrates with the urban setting and the bright sky overhead.

----
scene description:
[An adorable giant kitten playfully paws at passing pedestrians, its fluffy paws and curious face extending realistically into the space around the screen.]
```

*(Aquí iría la imagen generada, mostrando el gato gigante saliendo de la pantalla)*

---

### 👤 2. Retrato Estilo "Spotlight"

**Prompt:**
```text
Generate a hyperrealistic realistic-anime portrait of a female character standing in a completely black background.
Lighting: use a **narrow beam spotlight** focused only on the center of the face.
The edges of the light must be sharp and dramatic.
All areas outside the spotlight should fall quickly into deep darkness
(high falloff shadow), almost blending into the black background.
Not soft lighting.
Hair: long dark hair with some strands falling over the face. The lower parts of the hair should fade into the shadows.
Pose: one hand raised gently to the lips in a shy, hesitant gesture.
Eyes looking directly at the camera with a mysterious mood.
Clothing: black long-sleeve knit sweater;
the sweater and body should mostly disappear into the darkness with minimal detail.
Overall tone: dark, moody, dramatic, mysterious.
High-contrast only in the lit portion of the face.
Everything outside the spotlight should be nearly invisible.
```

*(Aquí iría la imagen generada, mostrando el retrato dramático)*

---
*Más ejemplos próximamente...*
# ai-image-prompting-guide
