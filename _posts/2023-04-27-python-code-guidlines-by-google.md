---
title: Python Coding Best Practices| A Comprehensive Guide by Google
author: Jaykant
date: 2023-04-27 11:33:00 +0800
categories: [java, rest, resapi]
tags: [java]
math: true
mermaid: true
---


> key Python code guidelines from Google's Python Style Guide, Reference https://google.github.io/styleguide/pyguide.html

Python is a versatile and powerful programming language that has become increasingly popular over the years. However, as with any programming language, it's important to write Python code that is easy to read, maintain, and understand by others. That's where a style guide comes in. 

Google has created its own Python Style Guide that provides a set of best practices and guidelines for writing Python code. In this blog post, we will explore some of the key guidelines from Google's Python Style Guide, including naming conventions, indentation, line length, comments, and more. By following these guidelines, you can improve the quality and readability of your Python code, making it easier for yourself and others to work with.

- Indentation: Use 4 spaces for indentation, not tabs. This is the preferred method for Python because it is more universally supported across different editors and environments.

- Line length: Limit lines to a maximum of 79 characters. This helps keep the code easy to read and reduces the need for horizontal scrolling.

- Naming conventions: Use descriptive names for variables, functions, classes, and modules. Here are some specific conventions:

    - Use lowercase for variable names and function names. Separate words with underscores (_). For example, my_variable, my_function.

    - Use CamelCase for class names. The first letter of each word should be capitalized, without underscores. For example, MyClass.

    - Use all uppercase for constants. Separate words with underscores (_). For example, MY_CONSTANT.

    - Use a leading underscore for "internal use" variables and functions that are not intended to be used outside the module. For example, _my_internal_variable, _my_internal_function.

    - Use a trailing underscore for variable names that conflict with reserved keywords. For example, class_, import_.

    - Use descriptive names that clearly communicate the purpose and meaning of the variable, function, or class. Avoid using single-letter variable names or abbreviations that may not be immediately obvious to someone reading the code.

- Comments: Use comments to explain code that is not obvious, but avoid obvious comments. Use complete sentences and punctuation in comments. Comments should describe why the code is doing something, not what it is doing.

- Docstrings: Use docstrings to document functions, modules, and classes. Docstrings should be enclosed in triple quotes and should include a brief summary of the purpose of the function, module, or class, as well as any parameters, return values, and exceptions.

- Imports: Put each import statement on a separate line. Group imports in the following order: standard library imports, third-party library imports, and local application imports. Import statements should be at the top of the file, before any other code.

- White space: Use white space to improve readability. For example, add a space after commas and around operators. Use blank lines to separate logical sections of code.

- Error handling: Use exceptions to handle errors, not return codes or print statements. Use meaningful error messages to help diagnose and fix problems.

- Testing: Write unit tests for all code, including edge cases and error handling. Tests should be automated and run as part of a continuous integration process.

- Formatting: Use tools like black or yapf to automatically format code. This helps ensure that the code conforms to the style guide and reduces the amount of time spent on manual formatting.

I hope this helps wiht key Python code guidelines from Google's Python Style Guide.





