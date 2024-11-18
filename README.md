# Обнаружение объектов с помощью YOLOv4-Tiny

## 📋 Обзор
Этот проект демонстрирует, как выполнять обнаружение объектов в реальном времени с помощью модели YOLOv4-Tiny. Код обрабатывает изображение, обнаруживает объекты, указанные пользователем, и отображает аннотированное изображение в окне с изменяемым размером.

---

## 🛠️ Features
- **Интеграция YOLOv4-Tiny**: Использует легкую, но мощную модель глубокого обучения для обнаружения объектов.
- **Настраиваемое обнаружение**: Позволяет пользователям указывать, какие категории объектов следует обнаруживать.
- **Визуализация в реальном времени**: Выделение обнаруженных объектов ограничительными рамками и метками.
- **Удобный для пользователя ввод**: Интерактивно принимает пути изображения и категории объектов.

---

## 📁 Структура проекта
```
project/
│
├──── resources/
│ ├──── yolov4-tiny.cfg # Конфигурационный файл YOLOv4-Tiny
│ ├──── yolov4-tiny.weights # Предварительно обученные веса YOLOv4-Tiny
│ ├──── coco.names.txt # Список имен классов набора данных COCO
│
├──── main.py # Точка входа в проект
```

## 🚀 Начало работы

### 1️⃣ Необходимые условия
Убедитесь, что у вас установлено следующее:

- Python 3.7+
- OpenCV
- NumPy

### 2️⃣ Установка
Клонируйте этот репозиторий:
```plaintext
git clone https://gitlab.com/your-repo/object-detection-yolov4-tiny.git
cd object-detection-yolov4-tiny
```
Установите зависимости:
```plaintext
pip install -r requirements.txt
```

Загрузите весовые и конфигурационные файлы YOLOv4-Tiny, если они еще не включены.

---

## 🖼️ Использование
Запустите скрипт:
```plaintext
python main.py
```

Предоставьте исходные данные:

- **Путь к изображению**: Введите путь к изображению, которое вы хотите обработать.
- **Объекты для обнаружения**: Перечислите объекты (например, автомобиль, человек) или оставьте пустым, чтобы обнаружить все объекты.

---

## 🔧 Ключевые функции.

- **`draw_text`**.  
  Добавляет на изображение текстовые метки с контуром.

- **`Обнаружение_объектов`**  
  Обнаруживает объекты на заданном изображении с помощью YOLO и применяет не максимальное подавление для удаления перекрывающихся областей.

- **`start_image_object_detection`**  
  Выполняет полный цикл: загрузку изображения, запуск обнаружения и отображение результатов.

---

## 📂 Ресурсы.
- **YOLOv4-Tiny Model**: [YOLOv4-Tiny Documentation](https://github.com/AlexeyAB/darknet)
- **Классы датасетов COCO**: Список классов, доступных в `resources/coco.names.txt`.

---

Наслаждайтесь исследованием возможностей обнаружения объектов в реальном времени! 💻✨
