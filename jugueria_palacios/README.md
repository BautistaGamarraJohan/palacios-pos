# 🍊 Juguería Palacios — Sistema POS

## Requisitos
- Python 3.8+
- pip

## Instalación

```bash
pip install flask openpyxl
```

## Ejecutar

```bash
cd jugueria_palacios
python app.py
```

Luego abre en tu navegador: **http://localhost:5000**

## Funciones
- ✅ Registro de pedidos con personalización (helado, sin helar, al tiempo, pulpa, azúcar, espuma)
- ✅ Menú completo: Jugos, Batidos, Extractos, Zumos, Combinaciones, Ensaladas, Comida, Bebidas calientes
- ✅ Pago: Efectivo, Yape, Tarjeta, Plin
- ✅ Base de datos SQLite (archivo palacios.db)
- ✅ Reportes semanales y mensuales en Excel (3 hojas: Resumen, Por día, Detalle)

## Estructura
```
jugueria_palacios/
├── app.py              ← Backend Flask
├── palacios.db         ← Base de datos (se crea automáticamente)
├── templates/
│   └── index.html      ← Frontend
└── README.md
```
