# Tello Computer Vision Project

Este proyecto utiliza técnicas de visión por computadora para controlar un dron DJI Tello mediante Python.

## 📋 Descripción

El proyecto implementa un sistema de control para el dron DJI Tello que utiliza algoritmos de visión por computadora para realizar tareas autónomas como seguimiento de objetos, detección de caras, y navegación basada en visión.

## 🚀 Características

- Control básico del dron Tello (despegue, aterrizaje, movimiento)
- Procesamiento de video en tiempo real
- Detección y seguimiento de objetos
- Interfaz de usuario para control manual
- Registro de datos de vuelo y video

## 🛠️ Tecnologías Utilizadas

- Python 3.8+
- OpenCV (Computer Vision)
- DJI Tello SDK
- NumPy (procesamiento numérico)
- Matplotlib (visualización de datos)

## 📦 Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/tu-usuario/tello-computer-vision.git
cd tello-computer-vision
```

2. Instala las dependencias:
```bash
pip install -r requirements.txt
```

## 🎮 Uso

Ejecuta el script principal:
```bash
python main.py
```

Controles manuales:
- T: Despegar
- L: Aterrizar
- Flechas: Movimiento
- W/S: Subir/Bajar
- A/D: Rotar
- Q: Salir

## 📁 Estructura del Proyecto

```
tello-computer-vision/
├── main.py              # Script principal
├── tello_controller.py  # Control del dron
├── vision_processing.py # Procesamiento de visión
├── utils.py             # Utilidades varias
├── requirements.txt     # Dependencias
└── README.md           # Este archivo
```

## 🤝 Contribución

Las contribuciones son bienvenidas. Por favor:

1. Haz un fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## ⚠️ Precauciones

- Vuela el dron en un área amplia y despejada
- Mantén el dron dentro del rango visual
- Asegúrate de tener suficiente batería
- Sigue las regulaciones locales de vuelo de drones

