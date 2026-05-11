# Carrasco_Lesly_Modelamiento_B
## Aprendizaje Supervisado para Clasificación | Dataset Wine

### 📋 Descripción
Repositorio correspondiente a la **Actividad Autónoma 1** de la Unidad 2: *Métodos de clasificación y clustering* (Tema 1: Aprendizaje supervisado).  
El proyecto aplica técnicas de clasificación supervisada (**Árbol de Decisión** y **Random Forest**) sobre el dataset *Wine* de `scikit-learn`, documentando y justificando cada decisión de preprocesamiento, modelado, selección de variables y evaluación, conforme a los criterios de la rúbrica académica.

### 🎯 Objetivo
Predecir el cultivar de vino (clase 0, 1 o 2) a partir de 13 características químicas cuantitativas, comparando modelos supervisados, identificando las variables con mayor poder predictivo y seleccionando el enfoque con mejor generalización mediante métricas de evaluación multiclase.

### 📦 Estructura del Proyecto
Apellido_Nombre_Modelamiento_Paralelo/
├── README.md
├── Informe/
│ └── Apellido_Nombre_Modelamiento_Paralelo.pdf
├── Codigo/
│ └── modelo_wine.ipynb # (o .py con todo el flujo)
└── requirements.txt
### 🛠️ Requisitos y Ejecución
1. **Entorno recomendado:** Python 3.9+
2. **Instalar dependencias:**
   ```bash
   pip install -r requirements.txt

   Ejecutar el código:
bash
jupyter notebook Codigo/modelo_wine.ipynb
# o
python Codigo/modelo_wine.py
