# Naming Conventions

## Folders

## Coding

Clang files and editorconfig will do most of the heavy lifting.

.clang-format, [.clang-tidy](https://github.com/godotengine/godot/blob/master/.clang-tidy), [.clangd](https://github.com/godotengine/godot/blob/master/.clangd) and .editorconfig files were taken from

[Godot](https://github.com/godotengine/godot)'s repo and modified by me

### All

- Code readability above all else

  That means curly brackets alone in their own line
  Curly brackets even when single line ifs
  Cohesive, consistent, clear, descriptive, etc naming for everything

- Line/Column length is 80 characters

  Readable from all IDEs and Text Editors (vim, vscode, jetbrains' ide, etc)
  This is the closest to "one size fits all" I could find
  Works for horizontal oriented monitors as well as vertical oriented
  Works for laptops and their small screen real-estate
  No side-scrolling even with (a sane amount) of docked windows around

- Self-documenting code may not be enough

  No need to write essays for each line of code, but some more complex classes
  and functions might need a little more information for understanding the
  code fully. Add comments where/when needed.

- Use formatters and linters provided here to aid in your code

  They'll do alot of the heavy-lifting for you but won't do everything for you.

### GDScript

#### Naming

| Type           | Convention               | Info            |
| -------------- | ------------------------ | --------------- |
| Class Names    | PascalCase               | MyClassName     |
| Node Names     | PascalCase               | MyNodeName      |
| Function Names | snake_case               | my_function     |
| Variable Names | snake_case               | my_variable     |
| Signal Names   | snake_case in past tense | door_opened     |
| Constant Names | CONSTANT_CASE            | MY_CONSTANT     |
| Enum Names     | PascalCase               | MyEnumName      |
| Enum Members   | CONSTANT_CASE            | MY_ENUM_ELEMENT |

    Virtual functions as well as private functions, variables, etc must be prepended
    with a underscore "\_"

#### Code Order

1. tool
2. class_name
3. extends
4. \# docstring

5. inner classes
6. signals
7. enums
8. constants
9. exported variables
10. public variables
11. private variables
12. public onready variables
13. private onready variables

14. optional built-in virtual \_init method
15. built-in virtual \_ready method
16. remaining built-in virtual methods
17. public methods
18. private methods
19. private signal receiver methods
20. public static methods
21. private static methods

### C/C++

Godot's Coding Standard

Microsoft style

### C\#

Godot's Coding Standard

[Roslyn style](https://github.com/dotnet/roslyn/blob/main/.editorconfig)
