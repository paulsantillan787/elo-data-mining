# Data Mining Project

## Descripción del Proyecto
Este proyecto se centra en el análisis de datos de transacciones y características de comerciantes para desarrollar un sistema de recomendación basado en machine learning. El objetivo es predecir el nivel de lealtad futura de los tarjetahabientes y mejorar la personalización de promociones.

## Estructura del Proyecto
```
data-mining
├── src
│   ├── train.csv
│   ├── test.csv
│   ├── historical_transactions.csv
│   ├── new_merchant_transactions.csv
│   └── merchants.csv
├── requirements.txt
├── README.md
└── Comprension_de_datos.ipynb
```

## Instrucciones de Configuración

### 1. Crear un entorno virtual:
- Para Windows:
```
python -m venv venv
```
- Para macOS/Linux:
```
python3 -m venv venv
```

### 2. Activar el entorno virtual:
- Para Windows:
```
venv\Scripts\activate
```
- Para macOS/Linux:
```
source venv/bin/activate
```

### 3. Instalar los paquetes requeridos:
```
pip install -r requirements.txt
``` 

## Archivos del Proyecto
- `src/train.csv`: Conjunto de entrenamiento utilizado para el entrenamiento del modelo.
- `src/test.csv`: Conjunto de prueba utilizado para la evaluación del modelo.
- `src/historical_transactions.csv`: Datos de transacciones históricas para análisis.
- `src/new_merchant_transactions.csv`: Datos de transacciones para nuevos comerciantes.
- `src/merchants.csv`: Información adicional sobre los comerciantes.
- `requirements.txt`: Lista de dependencias de Python requeridas para el proyecto.
- `Comprension_de_datos.ipynb`: Notebook para la comprensión y análisis de datos.

## Fuente
- https://www.kaggle.com/competitions/elo-merchant-category-recommendation/overview
