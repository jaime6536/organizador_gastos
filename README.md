# organizador_gastos
# idea
- la idea es que tu vas poniendo lo datos de lo que compras y despues te hace una lista con el total mensual para clacular gastos y podria venir con un grafico de lineas que te  uestre como a suvido o bajado el consumo y tambien que te diga en que es lo que mas gasta y datos a nivel de todos los meses

# Funcionalidades
- registrar_gasto(categoria, monto)
- guardar_en_archivo(categoria, monto, fecha)
- gasto_total_dia(fecha)
- gasto_total_mes(mes, año)
- ver_ultimos_gastos(n)
- gasto_total_historico()
- categoria_mas_gasto()

# Instalación
1. Clona el repositorio
2. Instala Python 3.x
3. Ejecuta `python main.py`

# Uso
Al ejecutar `python main.py`, aparecerá un menú con opciones como:

1. Registrar gasto
2. Ver total del día
3. Ver total del mes
4. Ver últimos gastos
5. Ver total histórico
6. Ver categoría con mayor gasto
7. Salir

# Estructura del Proyecto

organizador_gastos/
├── main.py
├── funciones.py
├── gastos.txt       
└── README.md
