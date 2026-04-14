# Style Guide

This file defines the coding style conventions for both human and AI contributors.

## General Guidelines
- Keep functions small and single-purpose.
- All code must be strongly typed (no `dynamic` in Dart, use type hints in Python).
- Write brief documentation for complex functions.

## Flutter / Dart
- **Formatting**: Run `dart format .` before finalizing code.
- **Widgets**: Extract large widget trees into separate smaller widgets. Use `const` constructors aggressively.
- **File Naming**: Use `snake_case` for file names (e.g., `login_screen.dart`).

## Python 
- **Formatting**: Use explicit formatters like `black` or `ruff`.
- **Typing**: Use standard Python type hinting (`def get_user(user_id: int) -> User:`).
- **File Naming**: Use `snake_case` for module names.

## JSON / NoSQL Data 
- Database document keys should be `camelCase`.

## Agent Instructions
*AI Agents must output code that adheres strictly to these guidelines. Refactor code seamlessly to match this style.*
