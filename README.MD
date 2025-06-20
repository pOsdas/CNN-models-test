# Instance Segmentation with CNN ai

Детекция и сегментация объектов на изображениях с использованием CNN моделей.

## Список проверенных моделей
- yolov5s
- yolov8s
- yolov9s
- yolov10s
- yolo11s
- detectron2

## Библиотеки

- [ultralytics](https://github.com/ultralytics/ultralytics)
- opencv-python
- detectron
- torch
- tensorflow
- matplotlib
- pandas

## Структура проекта

```
├── models/             # Директория с тестируемыми моделями
├── annotations/        # Аннотации COCO
├── coco_eval/          # Предсказанные аннотации для оценки COCO
├── val2017/            # 5000 изображений для тестирования модели
├── notebooks/          # Директория с colab ноутбуками          
├── main.py             # Основной скрипт для выполнения детекции и сегментации
├── test_data/          # Директория с входными изображениями (пример) / Теперь используется coco датасет
├── output/             # Директория для сохранения аннотированных изображений / Теперь используется coco датасет
├── coco.yaml           # Файл с важной онформацией для coco датасета
└── README.md           # Этот файл
```

> По понятным причинам в репозитории не хранятся: `coco_eval/`, `val2017/`, `annotations/`, `models/`

## Установка
1. Скопируйте репозиторий
```sh
git clone https://github.com/pOsdas/ai-object-vision.git
cd [ваше имя]
```
2. Создайте и активируйте свою виртуальную среду 
    ### Windows:
    ```sh
    python -m venv venv
    source venv/Scripts/activate
    ```
    ### Linux/MacOS:
    ```sh
    python -m venv venv
    source venv/bin/activate
    ```
3. Установить зависимости:
```commandline
pip install -r requirements.txt
```

## Author
Автор: pOsdas

