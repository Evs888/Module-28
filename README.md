В корневой папке находятся файлы chromedriver.exe для запуска тестов с браузером google chrome, requirements.txt для установки необходимых для тестирования библиотек, env.py с тестовыми данными.
Папка pages содержит следующие файлы: 
pages/base.py содержит реализацию шаблона PageObject для Python.
pages/auth_locators.py локаторы страницы авторизации для работы с автотестами.
pages/elements.py содержит вспомогательный класс для определения веб-элементов на веб-страницах.

test_RT.py содержит все тесты
Запуск тестов:
Для запуска тестов необходимо установить библиотеки командой:
- pip install -r requirements.txt
- Загрузите Selenium WebDriver с https://chromedriver.chromium.org/downloads (выберите версию, совместимую с вашим браузером)
- Запуск тестов при помощи команд в консоли:

- python -m pytest -v --driver Chrome --driver-path chromedriver.exe tests/test.py
# Module-28
