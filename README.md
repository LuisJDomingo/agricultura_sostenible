# Proyecto de Automatización de Huerta con Machine Learning

## Descripción

Este proyecto tiene como objetivo automatizar las tareas de una pequeña huerta utilizando sensores y algoritmos de machine learning. El sistema monitorea las condiciones del suelo y del clima, controla el riego automático y predice el rendimiento de los cultivos para optimizar el manejo de la huerta.

## Componentes

- **Sensores**: Humedad del suelo, temperatura y humedad ambiental, luminosidad, pluviómetro, pH del suelo.
- **Sistema de Riego Automático**: Válvulas de riego electrónicas y bomba de agua.
- **Estación Meteorológica**: Recolecta datos climáticos en tiempo real.
- **Plataforma de Datos**: Raspberry Pi para centralizar los datos y ejecutar modelos de machine learning.
- **Modelos de Machine Learning**: Predicción de necesidades de riego y rendimiento de cultivos.
- **Interfaz de Usuario**: Dashboard para monitorear y controlar el sistema.

## Instalación y Configuración

### Hardware

1. Conectar los sensores a la Raspberry Pi.
2. Instalar válvulas de riego electrónicas y bomba de agua.
3. Configurar la estación meteorológica.

### Software

1. Clonar el repositorio:
    ```bash
    git clone https://github.com/usuario/proyecto-huerta-automatizada.git
    cd proyecto-huerta-automatizada
    ```

2. Instalar dependencias:
    ```bash
    pip install -r requirements.txt
    ```

3. Configurar la base de datos:
    ```bash
    python setup_database.py
    ```

4. Ejecutar la aplicación:
    ```bash
    python app.py
    ```

## Uso

### Dashboard

El dashboard permite monitorear las condiciones de la huerta en tiempo real y controlar el riego manualmente si es necesario. También se pueden ver las predicciones de los modelos de machine learning y recibir alertas por SMS o correo electrónico.

### Notificaciones

Configura las notificaciones para recibir alertas en caso de condiciones críticas como baja humedad del suelo, alta temperatura, o fallos en el sistema de riego.

## Modelos de Machine Learning

### Predicción de Necesidades de Riego

Este modelo utiliza datos históricos y en tiempo real de los sensores para predecir cuándo es necesario regar las plantas.

### Predicción de Rendimiento de Cultivos

Este modelo predice el rendimiento de los cultivos basado en las condiciones del suelo y del clima.

## Contribuciones

Si deseas contribuir a este proyecto, por favor crea un fork del repositorio y abre un pull request con tus cambios.

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

