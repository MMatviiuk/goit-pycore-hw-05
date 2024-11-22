# goit-pycore-hw-05

## Тема 8. Домашня робота. Функціональне програмування та вбудовані модулі Python

"""
Принципи рекурсії та використання пам’яті для оптимізації алгоритмів
Використання функцій в якості аргументів.
Створення та використання кортежів для повернення кількох значень з функції.
Використання генераторів для ефективної ітерації та обробки великих об'ємів даних.
Використання функціонального підходу, такого як використання функцій в якості аргументів та застосування функцій в функціональному стилі.
Концепція декораторів та їх застосування для обробки помилок.
"""

## Завдання 1: Замикання та кешування чисел Фібоначчі
Реалізуйте функцію `caching_fibonacci()`, яка створює кеш для зберігання обчислених чисел Фібоначчі.

- **Функція `fibonacci(n)`**:
  - Використовує кеш для збереження обчислених значень.
  - Рекурсивно обчислює n-те число Фібоначчі, зберігаючи результат у кеші для повторного використання.

## Завдання 2: Генератор чисел та підсумовування
Створіть функцію `generator_numbers(text: str)`, яка аналізує текст та ідентифікує всі числа як генератор.

- **Функція `sum_profit(text: str, func: Callable)`** використовує `generator_numbers` для обчислення загальної суми чисел.

## Завдання 3 (необов'язкове): Аналіз логів
Розробіть скрипт для аналізу лог-файлів, що зчитує файли та виводить статистику за рівнями логування (INFO, ERROR, DEBUG).

- Скрипт приймає шлях до файлу логів і не обов'язковий фільтр рівня логування.
- Реалізуйте функції: `parse_log_line()`, `load_logs()`, `filter_logs_by_level()`, `count_logs_by_level()`, `display_log_counts()`.

## Завдання 4: Обробка помилок за допомогою декораторів
Додайте декоратор `input_error` для обробки помилок введення користувача в консольному боті.

- **Декоратор `input_error`** обробляє `KeyError`, `ValueError`, `IndexError`, забезпечуючи відповідні повідомлення користувачеві.

