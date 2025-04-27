## Análisis de Datos de Ganado Bovino: Tratamiento de Valores Faltantes
### 📌 Descripción del Proyecto
Este proyecto presenta un análisis completo sobre el manejo de valores faltantes en datos de producción ganadera. El notebook implementa:

* Un diagnóstico profesional de valores faltantes

* Visualizaciones avanzadas para entender patrones de missing data

* Estrategias de imputación adaptadas a cada tipo de variable

* Un framework extensible para análisis de datos incompletos

### 🛠️ Características Principales
Extensión de Pandas: Clase personalizada con 12 métodos especializados para análisis de valores faltantes

Visualizaciones interactivas:

* Matrices de missingness

* Gráficos UpSet para patrones complejos

* Comparativas antes/después de imputación

* Estrategias de imputación inteligente:

* Mediana agrupada

* Moda por categoría

* Asignación de categorías especiales

* Análisis de tipo MCAR/MAR/MNAR

### 📊 Estructura del Notebook
1. Configuración Inicial

    * Importación de librerías

    * Personalización de visualizaciones

    * Implementación de la extensión missing para DataFrames

2. Carga y Exploración de Datos

    * Dataset sintético de ganado bovino

    * Variables analizadas: Edad, Peso, Raza, Grado de marmoleo, Vacunación, Tipo de alimentación

3. Diagnóstico de Valores Faltantes

    * Estadísticas básicas de completitud

    * Análisis por variable

    * Visualización de patrones

    * Identificación de tipos (MCAR, MAR, MNAR)

4. Estrategias de Imputación

    * Técnicas específicas por tipo de variable

    * Implementación de imputaciones

5. Visualización Comparativa

    * Distribuciones antes/después

    * Completitud del dataset

6. Conclusiones y Resultados

    * Hallazgos clave

    * Impacto de las imputaciones

    * Reflexiones finales

### 🚀 Cómo Usar

1. Clona el repositorio:
```bash
git clone [URL del repositorio]
```

2. Instala las dependencias:
```bash
pip install -r requirements.txt
```
3. Ejecuta el notebook:
```bash
jupyter notebook datos_faltantes.ipynb
```
### 📋 Requisitos
* Python 3.7+

* Librerías principales:

pandas
numpy
matplotlib
seaborn
missingno
upsetplot

### 📈 Aplicaciones
Este análisis es útil para:

* Ganaderos que necesiten analizar datos de producción
* Investigadores en ciencias agrícolas
* Científicos de datos que trabajen con datos incompletos
* Estudiantes aprendiendo técnicas de imputación

### 🎯 Resultados Clave
* Reducción del 100% en valores faltantes
* Preservación de las distribuciones originales
* Estrategias documentadas para cada tipo de missing data
* Framework reusable para otros conjuntos de datos


### 🤝 Contribuciones
¡Las contribuciones son bienvenidas! Por favor abre un issue o envía un pull request.

### 📧 Contacto
Fabricio González - fgonzalezguasque@gmail.com
🔗 LinkedIn: [https://www.linkedin.com/in/fabriciogonzalezguasque/]