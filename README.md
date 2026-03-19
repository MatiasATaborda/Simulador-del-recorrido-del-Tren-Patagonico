# 🚆 Tren Patagónico – Simulador en Python
### 📌 ¿De qué trata este proyecto?
Este proyecto es un simulador del recorrido del Tren Patagónico, desarrollado en Python dentro de Jupyter Notebook.  
Permite visualizar estaciones, horarios y consultar tramos específicos del viaje entre Viedma y San Carlos de Bariloche.  
### 🎯 ¿Qué puede hacer el sistema?
Ver el recorrido completo de ida  
Ver el recorrido completo de regreso  
Consultar un tramo entre dos estaciones  
Interactuar mediante entradas del usuario  
### 🛤️ ¿Cómo están organizados los datos?
Se utilizan listas con diccionarios para representar los recorridos:  
Python  
servicio_ida = [  
    {"estacion": "Viedma", "hora": "17:00"},  
    {"estacion": "San Antonio Oeste", "hora": "21:25"},  
]  
Cada registro contiene:  
📍 Estación  
⏰ Hora  
### 🖥️ ¿Cómo funciona?
El programa tiene un menú interactivo que se ejecuta en una celda del notebook:  
🚆 SISTEMA TREN PATAGÓNICO  
1️⃣ Ver recorrido ida  
2️⃣ Ver recorrido regreso  
3️⃣ Consultar tramo del viaje  
4️⃣ Salir  
El usuario ingresa opciones usando input().  
### 📓 Entorno de trabajo
Jupyter Notebook  
Python 3  
Esto permite:  
Ejecutar el código por partes  
Probar cambios rápidamente  
Visualizar resultados en tiempo real  
### ▶️ Cómo usar el proyecto
Abrir el archivo .ipynb en Jupyter Notebook  
Ejecutar las celdas en orden  
Ejecutar la celda del menú  
Interactuar con el sistema  
#### 🔍 Ejemplo de uso  
Elegir opción 3  
Escribir: ida o regreso  
Ingresar estación de origen  
Ingresar estación destino  
### 👨‍💻 Autor
Matías Alejandro Taborda
