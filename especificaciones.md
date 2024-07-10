# Especificaciones del Proyecto de Automatización de Huerta

## Hardware

### Sensores

- **Humedad del Suelo**: Sensores YL-69
- **Temperatura y Humedad Ambiental**: Sensores DHT22
- **Luminosidad**: Sensor BH1750
- **Pluviómetro**: Sensor de lluvia
- **pH del Suelo**: Sensor de pH

### Sistema de Riego

- **Válvulas Electrónicas**: Válvulas de control de flujo de agua
- **Bomba de Agua**: Bomba eléctrica para riego
- **Controlador**: Raspberry Pi para centralizar y controlar el sistema

### Estación Meteorológica

- **Componentes**: Sensores de temperatura, humedad, velocidad y dirección del viento, precipitación

## Software

### Librerías

- **NumPy**: Cálculos numéricos
- **Pandas**: Manipulación y análisis de datos
- **Scikit-learn**: Modelos de machine learning
- **Matplotlib**: Visualización de datos
- **RPi.GPIO**: Control de hardware en Raspberry Pi
- **Flask**: Framework web para el dashboard

### Base de Datos

- **SQLite** o **PostgreSQL**: Almacenamiento de datos históricos y en tiempo real

### API Meteorológica

- **OpenWeatherMap**: Recolección de datos climáticos externos

## Funcionalidades

### Recolección de Datos

- Monitoreo continuo de las condiciones del suelo y del clima.
- Almacenamiento de datos en la base de datos para análisis histórico.

### Modelos de Machine Learning

- **Predicción de Necesidades de Riego**: Modelo que utiliza datos de sensores para determinar cuándo regar.
- **Predicción de Rendimiento de Cultivos**: Modelo que predice la productividad del cultivo basado en las condiciones.

### Interfaz de Usuario

- **Dashboard**: Monitoreo en tiempo real y control manual del riego.
- **Notificaciones**: Alertas por SMS o correo electrónico en condiciones críticas.

## Pasos para la Implementación

1. **Configuración del Hardware**:
   - Instalación y configuración de sensores.
   - Instalación y configuración del sistema de riego automático.

2. **Desarrollo del Software**:
   - Recolección de datos y almacenamiento en base de datos.
   - Entrenamiento de modelos de machine learning.
   - Desarrollo del dashboard con Flask.
   - Configuración de notificaciones.

3. **Pruebas y Ajustes**:
   - Pruebas del sistema en condiciones reales.
   - Ajuste de modelos y configuraciones según sea necesario.

4. **Implementación Final**:
   - Despliegue del sistema en la huerta.
   - Monitoreo y mantenimiento continuo.

