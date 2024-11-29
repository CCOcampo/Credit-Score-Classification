# Credit Score Classification Using Neural Networks

## Proyecto: Clasificación de Puntuaciones Crediticias a través de Redes Neuronales

Este proyecto utiliza técnicas avanzadas Deep Learning para clasificar puntuaciones crediticias en tres categorías principales: **Good**, **Standard**, y **Poor**. La finalidad es ayudar a las instituciones financieras a tomar decisiones más informadas en relación con la aprobación de préstamos, asignación de tasas de interés y segmentación de clientes.

---

## **Introducción**

La puntuación crediticia es un indicador clave del riesgo financiero, utilizado por bancos y otras instituciones para evaluar la capacidad de pago de los clientes. Este proyecto se enfoca en diseñar un modelo de Redes Neuronales Artificiales (ANN) que pueda predecir con precisión la categoría crediticia de un cliente a partir de una serie de atributos financieros.

---

## **Metodología**

El desarrollo del modelo implicó las siguientes etapas clave:

1. **Manejo de Datos**:

   - Limpieza de valores nulos y anómalos.
   - Conversión de variables categóricas en valores numéricos.
   - Normalización de variables numéricas para mejorar el rendimiento del modelo.

2. **Preparación del Dataset**:

   - Eliminación de columnas irrelevantes.
   - Balanceo del dataset utilizando técnicas como **SMOTE** para evitar sesgos.

3. **Construcción del Modelo**:

   - Diseño de un modelo ANN optimizado para capturar relaciones complejas entre atributos financieros.
   - Entrenamiento y evaluación del modelo en términos de precisión, recall, y F1 score.

4. **Validación**:
   - Análisis de la matriz de confusión y métricas clave para garantizar la efectividad del modelo.

---

## **Aplicaciones Industriales**

El modelo tiene aplicaciones prácticas en el sector financiero, tales como:

- **Aprobación de Préstamos**:
  Identificar clientes con bajo riesgo crediticio para optimizar el proceso de aprobación.
- **Determinación de Tasas de Interés**:
  Asignar tasas de interés favorables a clientes con puntuaciones altas.
- **Gestión de Riesgos**:
  Reducir riesgos financieros mediante la segmentación precisa de clientes y evaluación de su comportamiento financiero.

---

## **Ventajas del Proyecto**

- **Precisión**: Las redes neuronales son ideales para detectar patrones complejos en datos financieros.
- **Escalabilidad**: El modelo puede ser adaptado a datasets más grandes y diversas industrias.
- **Decisiones Informadas**: Permite a las instituciones financieras personalizar productos y reducir riesgos.

---

## **Cómo Usar Este Proyecto**

1. **Requisitos Previos**:

   - Python 3
   - Bibliotecas: TensorFlow, NumPy, pandas, Matplotlib, scikit-learn y demás que se pueden encontrar en **requirements.txt**

2. **Clonar el Repositorio**:

   ```bash
   git clone https://github.com/CCOcampo/Credit_Score_Classification.git
   cd Credit_Score_Classification
   ```

3. **Ejecución**:
   • Abre el archivo main.ipynb en Jupyter Notebook o VSCode para explorar los pasos y resultados del proyecto.
   • Configura los datasets según las instrucciones en el notebook.

## **Autor**

<div style="text-align: center;">
  <b>Cristhian Camilo Ocampo | Data Scientist | Nov 2024 </b>
    
  <br>
  Contact:
  <a href="https://www.linkedin.com/in/cristhian-camilo-ocampo-bolivar/">Linkedin</a> | 
  <a href="https://github.com/CCOcampo">GitHub</a> | 
</div>
