# Apuntes · Inteligencia Artificial II

> Síntesis académica de los temas del 2do Parcial — UMSS, Facultad de Ciencias y Tecnología  
> Materia: **Inteligencia Artificial II** · Docente: Lic. Carmen Rosa Garcia Perez · 2026

---

## Ver el sitio

Desplegado en GitHub Pages:  
**[https://tu-usuario.github.io/nombre-del-repo](https://tu-usuario.github.io/nombre-del-repo)**

> Reemplaza la URL con la tuya al activar GitHub Pages en `Settings → Pages → Branch: main → / (root)`.

---

## Estructura del proyecto

```
/
├── index.html      # Landing page — índice visual de todos los capítulos
├── cap1.html       # Visión por Computadora
├── cap2.html       # Procesamiento de Lenguaje Natural (PLN)
├── cap3.html       # Caso combinado: Análisis de sentimiento + Conclusiones
├── cap4.html       # Razonamiento con Incertidumbre           (pendiente)
├── cap5.html       # Redes Generativas Antagónicas (GANs)     (pendiente)
├── cap6.html       # Algoritmos Genéticos                     (pendiente)
└── README.md
```

---

## Temas del examen 2do Parcial

| # | Tema | Archivo | Estado |
|---|------|---------|--------|
| 1 | Razonamiento con Incertidumbre | `cap4.html` |  Pendiente |
| 2 | Redes Generativas Antagónicas (GANs) | `cap5.html` |  Pendiente |
| 3 | Algoritmos Genéticos | `cap6.html` |  Pendiente |
| 4 | Visión por Computadora | `cap1.html` |  Listo |
| 5 | Procesamiento de Lenguaje Natural | `cap2.html` | Listo |

---

## Tecnologías

- **HTML5 + CSS3 puro** — sin frameworks, sin dependencias externas
- Cada archivo es completamente autocontenido (estilos en `<style>` interno)
- Compatible con cualquier navegador moderno
- Listo para GitHub Pages sin configuración adicional

---

## Contribuir (para compañeros del grupo)

### Agregar un nuevo capítulo

1. Crea tu archivo `cap4.html`, `cap5.html` o `cap6.html` siguiendo la misma estructura de los existentes.
2. Agrega el enlace a la tarjeta correspondiente en `index.html`.
3. Haz commit con el siguiente formato:

```bash
git add capX.html index.html
git commit -m "feat(capX): add <Nombre del Tema> notes"
git push origin main
```

### Convención de commits

| Prefijo | Uso |
|---------|-----|
| `feat:` | Nuevo capítulo o sección |
| `fix:` | Corrección de contenido o errores |
| `style:` | Cambios solo de diseño/CSS |
| `docs:` | Cambios en el README |
| `refactor:` | Reorganización de contenido sin cambiar la información |

---

##  Contenido por capítulo

### Cap. 1 — Visión por Computadora
- Imagen como dato numérico (muestreo, cuantización, histograma, ecualización)
- Filtrado espacial (Gaussiano, Sobel, Prewitt)
- Detector de bordes de Canny (pipeline completo de 4 etapas)
- Puntos clave y descriptores (Harris, SIFT, ORB, matching)
- Geometría de cámara, calibración, estereovisión, triangulación 3D
- Pipeline clásico de visión: SVM, k-NN, RANSAC

### Cap. 2 — Procesamiento de Lenguaje Natural
- Fundamentos del PLN y niveles lingüísticos
- Problemas del lenguaje: ambigüedad, variabilidad morfológica, Ley de Zipf
- Pipeline clásico vs. sistemas extremo a extremo
- Representaciones: BoW, TF-IDF, Word2Vec, GloVe, embeddings contextuales
- Modelos clásicos: Naive Bayes, HMM, CRF
- Deep Learning en PLN: RNN, LSTM, GRU
- Transformers, mecanismo de atención, positional encoding, LLMs
- Subareas del PLN moderno

### Cap. 3 — Caso Combinado y Conclusiones
- Análisis de sentimiento como pipeline completo de PLN
- Función Softmax, métricas (Precisión, Recall, F1-Score)
- Comparativa histórica: métodos clásicos vs. modernos en Visión y PLN
- Nexos entre ambas disciplinas: convolución vs. atención, Vision Transformers
- Tareas multimodales (VQA, generación de pies de foto, CLIP)
- Reflexiones finales sobre cuándo usar cada paradigma

---

## 🎓 Información académica

| Campo | Detalle |
|-------|---------|
| Universidad | Universidad Mayor de San Simón (UMSS) |
| Facultad | Ciencias y Tecnología |
| Carrera | Ingeniería Informática |
| Materia | Inteligencia Artificial II |
| Docente | Lic. Carmen Rosa Garcia Perez |
| Gestión | 2026 |
| Parcial | 2do Parcial |

---

*Apuntes elaborados con fines académicos a partir de los informes de exposición de los grupos de estudio.*