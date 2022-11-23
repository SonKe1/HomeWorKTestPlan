# План автоматизации тестирования формы заявки на обучения "Тестировщик ПО".
**Цель:** Протестировать заявку на обучение.

Начальная страница входа :https://netology.ru/
Для того, чтобы найти заявку, необходимо с начальной страницы в разделе "Направления обучения" выбрать вкладку "Програмирование". В открывшемся окне выбрать раздел "Тестировщик ПО". Затем нажать кнопку записаться. Появится формула для заполнения.

## 1. Перечень автоматизируемых сценариев.
# Используем валидные тестовые данные:
**Поле "Имя":**
    * Кириллица (Артур, Ян, Алексей Некифоров);
    * Длина значения от 2 до 64 символов;
    * Допустимые спецсимволы: пробел, ё, дефис.
