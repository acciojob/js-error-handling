Writing programs that work when everything goes as expected is a good start. Making your programs behave properly when encountering unexpected conditions is where it really gets challenging. Proper error handling is important as it can help users to understand what went wrong. One of the important reasons to include proper error handling in your Web applications is to help you fix it for the next release and to make development faster.
 We will be constructing a smart evaluator which will test the validity of the input field. The input string(expression) should only evaluate addition, subtraction, multiplication, division of positive and negative integers. An expression can contain spaces. Any other character will be considered invalid and shall give OutOfRangeError.
 Details
 - Create two class that Extends Error class (OutOfRangeError,InvalidExprError)
 - OutOfRangeError class should take one and should have message field value <code>Expression should only consist of integers and +-/* characters and not &lt arg &gt</code>
 - InvalidExprError should have message field <code>Expression should not have an invalid combination of expression</code>
 - Above two classes should have a name field equal to their class name
 - ```evalString``` function should 
      - Throw error InvalidExprError if there is a combination of operators like ++, /+, etc.
      - Throw Syntax Error if Expression start with +,/,* operator with message <code>Expression should not start with invalid operator</code>
      - Throw Syntax Error if Expression ends with +,/,*,- operator with message <code>Expression should not end with invalid operator</code>
     - Write your code in the try-catch block given.
     - Don't alter other codes given.
