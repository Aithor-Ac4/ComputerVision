# 🧠 Computer Vision para Scouting y Análisis Táctico en Fútbol

Automatiza el análisis de vídeo mediante detección de jugadores usando IA con modelos preentrenados. Este proyecto permite extraer información estructurada (coordenadas, eventos) en segundos sin necesidad de entrenar modelos desde cero.

<p align="center">
  <img src="./RM_BOR - IA_1.png" alt="Frame 1" width="30%" />
  <img src="./RM_BOR - IA_2.png" alt="Frame 2" width="30%" />
  <img src="./RM_BOR - IA_3.png" alt="Frame 3" width="30%" />
</p>

## 🎯 Objetivo

- Maximizar la eficiencia del scouting y análisis táctico.
- Detectar jugadores automáticamente desde vídeo real.
- Generar salidas reutilizables (CSV, clips) para informes técnicos, modelos de IA o dashboards.

## ⚙️ Tecnologías utilizadas

- `Python 3.11`
- [`YOLOv8`]
- `OpenCV`
- `pandas`
- `Google Colab` (entorno de pruebas)

## ✅ Características

- Detección automática de jugadores (`class: person`) usando `YOLOv8x`.
- Procesamiento de vídeo en formato `.mp4` o `.mov`.
- Exportación de coordenadas y confianza a `.csv`.
- Inserción de marca de agua personalizada.
- Visualización directa de frames con bounding boxes.
- Compatible con vídeos verticales (Instagram, Reels) y widescreen.


## 📌 Aplicaciones

- Scouting individual o colectivo
- Análisis posicional
- Preparación de partidos
- Segmentación automática para clips tácticos
- Integración con OCR, tracking o IA de eventos
