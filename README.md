# 🤖 IA para Humanos: Clase Piloto

**Fecha:** 22 de Noviembre, 2025  
**Lugar:** TES, Zürich  
**Temática:** Introducción a la Inteligencia Artificial, Desmitificación y Herramientas Prácticas.

Este repositorio contiene los recursos y notas clave de la sesión "IA para Humanos". El objetivo es pasar de la teoría a la práctica, entendiendo la IA no como magia, sino como una herramienta que requiere estructura y pensamiento crítico.

> **📥 [Descargar Presentación Completa (PDF)](IA_intro_221125_pdf.pdf)**
---

## 📋 Agenda

1.  **Bases y Desmitificación:** Entender qué es realmente la IA y desmontar mitos.
2.  **Herramientas y Prompting:** Dominar la fórmula para obtener resultados de calidad.
3.  **NotebookLM y Futuro:** Crear asistentes personalizados con tus propios datos.

---

## 🧠 1. ¿Qué es la IA Realmente?

### Programación Tradicional vs. Machine Learning
La diferencia fundamental radica en cómo se procesa la información:
* **Programación Tradicional:** Reglas explícitas definidas por humanos → Resultados predecibles.
* **Machine Learning:** Datos (Ejemplos) → La máquina encuentra patrones implícitos → Predicción probabilista.

> **Implicación Clave:** La IA no sigue instrucciones rígidas como un script antiguo; aprende de ejemplos.

### IA Estrecha (Narrow AI) vs. IA General
Actualmente, **no existe la IA General**. Trabajamos con "IA Estrecha", que es especialista en dominios específicos (Ajedrez, Visión, Traducción) pero tiene limitaciones claras fuera de su campo.

### ⚠️ Limitaciones y Alucinaciones
Las alucinaciones no son "errores" del sistema, son una limitación fundamental de los Modelos de Lenguaje (LLMs).
* **Lo que esperas:** Hechos verificados y admisión de incertidumbre.
* **Lo que obtienes:** Texto *plausible* pero no necesariamente verdadero.

---

## 🛠️ 2. Panorama de Herramientas y Comparativa

No existe "la mejor herramienta", sino la herramienta adecuada para cada tarea.

| Herramienta | Fortalezas Principales | Mejor Caso de Uso |
| :--- | :--- | :--- |
| **ChatGPT** | Conversacional, intuitivo, amplio conocimiento general. | Brainstorming, redacción, ideación general. |
| **Gemini** | Integración con Google, datos en tiempo real, multimodal. | Análisis de documentos, búsquedas con contexto actual. |
| **Claude** | Contexto masivo (200K tokens), razonamiento profundo, seguridad. | Análisis técnico, programación, documentos extensos. |
| **Hugging Face** | Modelos Open-Source, altamente personalizable. | Implementación local, modelos especializados, investigación. |

---

## ✍️ 3. La Anatomía del Prompt "Perfecto"

Para obtener valor real (10x), un prompt debe dejar de ser vago y pasar a ser estructurado.

### Los 5 Componentes Esenciales
1.  **ROL:** ¿Quién eres? (Ej. "Eres un experto en marketing digital...")
2.  **CONTEXTO:** ¿Cuál es la situación? (Ej. "Estamos lanzando un SaaS B2B...")
3.  **TAREA:** ¿Qué debo hacer? (Ej. "Crea 5 headlines...")
4.  **FORMATO:** ¿Cómo lo entrego? (Ej. "Lista numerada, tono profesional...")
5.  **RESTRICCIONES:** ¿Qué evito? (Ej. "Evita jerga técnica...")

### Ejemplo: Vago vs. Estructurado
> **Prompt Vago:** "¿Qué es machine learning?"  
> ❌ **Resultado:** Definición genérica de Wikipedia.

> **Prompt Estructurado:** "ROL: Profesor de ciencia de datos para ejecutivos... CONTEXTO: Audiencia sin background técnico... TAREA: Explica qué es ML usando una analogía de negocios..."  
> ✅ **Resultado:** Explicación adaptada, memorable y accionable.

---

## 📓 4. Asistentes Personales: NotebookLM

Herramienta de Google para "Grounded AI" (IA fundamentada en *tus* fuentes).

* **Flujo de trabajo:** Cargar fuentes (PDFs, Webs) → Hacer preguntas → Generar Artefactos (Resúmenes, FAQs, Guías).
* **Diferencia Clave:** A diferencia de ChatGPT (conocimiento general), NotebookLM responde **solo** basándose en los documentos que tú subes, reduciendo drásticamente las alucinaciones.

> 🚨 **ADVERTENCIA CRÍTICA:** En NotebookLM **no hay papelera de reciclaje**. Si borras un cuaderno, se elimina permanentemente junto con todo el historial y notas. Haz backups exportando tu contenido regularmente.

---

## 🔗 Recursos y Videos

Enlaces mencionados durante la presentación para profundizar:

* **Fundamentos de IA (Google):** [Ver video en YouTube](https://www.youtube.com/watch?v=xnPkEDejc-g&fs=1&hl=es)
* **Conceptos y Aplicaciones (Dot CSV):** [Ver video en YouTube](https://www.youtube.com/watch?v=KytW151dpqU&fs=1&hl=es&t=0)

---

## 🚀 Próximos Pasos

1.  **Experimenta:** Prueba el mismo prompt en ChatGPT, Gemini y Claude para ver las diferencias.
2.  **NotebookLM:** Crea tu primer cuaderno con 3-5 fuentes de confianza.
3.  **Aplica la Estructura:** Nunca escribas un prompt sin definir al menos el Rol y la Tarea.

> *"La IA es una herramienta. No es magia, requiere estructura, pensamiento crítico y validación."*

---
*Presentación creada para TES Zürich, 2025.*
