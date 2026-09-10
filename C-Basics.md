# Markdown Table

## 1. Data Types
| Data Type | Description |
|-----------|-------------|
| `int` | Stores whole numbers usually with no decimal points.|
| `float` | Stores single-precision floating-point numbers or you can say numbers with decimals.|
| `double` | Stores double-precision floating-point numbers, or just decimal with 2 places.|
| `char` | Stores a single character which can either be a letter, digit, or symbol.|
| `bool` | Stores a Boolean value: `true` (1) or `false` (0).|
| `void` | Represents "no value".|

## 2. Format Specifiers
| Data Specifier | Description |
| -------------- | ----------- |
| `%d` | Whole number integer |
| `%u` | Unsigned decimal integer |
| `%o` | Unsigned octal (base 8) integer |
| `%x` | Unsigned hexadecimal integer (lowercase letters a-f) |
| `%X` | Unsigned hexadecimal integer (uppercase letters A-F) |
| `%f` | Floating-point number (decimal notation) |
| `%e` | Floating-point number in scientific (exponential) notation |
| `%c` | Single character |
| `%s` | String (sequence of characters) |
| `%ld` | Signed long integer |

## 3. Input/Output Functions
| Input/Output Functions | Description |
| ---------------------- | ----------- |
| `scanf()` | Reads input given by the user, using the format specifiers to know what kind of data to expect and stores the value accordingly |
| `printf()` | Prints the formatted output to the screen |
| `getchar()` | Reads a single character from given input |
| `putchar()` | Outputs that single character from the given input |
| `fgets()` | Reads a line of input string of text by the user until a new line is found. |
| `puts()` | Outputs a string and automatically creates a new line |

## 4. Escape Sequences

| Escape Sequence | Meaning | Example |
|------------------|---------|---------|
| `\n` | Newline — moves cursor to the next line | `printf("Hello\nWorld");` |
| `\t` | Horizontal tab — inserts a tab space | `printf("Name:\tAli");` |
| `\\` | Backslash — prints a backslash | `printf("C:\\Users");` |
| `\"` | Double quote — prints a `"` character | `printf("She said \"Hi\"");` |
| `\'` | Single quote — prints a `'` character | `printf("It\'s okay");` |
| `\0` | Null character — marks the end of a string | Used internally to terminate strings |
| `\r` | Carriage return — moves cursor to the beginning of the current line | `printf("Loading...\r");` |

## 5. Precision for Floating-Point Output

Precision controls how many digits appear after the decimal point, when printing from the the function 'printf'

**Syntax:** `%.nf` — where `n` is the number of decimal places to display.

**Examples:**
```
printf("%.2f", 3.14159);   // Output: 3.14   (2 digits after decimal)
printf("%.4f", 3.14159);   // Output: 3.1416 (4 digits after decimal, rounded)
printf("%.0f", 3.14159);   // Output: 3      (no decimal digits)
```
