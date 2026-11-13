# PROYECTO_HURTO_COLOMBIA

Proyecto de minería de datos orientado a la detección de patrones de hurto en Colombia, utilizando **Python**, **PostgreSQL Neon**, **Streamlit** y **Power BI**.

## 📂 Estructura del proyecto

```
data/
│   raw/          # Datasets originales (sin modificar)
│   processed/    # Datos limpios y transformados

database/         # Scripts y configuraciones de la base de datos
notebooks/        # Jupyter notebooks exploratorios
src/              # Código fuente del pipeline ETL y modelos

dashboard/        # Aplicación Streamlit (por desarrollar)
reports/
│   figures/      # Gráficos y visualizaciones estáticas

tests/            # Tests unitarios y de integración
```

## 🛠️ Instalación

1. **Crear el entorno virtual**
   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1   # PowerShell
   # o .\.venv\Scripts\activate   # CMD
   ```

2. **Instalar dependencias** (el archivo está vacío por ahora)
   ```powershell
   pip install -r requirements.txt
   ```

## 📈 Próximos pasos

- Añadir dependencias a `requirements.txt` (p.ej. `pandas`, `sqlalchemy`, `streamlit`).
- Configurar la conexión a **Neon PostgreSQL**.
- Desarrollar notebooks exploratorios y pipelines de transformación.
- Implementar dashboards con Streamlit y visualizaciones en Power BI.

