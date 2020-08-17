
# Addition

Scenario: Addition of two positive numbers .

  Given: The Calculator is ON .

  When:  The user enters two numbers and a '+' operator .

  Then:  The result is sum of two numbers .

Scenario: Addition of two negative numbers .

  Given: The Calculator is ON .

  When: The user enters two negative numbers and a '+' operator .

  Then: The result is sum of two numbers with a negative sign .
  
Scenario: when user enters multiple operators .

  Given: The Calculator is ON .

  When: The user gives multiple operator .

  Then: The result is an error message and
        user is asked to perform the operation again .
  
Scenario: The input is in wrong format ( 6 + * ) .

  Given: The Calculator is ON .

  When: The user gives input in wrong format like a single operand
        and multiple operators, single operand and single operator .

  Then: An error message is displayed to user.
        User is asked to enter the input parameters again .
  
Scenario: Adding numbers where result goes out of range .

  Given: The Calculator is ON .

  When: The user enters two operands, an operator and
        the result exceeds the display range .
  
  Then: An error message is displayed to user that result has exceeded and
        is asked to enter smaller numbers .

Scenario: Addition of fractions .

  Given: The Calculator is ON .

  When:  The user enters two fractional numbers and a '+' operator .

  Then:  The result is sum of two fractional numbers in decimals .

Scenario: Addition of positive and negative numbers .

  Given: The Calculator is ON .

  When:  The user enters one positive number and a negative number
         along with the '+' operator .

  Then:  The result is subraction of two numbers with a greater number sign .

Scenario: Addition of more than two numbers .

  Given: The Calculator is ON .

  When:  The user enters more than two numbers and a '+' operator .
  
  Then:  The result is summation of the numbers .
