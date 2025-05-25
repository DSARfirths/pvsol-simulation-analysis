# Data Analysis Project – Simulación PVSOL

## Metadatos de Simulación
| Parámetro                               | Units | Year    |
|-----------------------------------------|-------|---------|
| Radiación sobre la horizontal           | kWh/m²| 1969.1  |
| Radiación difusa sobre la horizontal    | kWh/m²| 955.62  |
| Temperatura exterior                    | °C    | 22.192  |
| …                                       | …     | …       |
| Consumo cubierto                        | kWh   | 16195   |

## Objetivo  
Transformar datos generados por PVSOL (hora a hora) en métricas diarias y perfiles horarios.

## Tecnologías  
- **Python** (pandas, Matplotlib)  
- **Jupyter Notebook**  
- **CSV** para ingestión en SPSS  

## Estructura del repositorio  
├── data/
│ └── pvsim_simulation.csv
├── screenshots/
│ ├── hist_performance_ratio.png
│ ├── serie_prod_consumo.png
│ ├── hourly_profile.png
│ └── daily_pr.png
├── analisis_spss_matplotlib.ipynb
└── README.md

## Resultados  
- **Metadatos**: unidades y valores base del año.  
- **Resumen mensual**: métricas de producción, consumo y PR.  
- **Detalle horario**: 8760 registros, métricas diarias y perfil medio por hora.  
- **Gráficos**:  
  - `hist_performance_ratio.png`  
  - `serie_prod_consumo.png`  
  - `hourly_profile.png`  
  - `daily_pr.png`  

## Instrucciones para reproducir  
1. Clona el repositorio.  
2. Abre `analisis_spss_matplotlib.ipynb` en JupyterLab.  
3. Ejecuta **Run All**.  
4. Verifica que en `screenshots/` aparezcan los 4 PNG generados.  
5. Usa `data/pvsim_simulation.csv` para SPSS o R.

## Licencia  
MIT
