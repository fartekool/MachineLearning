# Машинное обучение

Домашние задания по курсу «Машинное обучение».

## Задания

| № | Задание | Данные | Ноутбук |
|---|---|---|---|
| 1 | Предсказание скорости пристройства животных из приютов (многоклассовая классификация: kNN, логистическая регрессия, случайный лес, градиентный бустинг, SVC; TF-IDF для текстовых описаний) | [PetFinder.my Adoption Prediction](https://www.kaggle.com/c/petfinder-adoption-prediction) | [task1/PetFinder.ipynb](task1/PetFinder.ipynb) |

## Запуск

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cd task1
jupyter notebook PetFinder.ipynb
```
