### Лабораторна робота №14: Boolean Expressions and Conditional Statements в Python

#### Мета роботи:
Мета цієї лабораторної роботи полягає у написанні скрипта для аналізу булевих виразів і використанні умовних операторів для розв’язання різних завдань. Кожне завдання вимагає маніпуляцій з булевими умовами в різних контекстах.

#### Виконання роботи:
Структура проекту:
- `boolean_operations.py`: Містить реалізації функцій для кожного з описаних завдань.
- `README.md`: Описує структуру проекту, призначення кожного файлу, основні функції та методи з поясненням їх роботи, приклади використання і очікувані результати.

#### Опис завдання:

1. **Basic Boolean Operations**
   - Функція `check_truth(a, b, c)`: Приймає три булевих параметри і повертає результат виразу `(a and b) or c`.

2. **Logical Equivalence**
   - Функція `logical_equivalence(a, b)`: Приймає два булевих параметри і повертає `True`, якщо вони логічно еквівалентні, і `False` в іншому випадку.

3. **Exclusive Or (XOR)**
   - Функція `xor(a, b)`: Приймає два булевих аргументи і повертає `True`, якщо рівно один із аргументів є `True`.

4. **Conditional Greeting**
   - Функція `greet(flag)`: Приймає булеве значення. Якщо `True`, функція повертає `"Hello, World!"`, інакше повертає `"Goodbye, World!"`.

5. **Nested Conditions**
   - Функція `nested_condition(x, y, z)`: Приймає три цілі числа і повертає `"All same"`, якщо всі три числа однакові, `"All different"`, якщо вони всі різні, і `"Neither"` в іншому випадку.

6. **Conditional Counting**
   - Функція `count_true(lst)`: Приймає список булевих значень і повертає кількість `True` значень в списку.

7. **Boolean Parity**
   - Функція `parity(num)`: Приймає ціле число і повертає `True`, якщо кількість одиниць в його двійковому представленні парна, в іншому випадку `False`.

8. **Majority Vote**
   - Функція `majority_vote(a, b, c)`: Приймає три булеві значення і повертає `True`, якщо більше половини з них є `True`, інакше `False`.

9. **Boolean Switch**
   - Функція `switch(flag)`: Приймає булеве значення і повертає протилежність цього значення (`True` стає `False` і навпаки).

10. **Ternary Operator Simulation**
    - Функція `ternary_check(condition, result_if_true, result_if_false)`: Симулює тернарний оператор. Повертає `result_if_true`, якщо `condition` є `True`, інакше повертає `result_if_false`.

11. **Validate Combination**
    - Функція `validate(x, y, z)`: Приймає три булеві значення і повертає `True`, якщо `x` є `True`, або обидва `y` і `z` є `True`, в іншому випадку `False`.

12. **Condition Chain**
    - Функція `chain_check(a, b, c)`: Приймає три цілі числа і повертає `"Increasing"`, якщо вони знаходяться в строгому зростаючому порядку, `"Decreasing"`, якщо вони знаходяться в строгому спадаючому порядку, і `"Neither"` в іншому випадку.

13. **Boolean Filter**
    - Функція `filter_true(lst)`: Приймає список булевих значень і повертає новий список, що містить лише значення `True`.

14. **Conditional Multiplexer**
    - Функція `multiplexer(a, b, c, num)`: Приймає три булевих параметри і одне ціле число. Якщо перший булевий параметр є `True`, повертає подвоєне значення числа. Якщо другий булевий параметр є `True`, повертає потроєне значення числа. Якщо третій булевий параметр є `True`, повертає число, зменшене на п'ять. Якщо жоден з них не є `True`, повертає ціле число без змін.

#### Результати:
```python
print(check_truth(True, False, True)) # True
print(logical_equivalence(True, True)) # True
print(logical_equivalence(True, False)) # False
print(xor(True, False)) # True
print(xor(True, True)) # False
print(greet(True)) # Hello, World!
print(greet(False)) # Goodbye, World!
print(nested_condition(3, 3, 3)) # All same
print(nested_condition(3, 4, 5)) # All different
print(count_true([True, False, True, False, True])) # 3
print(parity(3)) # False (binary 11)
print(majority_vote(True, True, False)) # True
print(switch(True)) # False
print(ternary_check(True, "Yes", "No")) # Yes
print(validate(True, False, True)) # True
print(chain_check(1, 2, 3)) # Increasing
print(chain_check(3, 2, 1)) # Decreasing
print(filter_true([True, False, True, False])) # [True, True]
print(multiplexer(False, False, True, 10)) # 5
```

#### Висновки:
У цій лабораторній роботі було розглянуто і реалізовано різні функції для роботи з булевими виразами і умовними операторами в мові програмування Python. Кожна функція вирішує конкретне завдання, пов’язане з маніпуляціями булевими умовами і обробкою даних.

#### Інструкції з запуску:
Для запуску цих функцій необхідно виконати файл у середовищі Python, що підтримує умови виконання, перераховані вище. Після виконання, у консоль виведуться результати виконання кожної функції згідно з прикладами вище.
