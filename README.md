# Rostelecom
Инструменты для тестирования: PyCharm - воспроизведение автотестов и Google-таблица - описание тест-кейсов и баг-репорт.
https://docs.google.com/spreadsheets/d/1rUjdzCHt_sdq5hs19Ps16Ph58tNQMovIXIuojzBl7Ao/edit?usp=sharing – тест-кейсы и баг репорт.

Для воспроизведения автотестов необходимо установить библиотеки selenium и pytest.
Тесты запускаются кнопкой Run.

В файле tests.py присутствуют следующие тесты (более 20) на проверку сайта:
- позитивный тест для входа в аккаунт по электронной почте
- негативные тесты для входа в аккаунт по электронной почте
- позитивный тест для восстановления пароля по электронной почте
- негативные тесты для восстановления пароля по электронной почте
- открытие гипертекстового окна "Cookies"
- переход по ссылке на страницу пользовательского соглашения
- переход по ссылке о политике конфиденциальности
- переход оранжевой по ссылке на страницу пользовательского соглашения
- негативный тест на регистрацию по уже зарегистрированному адресу
- другие негативные тесты на регистрацию
- переход на сайт "ВКонтакте"
- переход на сайт "Одноклассники"
