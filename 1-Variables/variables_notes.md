# Variables


Variables are mainly used to store data in a computer memory, and it can be retrieved to conduct multiple operations.

## How to create variables?

To create a variable simply associate variable name with the value as:
 `variable_name` = `value`

```python
salary = 10000
```

### Declaring Multiple Variable in a Line.

Multiple variables can be declared in one line.
`first_variable_name`, `second_variable_name` = `first_value`, `second_value`

## How to name a variable?

- **Use Descriptive Names**

    Choose names that clearly describe the purpose of the variable and avoid using single letters or abbreviations that are not immediately clear.

    ```python
    # Bad
    a = 5

    # Good
    count_of_students = 5
    ```
- **Follow PEP 8 Naming Conventions**

    Use lowercase letters with words separated by underscores (`snake_case`) for variable names.
    ```python
    student_count = 25
    ```
- **Avoid Using Python Reserved Keywords**

    Do not use keywords reserved by Python as variable names.
    ```python
    # Bad
    class = "Math"

    # Good
    class_name = "Math"
    ```
- **Keep It Concise but Clear**

    Aim for a balance between conciseness and clarity.
    ```python
    # Bad
    number_of_students_in_the_class = 30

    # Good
    student_count = 30
    ```
- **Use Meaningful Distinctions**

    Make sure similar variables have distinguishable names.
    ```python
    # Bad
    student1 = "John"
    student2 = "Jane"

    # Good
    first_student = "John"
    second_student = "Jane"
    ```
- **Use Plural Names for Collections**

    For variables that hold collections of items, use plural names.
    ```python
    # Bad
    student = ["John", "Jane"]

    # Good
    students = ["John", "Jane"]
    ```
- **Use a Consistent Naming Scheme**

    Stick to a naming scheme throughout your code for consistency.
    ```python
    # Bad
    total_price = 100
    totalCost = 150

    # Good
    total_price = 100
    total_cost = 150
    ```
- **Avoid Unnecessary Prefixes and Suffixes**

    Do not add unnecessary words to variable names.
    ```python
    # Bad
    the_student_list = ["John", "Jane"]

    # Good
    students = ["John", "Jane"]
    ```
- **Use Uppercase for Constants**

    If a variable is meant to be a constant, use uppercase letters with underscores.
    ```python
    MAX_SPEED = 120
    ```

These were the most common *best practices* for naming variables to help ensure that your code is easily readable and maintainable by others (and yourself in the future).

## Recourses

- [PEP 8 -- Style Guide for Python Code](https://peps.python.org/pep-0008/)
- [How to Writing Readable and Maintainable Python Code?](https://medium.com/@b.kiran1999kumar/a-guide-to-writing-readable-and-maintainable-python-code-28bb5dbb91ce)