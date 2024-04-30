### 1. i
    3
    This is printed since the value of i is 3 after the last time it iterates over the loop as 
    the length of the prices array inputted is 3 in this case
### 2. Discounted Price

    150
    This is printed since the value of discountedPrice is 150 at the last iteration of for the loop as
    the last element prices array inputted is 300 in this case
### 3. Final Price
    150
    This is printed since the value of finalprice is 150 at the last iteration of for the loop as 
    the last element prices array inputted is 300 in this case
### 4. Array

    This function will return an array of the finalprice which in this case will be the
    following [50,100,150], this because the function successfully calculates the required prices and
    the final prices are pushed to an array called discounted.
    
    (3) [50, 100, 150]
    0:50
    1:100
    2:150
    
### 5. Reference Error
     We will get a Reference Error at line 12, this happens because i is defined as let inside the 
     for loop so its scope is just the for loop. Trying to print it outside the loop will cause an error.
### 6. Reference Error

    We will get a Reference Error at line 13, this happens because discountedPrices
    is defined as let inside the for loop so its scope is just the for loop. 
    Trying to print it outside the loop will cause an error.
### 7. Final Price

    150
    This is printed since the value of finalprice is 150 at the last iteration of for the
    loop as the last element prices array inputted is 300 in this case and finalprice is still
    in scope as that was defined outside the for loop, its scope is the entire function
### 8.
     This function will return an array of the finalprice which in this case will be the following 
     [50,100,150],this because the function successfully calculates the required prices a
     nd the final prices are pushed to an array called discounted
     Both the final price and discounted have the correct scopes, as they are defined 
     at the beggining in the function and that is why it calculates it appropriately.
    
    (3) [50, 100, 150]
    0:50
    1:100
    2:150
### 9. Multiple Errors
    

### 10. Length
    3
    This is printed since the length is defined as a constant and the intial value given to it is the value of the
    prices array, which in this case is 3. The value remains the same no matter where we print it
### 11. Discounted
    This function will return an array of the discountedPrice which in this case will be the
    following [50,100,150], this because the function successfully calculates the required prices and
    the final prices are pushed to an array called discounted. Const defines that the variable cannot be reassigned, 
    it is still mutable. Over here we are just adding elements to it not reassigning any value so it works.
    
    (3) [50, 100, 150]
    0:50
    1:100
    2:150

### 12. Data Types
    Accessing the value of the name property in the student object: student.name
    Accessing the value of the Grad Year property in the student object: student["Grad Year"]
    Calling the function for the greeting property in the student object: student.greeting()
    Accessing the name property of the object in the Favorite Teacher property in student: student['Favorite Teacher'].name
    Access index zero in the array of the courseLoad property of the student object: student.courseLoad[0]
### 13. Basic Operators & Type Conversion  (Arithmetic)
    A. 32: integers map to their exact string representation and the both are concatenated
    B. 1 : For substraction, Javascript converts a string to a number and then performs it
    C. 3: Null is treated as 0, therefore making it 3
    D. 3null : In this case since '3' is a string, null is converted to a string and concatenated with 3
    E. 4 : In this case true is treated as 1 and adding it to 3 gives 4
    F. 0 : Both, false and null is treated as 0
    G. 3undefined : In this case since '3' is a string, undefined is converted to a string and concatenated with 3
    H. NaN: undefined is NaN as a number and '3' becomes 3. Number-NaN is NaN

### 14. Basic Operators & Type Conversion  (Comparison)
    A. true : String is converted to a number and then compared
    B. false : It compares the it in lexicographic order and '2'>'12' in that
    C. true : It does not take type into account, it compares only the values
    D. false : This takes type into account as well, since the types are different (string and number) its false
    E. false : true is converted to the number 1 and then compared with 2 
    F. true : Boolean(2) would be treated as true.

### 15. Difference between the == and === operators
    == is the lose equality operator, this checks whether the "value" is equal or not. 
    It performs type coercion i.e it converts both of them to the same type and then compares it, 
    so '2' == 2 will return true
    === is the stricst equality operator, this checks both the value and type are equal or not.
    It does not perform tyope coercion so '2' === 2 will return false
    
