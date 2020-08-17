
# Multiplication

Scenario: Result overflow .

  Given: The Calculator is ON .

  When:  The user enters two numbers and a '*' operator,
         and result is exceeded.

  Then:  The result is an error message that result has exceeded the range,
         user is asked to try again and enter smaller numbers .

Scenario: Zero value multiplication .

  Given: The Calculator is ON .

  When: The user enters a number, zero and a '*' operator .

  Then: The result is zero value .
  
Scenario: Multiplication by 1 .

  Given: The Calculator is ON .

  When: The user enters a number, 1 and a '*' operator .

  Then: The result is 1 .
  
Scenario: Decimal value multiplication.

  Given: The Calculator is ON .

  When: The user enters two or more decimal numbers and a '*' operator .

  Then: The result is product of numbers with precision upto 4 decimal places .
  
Scenario: Irrational value multiplication .

  Given: The Calculator is ON .

  When: The user enters two irrational numbers and a '*' .
  
  Then: The result is product of two irrational numbers
        that is either rational or irrational .

Scenario: Multiplication of two numbers .

  Given: The Calculator is ON .

  When:  The user enters two numbers and a '*' operator .

  Then:  The result is product of two numbers .

Scenario: Multiplication of rational numbers .

  Given: The Calculator is ON .

  When:  The user enters two rational numbers and '*' operator .

  Then:  The result is product of two numbers and is a rational number .

Scenario: Multiplication of decimal and integer numbers .

  Given: The Calculator is ON .

  When:  The user enters a decimal number,an integer and a '*' operator .
  
  Then:  The result is a decimal value upto 4 decimal places .

Scenario: Range of operand exceeds .

  Given: The Calculator is ON .

  When:  The user enters two numbers(operands) and gives the '*' operator,
         the operands exceed the specified range .
  
  Then:  The result is an error message and
         user is asked to try again and enter smaller numbers(operands) .

Scenario: Multiplication of more than two numbers .

  Given: The Calculator is ON .

  When:  The user enters more than two numbers and a '*' operator .
  
  Then:  The result is product of the numbers .
