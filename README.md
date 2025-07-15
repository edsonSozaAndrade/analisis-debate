#CHECK MASTER BRANCH

# 📊 Análisis del Debate Presidencial Bolivia 2025

Este proyecto utiliza herramientas de ciencia de datos e inteligencia artificial para analizar el **debate presidencial de Bolivia 2025**, mediante técnicas de procesamiento de lenguaje natural (NLP), análisis de sentimiento y visualizaciones interactivas.

---

## 🧠 ¿Qué contiene este análisis?

### ✅ Archivos procesados:
- 📝 Transcripción (`.txt` / `.vtt`)
- 🔊 Diarización de locutores (`.rttm`, `.json`)
- 📄 Texto por locutor y fragmento

---

## 🔍 ¿Qué se analiza?

### 1. **Análisis de Sentimiento**
- Clasificación del tono por fragmento y por candidato.
- Gráfico de barras con promedio de sentimiento.
- **Gráficos temporales interactivos** por candidato: evolución del sentimiento minuto a minuto.

### 2. **Nubes de Palabras**
- Nube estática (imagen) y nube interactiva (HTML).
- Palabras filtradas por longitud y relevancia.
- Cada locutor tiene su propia nube personalizada.

### 3. **Palabras más frecuentes**
- Tabla con las 20 palabras más comunes por candidato.
- Visualización en `heatmap` para comparar frecuencias entre ellos.

### 4. **Palabras compartidas y únicas**
- Intersección y diferencias léxicas entre los discursos de cada candidato.

---

## 📁 Estructura del Repositorio

```
analisis-debate/
├── data/                    # Archivos originales y procesados
│   ├── debate.wav
│   ├── transcript.vtt
│   ├── diarization.json
│   └── diarization.rttm
│
├── graphs/                # Gráficos exportados en imagen
│   └── ...
│
├── scripts/                # Código exportado desde notebooks
│   └── Análisis Debate.py
│
├── README.md               # Documentación del proyecto
└── requirements.txt        # Dependencias para reproducir el análisis
└── Análisis Debate.ipynb   # Documento de Análisis
```

---

## 📌 Requisitos

Instala las dependencias con:

```bash
pip install -r requirements.txt
```

Algunas librerías utilizadas:
- `pandas`, `matplotlib`, `seaborn`
- `nltk`, `textblob`, `transformers`, `plotly`
- `wordcloud`, `kaleido`

---

## 📈 ¿Qué aporta este análisis?

- Transparencia y rendición de cuentas en discursos políticos.
- Visualización del uso del lenguaje emocional y positivo.
- Facilita el entendimiento ciudadano y el periodismo de datos.

---

## 📌 Cómo contribuir

¿Quieres mejorar el análisis o aplicarlo a otros países o elecciones? ¡Contribuciones son bienvenidas! Puedes abrir un issue o un pull request.

---

## 📄 Licencia

Este proyecto es de libre uso con fines académicos, periodísticos y ciudadanos.  
**Autor:** Edson Soza
