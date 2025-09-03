# Dispositivo de Estimulación Sensorial para Bebés Prematuros

Este repositorio contiene toda la documentación, el software y los archivos de diseño de hardware para el "Dispositivo de Estimulación Temprana para Bebés Prematuros", un proyecto desarrollado en la **Universidad Politécnica de Chiapas** en colaboración con el **Hospital de Especialidades Pediátricas**.

El sistema integra estímulos auditivos, táctiles y visuales de forma controlada para apoyar el desarrollo neurológico, motor y emocional de los bebés nacidos prematuramente, basándose en principios de neurociencia del desarrollo y el método Rood.

## 🌟 Características Principales

* **Módulo Auditivo:** Emite sonidos suaves (música clásica, voces parentales) a niveles seguros para el neonato.
* **Módulo Táctil:** Proporciona vibraciones suaves a través de almohadillas ajustables para promover respuestas neuromotoras.
* **Módulo Visual:** Utiliza luces y formas simples en movimiento en intervalos breves para apoyar el desarrollo visual.
* **Control Centralizado:** Todo el sistema es controlado por una **Raspberry Pi 4**, con una interfaz gráfica desarrollada en Python (Tkinter).
* **Diseño Físico Abierto:** Incluye los archivos de diseño `.STL` para la carcasa impresa en 3D, permitiendo su replicación.

## 📂 Contenido del Repositorio

* **/hardware**: Contiene los archivos `.STL` para la impresión 3D de la carcasa del dispositivo.
* **/software**: Incluye el script de Python (`front_3.py`) que controla la interfaz de usuario y los actuadores (GPIO de la Raspberry Pi).
* **/docs**: Documentación detallada del proyecto, incluyendo el marco teórico y la metodología.

## ⚙️ Requisitos de Software

Las librerías de Python necesarias para ejecutar la interfaz se listan en el archivo `requirements.txt`.

-   Python 3
-   Tkinter (generalmente incluido con Python)
-   Pillow (PIL)
-   RPi.GPIO
-   playsound

## 👥 Créditos

Este proyecto fue desarrollado por:
* **Desarrolladores:** Calvo Cruz Diego Andrés, Benítez Muñoz Josué.
* **Asesores:** Dr. Christian Roberto Ibáñez Nangüelú, Dr. Irving Roque López.

## 📄 Licencia

Este proyecto se distribuye bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
