### 1. Var Declaration
- **Line 9**
  
      values added: 
      20
- **Line 13**

      final result: 
      20

### 2. Let Declaration
- **Line 9**
  
      values added: 
      20  

- **Line 13**

      Reference Error 
      We have intialized result using let inside the if statement which causes the scope of result to be only in the if statement block since this is outside that it gives us an error

### 3. Const Declaration

- **Line 9** and **Line 13**
  
      Nothing is printed on either, we get an error stating "Cannot assign to "result" because it is a constant". We get this error since result is defined as a const
      and then we are trying to change by changing its value to num1 + num2, this is not allowed as a const cannot be reassigned to another value.


                
                 
