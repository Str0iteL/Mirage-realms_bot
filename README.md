RU:
**Название репозитория:**  
Automated-Image-Clicker  

**Описание:**  
Этот проект представляет собой набор автоматизированных скриптов на Python, которые используют библиотеки `pyautogui`, `keyboard`, `ctypes`, а также `tkinter` и `pynput` для выполнения следующих задач:  

- **Распознавание изображений на экране:** Поиск заданных PNG-файлов в указанной области экрана с использованием шаблонного сопоставления.  
- **Автоматизация кликов:** Автоматический клик по найденным изображениям с выполнением дополнительных действий.  
- **Имитирование нажатий клавиш:** Выполнение заданной последовательности нажатий клавиш с регулируемыми интервалами.  
- **Работа с админскими правами:** Скрипт запрашивает права администратора для работы в защищённой среде.  
- **Отслеживание координат мыши:** Отображение текущих координат курсора в небольшом окне, всегда находящемся поверх других.  

**Применение:**  
Скрипты могут быть полезны для автоматизации задач в играх, приложениях или других программах, где требуется взаимодействие с графическим интерфейсом.  

**Основные функции:**  
1. Гибкая настройка области поиска изображений на экране.  
2. Автоматизация кликов и выполнение действий с задержкой.  
3. Бесконечный цикл с возможностью добавления своей логики.  
4. Простое GUI для отслеживания текущей позиции мыши.  

**Требования:**  
- Python 3.7+  
- Установленные библиотеки:  
  - `pyautogui`  
  - `keyboard`  
  - `tkinter` (входит в стандартную библиотеку)  
  - `pynput`  

**Как запустить:**  
1. Убедитесь, что у вас установлен Python и необходимые зависимости.  
2. Для скрипта кликов по изображениям:  
   - Укажите путь к папке с изображениями в переменной `folder_path`.  
   - Настройте область поиска и координаты кликов в переменных `region` и `click_coords`.  
   - Запустите скрипт с правами администратора.  
3. Для скрипта отслеживания координат:  
   - Просто запустите его для отображения текущей позиции мыши в реальном времени.  

**Включённые файлы:**  
В репозитории предоставлены русские и английские версии скриптов в ZIP-архиве:  
- **1_RU_main.py**: Русская версия скрипта для автоматизации кликов по изображениям.  
- **2_English_main.py**: Английская версия скрипта для автоматизации кликов по изображениям.  
- **3_RU_For_coordinates.py**: Русская версия скрипта для отслеживания координат мыши.  
- **4_English_For_coordinates.py**: Английская версия скрипта для отслеживания координат мыши.  

**Предупреждение:**  
Скрипты предназначены для учебных и автоматизационных целей. Используйте их ответственно и не нарушайте правила использования приложений или игр.  

**Лицензия:**  
MIT License  


English:
**Repository Name:**  
Automated-Image-Clicker  

**Description:**  
This project is an automated Python script leveraging the `pyautogui`, `keyboard`, and `ctypes` libraries to perform the following tasks:  

- **Image Recognition on Screen:** Search for specified PNG files within a designated screen region using template matching.  
- **Automated Clicks:** Automatically click on detected images with additional actions as required.  
- **Simulated Key Presses:** Execute a predefined sequence of key presses at configurable intervals.  
- **Administrator Privileges:** The script requests admin rights to operate in secure environments.  

**Additional Script:**  
This repository also includes another script for real-time tracking of mouse coordinates using `tkinter` and `pynput`.  
- Displays the current mouse cursor position in a small, always-on-top window.  
- Useful for determining screen regions or click coordinates for automation tasks.  

**Application:**  
The scripts are ideal for automating tasks in games, applications, or other programs that require interaction with graphical user interfaces.  

**Key Features:**  
1. Flexible configuration for searching images within a defined screen region.  
2. Automated mouse clicks and additional actions with delays.  
3. Simulated keypress functionality in an infinite loop.  
4. Simple GUI for real-time mouse position tracking.  

**Requirements:**  
- Python 3.7+  
- Installed libraries:  
  - `pyautogui`  
  - `keyboard`  
  - `tkinter` (standard library)  
  - `pynput`  

**How to Run:**  
1. Ensure Python and the required dependencies are installed.  
2. For the image clicker script:  
   - Set the path to the folder containing images in the `folder_path` variable.  
   - Configure the search region and click coordinates in the `region` and `click_coords` variables.  
   - Run the script with administrator privileges.  
3. For the mouse coordinates tracker:  
   - Run the script directly to display the current cursor position.  

**Included Files:**  
This repository provides both Russian and English versions of the scripts in a ZIP file:  
- **1_RU_main.py**: Russian version of the automated image clicker script.  
- **2_English_main.py**: English version of the automated image clicker script.  
- **3_RU_For_coordinates.py**: Russian version of the mouse coordinates tracker.  
- **4_English_For_coordinates.py**: English version of the mouse coordinates tracker.  

**Warning:**  
These scripts are intended for educational and automation purposes. Use them responsibly and do not violate application or game usage policies.  

**License:**  
MIT License  
