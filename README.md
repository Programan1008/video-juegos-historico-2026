# 🎮 Videojuegos en la Historia — Análisis Global 1977–2024

> Proyecto de Ciencia de Datos 

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?logo=pandas)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-3D4A8F?logo=plotly)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📋 Descripción

Análisis exploratorio completo de la industria del videojuego desde 1977 hasta 2024.
El dataset contiene **3.500 registros** con información de ventas regionales, scores de crítica,
consolas, géneros, publishers y más — cubriendo desde el Atari 2600 hasta PS5 y Xbox Series X.

---

## 🗂️ Estructura del Proyecto

```
📁 video_juegos_historico_2026/
├── 📓 videos_juegos_analisis.ipynb          # Notebook principal de análisis
├── 📊 videojuegos_historicos_chile.xlsx     # Dataset completo (3.500 registros)
├── 📄 README.md                             # Este archivo
├── 📄 requirements.txt                      # Dependencias del proyecto
└── 📄 .gitignore                            # Archivos excluidos del repo
```

---

## 📊 Variables del Dataset (32 columnas)

| Columna | Descripción |
|---------|-------------|
| `ID Juego` | Identificador único |
| `Título` | Nombre del videojuego |
| `Desarrollador` | Estudio de desarrollo |
| `Publisher` / `Grupo Publisher` | Empresa publicadora |
| `Género` / `Subgénero` | Categoría del juego |
| `Consola` / `Marca Consola` / `Tipo Consola` | Plataforma |
| `Generación` | Generación de consola (2–9) |
| `Año Juego` | Año de lanzamiento |
| `Ventas NA/EU/JP/LATAM/RoW (M)` | Ventas regionales en millones |
| `Ventas Total (M)` | Ventas globales totales |
| `Score Crítico` / `Score Usuarios` | Puntuaciones Metacritic |
| `Precio Lanzamiento (USD)` | Precio original de venta |
| `Multijugador` / `Online` / `DLC Disponible` | Características del juego |
| `Premios` | Reconocimientos de la industria |

---

## 🔍 Secciones del Análisis

| # | Sección | Contenido |
|---|---------|-----------|
| 0 | ⚙️ Configuración | Imports, estilo gaming, carga del dataset |
| 1 | 🔍 EDA | Estructura, distribuciones, cobertura de datos |
| 2 | 🏭 Marcas | Nintendo vs Sony vs Microsoft vs Sega |
| 3 | 🕹️ Consolas | Timeline histórico de plataformas |
| 4 | 🎯 Géneros | Ventas y scores por categoría |
| 5 | 📅 Evolución Temporal | Series de tiempo 1977–2024 con hitos históricos |
| 6 | 🌎 Regional | NA vs EU vs JP vs LATAM — Radar chart y mapas |
| 7 | ⭐ Score vs Ventas | Correlación calidad–ventas, regresión lineal |
| 8 | 🏆 Rankings | Top 20 juegos, publishers, franquicias |
| 9 | 📊 Dashboard | Panel ejecutivo multi-gráfico |
| 10 | 💾 Exportación | CSV/JSON para Power BI, reporte HTML |

---

## 🚀 Cómo Ejecutar

### Opción A — Anaconda (recomendado)

```bash
# 1. Clonar el repositorio
git clone https://github.com/Programan1008/video-juegos-historico-2026.git
cd video_juegos_historico_2026

# 2. Crear entorno virtual
conda create -n gaming_ds python=3.11
conda activate gaming_ds

# 3. Instalar dependencias
pip install -r requirements.txt

# 4. Abrir Jupyter Lab
jupyter lab
```

### Opción B — pip estándar

```bash
git https://github.com/Programan1008/video-juegos-historico-2026.git
cd video_juegos_historico_2026
pip install -r requirements.txt
jupyter lab
```

> ⚠️ **Importante:** Ajusta la variable `FILE_PATH` en la Sección 0 del notebook
> con la ruta donde tengas guardado el archivo `.xlsx` en tu equipo.

---

## 📈 Visualizaciones Destacadas

- **Gráficos interactivos** con Plotly (scatter, área, barras)
- **Heatmap** de ventas por Género × Marca
- **Radar chart** de distribución regional por marca
- **Dashboard ejecutivo** con KPIs, barras, líneas y pie chart
- **Regresión lineal** Score Crítico vs Ventas

---

## 🛠️ Tecnologías Utilizadas

| Librería | Uso |
|----------|-----|
| `pandas` | Manipulación y análisis de datos |
| `numpy` | Cálculos numéricos |
| `matplotlib` | Visualizaciones estáticas |
| `seaborn` | Heatmaps y gráficos estadísticos |
| `plotly` | Gráficos interactivos |
| `scipy` | Análisis estadístico (correlaciones) |
| `openpyxl` | Lectura del archivo Excel |
| `ydata-profiling` | Reporte EDA automático (opcional) |

---

## 📦 Fuentes de Datos

- [VGChartz](https://www.vgchartz.com) — Ventas de videojuegos por región
- [IGDB](https://www.igdb.com) — Base de datos de videojuegos
- [Metacritic](https://www.metacritic.com) — Scores de crítica y usuarios
- Datos actualizados a **2024**

---

## 👤 Autor

**[Cristopher Jiménez Escobar]** *Analista Programador / Cientifico de Datos*
- GitHub: [Programan1008](https://github.com/Programan1008)
- LinkedIn: [linkedin.com/in/TU_PERFIL](www.linkedin.com/in/programan1008)

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT.
Los datos de ventas son de uso educativo y de investigación.
