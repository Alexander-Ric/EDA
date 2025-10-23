# <img src="img/introduccion.jpg" width="100%" alt="Cabecera del proyecto">

# 🏈 EDA - Super Bowl

Proyecto desarrollado como parte de **The Bridge Data Science Bootcamp**.  
Autor: **Alexander Ricart**  
Instructor principal: **Borja Barber**

---

## 📂 Organización de carpetas

EDA/
│
├── data/
│ ├── halftime_musician.csv
│ ├── super_bowl_ratings.csv
│ └── super_bowls.csv
│
├── img/
│ └── introduccion.jpg
│
├── notebooks/
│ └── Memoria.ipynb
│
└── presentation/
└── Presentación EDA.pdf

yaml
Copiar código

- **data/** → Conjunto de datasets utilizados para el análisis.  
- **img/** → Recursos visuales del proyecto, incluyendo la imagen de cabecera.  
- **notebooks/** → Notebook principal (`Memoria.ipynb`) con el análisis exploratorio.  
- **presentation/** → Presentación resumen del proyecto en PDF.

---

## 🧠 Descripción del proyecto

Este proyecto consiste en un **análisis exploratorio de datos (EDA)** centrado en la evolución de la **Super Bowl**, uno de los eventos deportivos más importantes del mundo.  
El objetivo principal es comprender la relación entre:

- Los niveles de **audiencia**.  
- El **precio de los anuncios publicitarios** durante la retransmisión.  
- Los **artistas del Halftime Show** y su impacto mediático.  

El trabajo analiza cómo estos factores se correlacionan entre sí y cómo han evolucionado a lo largo del tiempo.

---

## 📊 Dataset

Se utilizan tres datasets en formato `.csv`:

1. **`super_bowls.csv`** → Información general por año: equipos, puntuaciones, ciudad, estadio y asistencia.  
2. **`super_bowl_ratings.csv`** → Datos de audiencia: espectadores, rating y porcentaje de share televisivo.  
3. **`halftime_musician.csv`** → Artistas que participaron en el Halftime Show, año y cantidad.

> Los datos permiten analizar de forma conjunta la relación entre la audiencia, los artistas invitados y el coste publicitario.

---

## 🧩 Requisitos

Requiere **Python 3.x** y las siguientes librerías:

```bash
pandas
numpy
matplotlib
seaborn
jupyter
Opcionalmente:

bash
Copiar código
scipy
plotly
Instalación rápida:

bash
Copiar código
pip install pandas numpy matplotlib seaborn jupyter
📔 Estructura del Notebook (Memoria)
El Notebook Memoria.ipynb se organiza en los siguientes apartados principales:

1️⃣ Introducción y carga de datos
Importación de librerías.

Lectura y limpieza de los tres datasets.

2️⃣ Hipótesis
H1: El aumento del precio de los anuncios depende de la audiencia.

H2: El número de artistas no influye tanto como su caché.

H3: El caché del artista del Halftime Show afecta directamente al precio de los anuncios.
(Hipótesis presentadas también en la diapositiva 3 de la presentación
Presentación EDA

.)

3️⃣ Medios de emisión
Comparación entre cadenas (CBS, NBC, FOX, ABC).

Identificación del año con mayor audiencia: 2015
Presentación EDA

.

4️⃣ Audiencia y asistencia
Análisis de la intensidad del partido según la diferencia de puntos.

Ciudades destacadas: Arlington (Texas) y Pasadena (California)
Presentación EDA

.

5️⃣ Halftime Show
Relación entre el número y caché de los artistas con la audiencia.

Caso clave: 1993 – Michael Jackson, con un aumento de 11 millones de espectadores
Presentación EDA

.

6️⃣ Publicidad y costes
Evolución del precio de un anuncio de 30 segundos.

Correlación positiva con la audiencia (Pearson ≈ 0.76)
Presentación EDA

.

7️⃣ Revisión de hipótesis y conclusiones
Se confirma la correlación entre audiencia y coste publicitario.

Se rechaza la relación directa entre número de artistas y audiencia.

Se sugiere mayor relevancia del caché individual de los intérpretes.

📈 Resultados clave
📅 Año con mayor audiencia: 2015.

💰 Crecimiento exponencial del coste publicitario a lo largo de las décadas.

🎤 Mayor impacto del caché de los artistas sobre la audiencia.

🏟️ Texas y California destacan como los estados con mayor asistencia promedio.

🚀 Futuras líneas de investigación
Incluir datos del caché real de los artistas del Halftime Show.

Analizar el impacto de redes sociales y plataformas digitales en la audiencia.

Modelar predicciones de audiencia utilizando Machine Learning.

🎓 Créditos
Proyecto realizado por Alexander Ricart
Para The Bridge Data Science Bootcamp
Instructor: Borja Barber

