
# Subtraction

Scenario: Subtraction of two positive numbers .

  Given: The Calculator is ON .

  When:  The user enters two numbers and a '-' operator .

  Then:  The result is difference of two numbers .

Scenario: Subtraction of two negative numbers .

  Given: The Calculator is ON .

  When: The user enters two negative numbers and a '/' operator .

  Then: The result is difference of two numbers with a greater number sign .
  
Scenario: when user enters more than one operator .

  Given: The Calculator is ON .

  When: The user enters more than one operator .

  Then: The result is an error message and
        user need to perform the operation again .
  
Scenario: The input is in wrong format ( 6 - * ) .

  Given: The Calculator is ON .

  When: The user gives input in wrong format like a single operand
        and more than one operator, single operand and single operator .

  Then: The result is an error message.
        User need to enter the input parameters again .
  
Scenario: Subtraction of fractions .

  Given: The Calculator is ON .

  When:  The user enters two fractional numbers and a '/' operator .

  Then:  The result is difference of two fractional numbers in decimals .

Scenario: Subtraction of positive and negative numbers .

  Given: The Calculator is ON .

  When:  The user enters one positive number and a negative number
         along with the '-' operator .

  Then:  The result depends on following cases
         case a: if operand 1 is positive and operand 2 is negative
                 then operand 1 - operand 2 gives result as sum of
                 two operands .
         case b: if operand 1 is negative and operand 2 is positive
                 then operand 1 - operand 2 gives result as sum of
                 two operands with negative sign .

Scenario: Subtraction of more than two numbers .

  Given: The Calculator is ON .

  When:  The user enters more than two numbers and a '-' operator .
  
  Then:  The result is difference of the numbers with a positive
         or negative sign depending on the sequence of numbers  .
