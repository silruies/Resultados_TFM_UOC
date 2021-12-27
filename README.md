# Resultados_TFM_UOC

## Factores que influyen en la afectación del ventrículo derecho en las miocardioaptías isquémicas y no isquémicas

Resultados obtenidos en el Trabajo Fin de Máster de Silvia Ruiz España para el Máster de Ciencia de Datos de la Universitat Oberta de Catalunya (UOC), presentado en enero de 2022.

### Descripción del trabajo 

En este trabajo se ha llevado a cabo un proyecto de investigación en el que se ha analizado una base de datos con diferentes parámetros cardíacos. La base de datos ha sido preprocesada y analizada mediante técnicas de *Machine Learning* con una doble finalidad: (a) obtener modelos capaces de identificar a aquellos pacientes con miocardiopatía y disfunción del ventrículo derecho; (b) determinar los parámetros cardíacos o factores clave que influyen en la afectación de dicho ventrículo. 

Se han evaluado los siguientes modelos:
* Naïve Bayes
* Support Vector Machine con kernel lineal
* Support Vector Machine con kernel radial
* k-nearest neighbors
* Random Forest
* Multilayer perceptron

Se han estudiado y comparado tres métodos diferentes de selección de características: 
* Un filtro : basado en el valor de *p*
* Un filtro: ReliefF
* Un wrapper: SVM-RFE

### Detalle de las carpetas

A continuación, se incluye una breve descripción de las carpetas del repositorio:
* **Análisis exploratorio**: imágenes correspondientes al análisis exploratorio de la base de datos. Esta carpeta contiene:

  * Imagen con la cantidad de datos faltantes que contiene cada variable (carpeta Datos_faltantes).
  * Imagen con la distribución de clases (carpeta Distribucion_clases). 
  * Imagen de ejemplo de la eliminación de datos extremos (carpeta Eliminacion_outliers_figura_ejemplo). 
  * Imágenes antes y después de la eliminación de datos extremos (carpeta Eliminacion_outliers). 
  * Imagen de ejemplo de la exploración de una variable numérica y una categórica (carpeta Exploracion_variables_figura_ejemplo).
  * Histogramas de las variables numéricas (carpeta Exploracion_variables_numericas).
  * Gráficos de barras de las variables tipo texto (Exploracion_variables_tipo_texto).
  * Matriz de correlaciones (carpeta Matriz_correlaciones).    

* **Resultados análisis**: imágenes con los resultados de los diferentes análisis. Esta carpeta contiene: 
  * Resultados obtenidos utilizando el filtro basado en el valor de *p* (carpeta Filtro_valor_p).
  * Resultados obtenidos utilizando el filtro ReliefF (carpeta Filtro_ReliefF).
  * Resultados obtenidos utilizando el wrapper (Carpeta Wrapper).
  * Imagen comparando los resultados obtenidos con los tres métodos (carpeta Comparativa_metodos_Feature_Selection)
  * Imagen mostrando la variabilidad de los resultados obtenidos (Estudio_variabilidad).





