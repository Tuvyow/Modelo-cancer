---

## **Optimización de Random Forest con RandomizedSearchCV**

### **Descripción**
Este repositorio contiene un cuaderno de trabajo en Python que implementa un modelo de clasificación utilizando `RandomForestClassifier`. El objetivo principal es optimizar los hiperparámetros del modelo mediante `RandomizedSearchCV`. El proyecto incluye una evaluación detallada del modelo con validación cruzada y análisis de los resultados.

### **Contenido**
1. **Cuaderno principal (`random_forest_optimization.ipynb`):**
   - Implementación del modelo Random Forest.
   - Optimización de hiperparámetros con RandomizedSearchCV.
   - Evaluación del modelo utilizando validación cruzada.
   - Análisis de los resultados obtenidos.

2. **Archivo README.md:** 
   - Explicación del propósito del proyecto, los pasos realizados y los resultados obtenidos.

3. **Licencia MIT:**  
   - Licencia que permite el uso, modificación y distribución del contenido con atribución.

4. **Resultados:** 
   - Los parámetros óptimos y la precisión del modelo se documentan en el cuaderno y en el README.

### **Datos utilizados**
El modelo se entrenó y evaluó con datos de clasificación ficticios, que incluyen variables como:
- **Características**: Variables explicativas del conjunto de datos.
- **Etiqueta de clase**: Variable objetivo.

Se utilizó un conjunto de datos dividido en entrenamiento y prueba (80%-20%) para garantizar una evaluación justa del modelo.

### **Resultados obtenidos**
- **Parámetros óptimos**: Se encontraron los mejores valores para hiperparámetros como `n_estimators`, `max_depth`, `max_leaf_nodes`, `min_samples_split`, y `min_samples_leaf`.
- **Precisión promedio**: El modelo optimizado alcanzó una precisión promedio de validación cruzada superior al 95%.

### **Requisitos**
- Python 3.8 o superior.
- Bibliotecas: `scikit-learn`, `pandas`, `numpy`, entre otras.

### **Cómo usar este repositorio**
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Tuvyow/Modelo-cancer.git
   ```
2. Instalar los requisitos:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecutar el cuaderno en Jupyter Notebook o cualquier entorno compatible.

### **Licencia**
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---
