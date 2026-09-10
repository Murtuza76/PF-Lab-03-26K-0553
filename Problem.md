# Display student information using different data types.

### Pseudocode
```
START
DEFINE INTEGER rollnumber = 0553
DEFINE STRING name = "Albert"
DEFINE CHARACTER grade = 'B'
DEFINE FLOAT gpa = 3.3

    PRINT "=== Student Information ==="
    PRINT "Roll Number:", rollnumber
    PRINT "Name:", name
    PRINT "Grade:", grade
    PRINT "GPA:", gpa
END
```

# Read and display a character using getchar() and putchar().

### Pseudocode
```
START
DEFINE CHARACTER ch
PRINT "Enter a single character"
READ ch USING getchar()
PRINT ch USING putchar()
END
```

# Display a floating-point value using different precision settings.

### Pseudocode
```
START
DEFINE FLOAT value = 3.14267
PRINT "Default Precision Value: ", value
PRINT "1 Decimal Place: ", FORMAT(value, 1_DECIMAL)
PRINT "2 Decimal Places: ", FORMAT(value, 2_DECIMALS)
PRINT "3 Decimal Places: ", FORMAT(value, 3_DECIMALS)
END
```
