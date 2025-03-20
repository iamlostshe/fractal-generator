# Генератор-фракталов | Fractal-generator

Проект реализован только лишь ради интереса.

Если получаются одинаковые изображения -> попробуй поменять содержание папки images. Даже небольшие изменения оказывают большое влияние на конечный результат.

## Кау установить?

1. Клонируем репозиторий и переходим в папку с проектом:

```bash
git clone https://github.com/Microvolna/fractal-generator
cd fractal-generator
```

2. Устанавливаем зависимости и запускаем проект:

<details>
    <summary>Через uv (рекомендуется)</summary>

Устанавливаем `uv` (если еще не установлен):

Linux:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Windows:

```bash
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Запускаем:

```bash
uv run bot.py
```
</details>


<details>
    <summary>Через requirements.txt</summary>

``` sh
pip install -r requirements.txt
```

или

``` sh
python -m pip install -r requirements.txt
```

3. Запускаем main.py

``` sh
python main.py
```
</details>

## Структура проекта

```
├── requirements.txt - необходимые зависимости
├── data.json        - служебный файл (мой проект по сортировке проектов)
├── fractal.png      - сгенерированный в ходе работы программы файл
├── main.py          - основной скрипт
├── README.md        - тот файл, который ты читаешь (описание проекта)
└── images           - папка в которой лежат изображения для обучения модели
    └── img.png      - пример изображения
```