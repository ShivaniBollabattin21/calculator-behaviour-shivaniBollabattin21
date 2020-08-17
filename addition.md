
# Addition

Scenario: Addition of two postive numbers .  
  Given: The Calculator is ON .
  When:  The user enters two numbers and gives the '+' operator .
  Then:  The sum of two numbers is displayed .

Scenario: Addition of two negative numbers .  
  Given: The Calculator is ON .  
  When: The user enters two negative numbers and gives the + operator .  
  Then: The sum is displayed with a negative sign .
  
Scenario: when user enters multiple operators .  
  Given: The Calculator is ON .
  When: The user gives multiple operator .
  Then: An error message is displayed to user and
        user is made to perform the operation again .
  
Scenario: The input is in wrong format (6+*) .
  Given: The Calculator is ON .
  When: The user gives input in wrong format like a single operand
        and multiple operators, single operand and single operator .
  Then: An error message is displayed to user.
        User is asked to give the again .
  
Scenario: Adding numbers where result goes out of range .
  Given: The Calculator is ON .
  When: The user gives two operands and an operator and
        the result exceeds the display range .
  Then: An error message is displayed to user that result has exceeded and
        is asked to enter smaller numbers .
