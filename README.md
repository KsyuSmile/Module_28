# Module_28

Объект тестирования: форма авторизации и регистрации ЛК Ростелеком - https://b2c.passport.rt.ru <br>
<br>
*Протестировать требования. Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна.*<br>
*Провести автоматизированное тестирование продукта (не менее 15 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub.*<br>
*Оформить описание обнаруженных дефектов. Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов.*<br>
*Описать используемые техники тестирования.*<br>
<br>

Во время тестирования использовались классы эквивалентности для сокращения количиства параметров при проверки формы для ввода имени и фамилии.<br>
Также была применена техника граничных значений, для проверки полей для ввода (Имя, Фамилия, Почта).<br>
На основе опыта были определены возможные ошибки (техника предугадывания ошибок).<br>
При тестировании автоматической смены таба выбора аутентификации использовалась техника состояний и переходов (для проверки соответствия заявленным требованиям).<br>
Попарное тестирование применялось для проверки пар логин и пароль (валидные-невалидные данные). <br>
Для автотестов взята структура PegeObject. В отдельном файле conftest.py прописаны все фикстуры. <br>
В корневой папке разещён файл с ручными тест-кейсами и баг-репортами. <br>
А также файл с тестовой документацией, в котором отмечены комментарии для исправления. <br>
 
<br>
УСЛОВИЯ ДЛЯ АВТОТЕСТОВ:<br>
• На ПК установлены Python3 и PyTest <br>
• Скачать Selenium WebDriver - https://chromedriver.chromium.org/downloads <br>
• Файл WebDriver разместить в корневой папке проекта <br>
• Установить библиотеки pytest и selenium
