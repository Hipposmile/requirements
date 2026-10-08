# Code requirements

This does not apply to HTML and CSS.

To ensure the code remains clear, readable, maintainable, high-quality, and secure, the following requirements apply:

- Typing: All variables, parameters, constants, functions, and methods must be typed.
- Naming:
- All names must accurately describe what the class represents, what the variable stores, or what the function executes
  or stores, without including unnecessary context.
- All names must be in English.
- All names must adhere to the naming conventions of the respective language (e.g., snake_case for variables,
  parameters, functions, and methods; UPPER_SNAKE_CASE for constants; and PascalCase for classes in Python; or camelCase
  for variables, parameters, constants, functions, and methods; and PascalCase for classes in Dart and JavaScript).
- Functions and methods:
- Every function and method must be as short as possible.
- Every function and method must have as few dependencies as possible.
- Every function and method must perform only one task and have no "side effects."
- Code duplication must be reduced to an absolute minimum through the use of reusable functions, classes, and methods.
- A function should generally either perform an action or return a value, but not both. Exceptions must be explicitly
  justified.
- Exceptions: The code must handle every scenario and user input without crashing. Instead, error messages should be
  displayed; if the error is caused by invalid user input, the specific nature of the error must be indicated. If the
  error originates elsewhere in the code, it must be logged so that developers can review all errors that have occurred.
- Comments: Comments should only be used where absolutely necessary. They must describe *why* the code performs an
  action, not *what* it does. In general, the code should be clear enough that comments are not required. - Tests: Every
  unit of code (function, method, class) must be testable and covered by tests that account for "happy paths," edge
  cases, and error scenarios. Test code must be written to the same quality standards as production code.
- Efficiency: Code should be designed for maximum efficiency and speed—for instance, by using constants instead of
  variables where possible and minimizing database or API calls. While such efficiency is critical for production code,
  it is of secondary importance for test code.
- Quotation marks: Single quotation marks must be used by default.
- Parameters must be—or be treated as—named parameters.

All these guidelines are based on the book *Clean Code: A Handbook of Agile Software Craftsmanship* by Robert C. Martin.
The rules outlined therein—like those listed above—must be strictly adhered to.
