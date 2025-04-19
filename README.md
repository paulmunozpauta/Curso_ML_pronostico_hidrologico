
# 🌊 Curso Machine Learning para pronóstico hidrológico

Este repositorio contiene **notebooks interactivos en Jupyter** para el desarrollo de modelos de *machine learning* aplicados al pronóstico hidrológico. El curso está orientado a la práctica (*hands-on*) y ha sido diseñado para ejecutarse fácilmente en **Google Colab**, sin necesidad de instalaciones locales.

---

## 📁 Estructura del proyecto

<pre>
ml-hydrological-forecasting/
├── notebooks/              # Jupyter notebooks
│   ├── example_notebook.ipynb
├── pyproject.toml          # Poetry dependency file
├── poetry.lock             # Poetry lock file (auto-generated)
├── README.md               # Project documentation
</pre>


## 🚀 Cómo ejecutar el proyecto

Este curso está diseñado para trabajar en **Google Colab**.  
Cada notebook incluye instrucciones para configurar automáticamente el entorno y descargar los paquetes necesarios.

---

## 📊 Notebooks disponibles

**1_Precipitacion_satelital.ipynb**  
   Introducción al uso de datos de precipitación satelital (IMERG y PERSIANN), incluyendo descarga, preprocesamiento y visualización.

**2_Modelado_ML.ipynb**  
   Desarrollo de modelos de *machine learning* (Random Forest, redes neuronales) para el pronóstico de caudales, incluyendo entrenamiento, ajuste de hiperparámetros y evaluación del desempeño.

---

## ⚙️ Dependencias del proyecto

El entorno está gestionado con **Poetry**, lo cual asegura coherencia en las versiones de los paquetes utilizados.

### Principales bibliotecas utilizadas:
- `scikit-learn ^1.3.0` – Algoritmos de *machine learning*  
- `numpy ^1.25.0`, `pandas ^2.0.3` – Manejo de datos numéricos y tabulares  
- `matplotlib ^3.8.0`, `seaborn ^0.12.2` – Visualización de datos  
- `xarray ^2023.6.0`, `rioxarray ^0.15.0` – Manipulación de datos geoespaciales multidimensionales  
- `geopandas ^0.14.1`, `rasterio ^1.3.9`, `shapely ^2.0.1`, `descartes ^1.1.0` – Procesamiento de datos espaciales  
- `h5py ^3.10.0`, `openpyxl ^3.1.2` – Lectura de archivos HDF5 y Excel  
- `jupyter ^1.0.0` – Entorno interactivo para notebooks

Todas las dependencias están especificadas en el archivo `pyproject.toml`.

---

## 📬 Contacto

Para consultas o soporte durante el curso:  
**Paul Muñoz** – paul.andres.munoz@gmail.com

## ⚠️ Licencia y uso del contenido

Todo el contenido de este curso, incluyendo los notebooks, presentaciones, ejercicios y materiales de apoyo, es de **autoría exclusiva de Paul Muñoz**.

Queda **prohibida la reproducción, redistribución o uso parcial o total** del material sin **autorización expresa por escrito del autor**.

Este curso ha sido desarrollado para fines formativos específicos dentro del marco de **FICEP CIVIL 2025**.

Este repositorio está licenciado bajo los términos de la siguiente licencia:

**🔒 Licencia: [Creative Commons Atribución-NoComercial-SinDerivadas 4.0 Internacional (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.es)**

Esto significa que puedes:
- Ver y usar el material con fines no comerciales

Pero **no puedes**:
- Usar este contenido con fines comerciales
- Adaptarlo o transformarlo 
- Redistribuirlo sin permiso del autor