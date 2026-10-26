#🤖👨‍💻 PulmoAI: Chest X-Ray Classification with Deep Learning

Multi-label classifier that detects 15 thoracic pathologies from chest X-rays, with Grad-CAM visual explanations, served through a web application.

## Overview
- **Model**: DenseNet121 with a CBAM attention mechanism, trained as a multi-label classifier (15 pathologies) on the NIH Chest X-ray dataset
- **Explainability**: Grad-CAM to highlight the image regions behind each prediction
- **Application**: responsive web app (Laravel, Blade, Bootstrap, JavaScript) connected to a Flask REST API that serves the model

## Architecture
User → Laravel web app → Flask REST API → TensorFlow/Keras model → predictions (+ Grad-CAM)

## Tech stack
Python, TensorFlow, Keras, Flask, SQL, Laravel, Bootstrap, JavaScript

## Team and contributions
Team project.
