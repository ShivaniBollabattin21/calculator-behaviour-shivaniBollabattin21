
# Division

Scenario: Divide by zero .

  Given: The Calculator is ON .

  When: The user enters a number, zero and a '/' operator .

  Then: The result is an infinite value or an error message.
  
Scenario: when both operands are zero .

  Given: The Calculator is ON .

  When: The user enters both numbers as zero and  a '/' operator .

  Then: The result is an error message .
  
Scenario:  When operand 2 is not present.

  Given: The Calculator is ON .

  When: The user enters only one operand and a '/' operator .

  Then: The result is an error message,
        user need to enter the values again .
  
Scenario: Recurring decimals .

  Given: The Calculator is ON .

  When: The user enters two numbers and a '/' operator
        and result is reccuring number .
  
  Then: The result is rounded up to 4 decimals .

Scenario: Division by fractional operands .

  Given: The Calculator is ON .

  When:  The user enters two numbers
         (if one of the operand or both operands are fractional)
         a '/' operator .

  Then:  The result is either a decimal value or integer value
         if decimal, it is rounded up to 4 decimals .

Scenario: Division of multiple numbers .

  Given: The Calculator is ON .

  When:  The user enters more than two numbers and '/' operator .

  Then:  The result is either a decimal value or integer value
         if decimal, it is rounded up to 4 decimals .
