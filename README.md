# CUIA - Prácticas de Computación Ubicua e Inteligencia Ambiental

Este repositorio contiene material de estudio para la asignatura **Computación Ubicua e Inteligencia Ambiental (CUIA)** del Grado en Ingeniería Informática.

El contenido se basa en las prácticas y notebooks del repositorio del profesor: [ba1l0n/CUIA](https://github.com/ba1l0n/CUIA).

## Contenido

- **`quiz.py`**: Script interactivo en Python para repasar conceptos clave de la asignatura.
- **`preguntas.json`**: Base de preguntas de autoevaluación organizadas por temas.

## Temas cubiertos

Las preguntas abarcan los siguientes bloques de la asignatura:

- **OpenCV**: lectura y visualización de imágenes, espacios de color (BGR, RGB, HSV, grayscale), acceso a píxeles, dibujo, filtros y operaciones morfológicas.
- **Procesamiento de imagen**: histogramas, ecualización, detección de bordes y contornos.
- **Detección de rostros**: clasificadores en cascada de Haar, face_recognition, DNNs preentrenadas.
- **Hilos y concurrencia**: uso de threading en Python para aplicaciones de visión por computador.
- **Realidad Aumentada (RA)**: definiciones, historia, tipos de displays, marcadores, tracking, SLAM e interacción.
- **Infraestructura**: gestión de entornos virtuales (`venv`) y librerías gráficas (`pygfx`).

## Uso

Para ejecutar el cuestionario interactivo:

```bash
python quiz.py
```

El script lee `preguntas.json`, baraja las preguntas y muestra explicaciones detalladas tras cada respuesta.

## Licencia

Este material es de uso académico personal, derivado de las prácticas docentes del profesorado de CUIA.
