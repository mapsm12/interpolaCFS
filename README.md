
# Análisis y Comparación Climática con ERA5 y CFS

## Descripción
Este proyecto contiene un análisis detallado y comparativo de datos climáticos, utilizando principalmente los conjuntos de datos de ERA5 (Reanálisis Climático de la Era 5) y CFS (Sistema de Pronóstico Climático). Se enfoca en la creación de mapas comparativos y series de tiempo para entender mejor las tendencias y variaciones en los datos climáticos.

## Características
- **Comparación de Datos Crudos y Corregidos:** Análisis de las diferencias entre datos crudos y datos corregidos en los modelos climáticos.
- **Mapas Comparativos:** Generación de mapas que comparan datos de diferentes fuentes como ERA5, CFS, y otros para una visualización más clara de las diferencias y similitudes.
- **Series de Tiempo:** Estudio de las series de tiempo para identificar tendencias y patrones en los datos climáticos.

## Requerimientos
- **Python Versión:** 3.10
- **Bibliotecas Requeridas:**
  - from PIL import Image
  - from datetime import datetime
  - from pptx import Presentation
  - from pptx.dml.color import RGBColor
  - from pptx.enum.text import PP_ALIGN
  - from pptx.util import Inches, Pt
  - import cartopy
  - import cartopy.crs as ccrs
  - import cartopy.io.shapereader
  - import locale
  - import matplotlib.dates as mdates
  - import matplotlib.pyplot as plt
  - import numpy as np
  - import pandas as pd
  - import pygrib
  - import warnings
  - import xarray as xr

## Instalación
Para instalar las bibliotecas requeridas, ejecute el siguiente comando:
```bash
pip install PIL datetime pptx pptx.dml.color pptx.enum.text pptx.util cartopy cartopy.crs cartopy.io.shapereader locale matplotlib.dates matplotlib.pyplot numpy pandas pygrib warnings xarray
```

## Uso
El cuaderno Jupyter `Interpolar.ipynb` incluido en este repositorio contiene todo el código y las visualizaciones necesarias para realizar el análisis.

