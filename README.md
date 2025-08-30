# Deep Learning – Foundation Models  

# Introducción
- El auge de los **Foundation Models** (FM): BERT, DALL·E, GPT-3.  
- Entrenados con datos masivos y generalistas.  
- Adaptables a múltiples tareas downstream.  
- Paradigma central en IA actual.  

---

# Contexto histórico
- 1950s–2000s: IA → Machine Learning → Deep Learning.  
- 2010s: Deep Learning revoluciona la industria.  
- 2020s: Surge el concepto de **Foundation Models**.  

---

# Definición de Foundation Models
- Modelos entrenados en datos amplios y diversos.  
- Adaptables a múltiples tareas mediante fine-tuning.  
- Escala masiva produce **capacidades emergentes**.  
- Riesgos y oportunidades sociotécnicas.  

---

# Reporte clave (Stanford CRFM, 2021)
- Documento fundacional: *On the Opportunities and Risks of Foundation Models*.  
- Autores: Percy Liang y colaboradores.  
- Riesgos y oportunidades:  
  - Capacidad y generalización.  
  - Impacto social, económico y ambiental.  
  - Homogeneización de modelos → defectos heredados.  

---

# Avances técnicos clave
- Modelos Seq2Seq con atención → limitaciones en secuencias largas.  
- **Transformers**: arquitectura basada en auto-atención.  
- Ventajas: mayor eficiencia, dependencias largas, escalabilidad.  
- Encoder–Decoder sin recurrencia.  

---

# Auto-atención
- Cada elemento de la secuencia depende de otros.  
- Extensión a **auto-atención multimodal** (texto, imágenes, audio, etc.).  
- Incorporación del orden mediante embeddings posicionales.  
- Elemento clave del Transformer (aunque en debate).  

---

# Transformers → Revolución
- Entrenamiento supervisado inicial (traducción).  
- **Pre-entrenamiento + fine-tuning** para transferir conocimiento.  
- Limitación: falta de datos etiquetados suficientes.  
- Solución: **aprendizaje autosupervisado**.  

---

# BERT y variantes
- BERT: modelo pre-entrenado con tareas de enmascaramiento.  
- Transferencia a múltiples idiomas y aplicaciones.  
- Escala y auto-supervisión impulsan su éxito.  

---

# Tres conceptos clave de Transformers
- Arquitectura generalista (sesgo inductivo en atención).  
- Entrenamiento autosupervisado masivo.  
- Alineamiento con humanos y aplicaciones como paso final.  

---

# Casos de uso de LLMs
- Asistentes de programación (GitHub Copilot).  
- Tutores virtuales.  
- Automatización de tareas administrativas.  

---

# Vision Transformers (ViT)
- Reemplazan CNNs en visión por atención.  
- Entrenamiento incluso auto-supervisado.  
- Caso de uso principal: transferencia de conocimiento.  

---

# Multimodalidad
- Fusión de texto + visión.  
- **CLIP**: entrenamiento contrastivo en 400M pares texto-imagen.  
- Zero-shot classification y aplicaciones visuales múltiples.  

---

# Modelos de difusión
- Nueva generación en generación de imágenes.  
- DALL·E 2: combinación CLIP + difusión.  
- DALL·E 3: integración con GPT-4 para prompts más detallados.  

---

# Escalamiento
- Sin aparente límite en tamaño y datos.  
- **Leyes de escala** permiten predecir mejoras.  
- Datos dominan sobre parámetros.  
- Ejemplo: Gopher (280B) vs Chinchilla (70B) → datos más relevantes.  

---

# Debate sobre auto-atención
- Artículo (2023): lo esencial es la **predicción autoregresiva**, no la auto-atención.  
- Autoregresión produce buenas features de entrada.  
- Trade-off: rotulado de datos vs tamaño de red.  

---

# Ideas finales
- Foundation Models dominarán la próxima década.  
- Riesgos y oportunidades requieren comprensión interdisciplinaria.  
- La industria ya ofrece **AI-as-a-service**.  
- Entender fundamentos será clave para aplicaciones específicas.  
- Seguir estudiando es esencial: el panorama cambia cada año.  

---

# Referencias y enlaces
- Stanford CRFM (2021): *On the Opportunities and Risks of Foundation Models*.  
- Jay Alammar: *Illustrated Transformer*.  
- Artículos recientes sobre leyes de escala y auto-atención.  
- Ejemplos: GitHub Copilot, CLIP, DALL·E.  
