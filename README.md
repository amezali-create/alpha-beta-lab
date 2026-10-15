# Laboratorio: Minimax y Poda Alfa-Beta

## Descripción
Este proyecto implementa los algoritmos Minimax y Poda Alfa-Beta para resolver un árbol de decisión simplificado.

## Objetivo
Comparar el resultado y la eficiencia de Minimax frente a Poda Alfa-Beta en términos de nodos evaluados y ramas podadas.

## Instalación
python -m venv .venv
source .venv/Scripts/activate
pip install -r requirements.txt

## Ejecución
python -m src.main

## Pruebas y Cobertura
pytest --cov=src --cov-report=term-missing
