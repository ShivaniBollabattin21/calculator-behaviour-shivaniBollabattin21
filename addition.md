
# Addition

Scenario: Addition of two positive numbers .

  Given: The Calculator is ON .

  When:  The user enters two numbers and a '+' operator .

  Then:  The result is sum of two numbers .

Scenario: Addition of two negative numbers .

  Given: The Calculator is ON .

  When: The user enters two negative numbers and a '+' operator .

  Then: The result is sum of two numbers with a negative sign .
  
Scenario: when user enters more than one operator .

  Given: The Calculator is ON .

  When: The user enters more than one operator .

  Then: The result is an error message and
        user need to perform the operation again .
  
Scenario: The input is in wrong format ( 6 + * ) .

  Given: The Calculator is ON .

  When: The user gives input in wrong format like a single operand
        and more than one operator, single operand and single operator .

  Then: The result is an error message.
        User need to enter the input parameters again .
  
Scenario: Adding numbers where result goes out of range .

  Given: The Calculator is ON .

  When: The user enters two operands, an operator and
        the result exceeds the display range .
  
  Then: The result is an error message.
        User need to enter smaller numbers .

Scenario: Addition of fractions .

  Given: The Calculator is ON .

  When:  The user enters two fractional numbers and a '+' operator .

  Then:  The result is sum of two fractional numbers in decimals .

Scenario: Addition of positive and negative numbers .

  Given: The Calculator is ON .

  When:  The user enters one positive number and a negative number
         along with the '+' operator .

  Then:  The result is subtraction of two numbers with a greater number sign .

Scenario: Addition of more than two numbers .

  Given: The Calculator is ON .

  When:  The user enters more than two numbers and a '+' operator .
  
  Then:  The result is summation of the numbers .
