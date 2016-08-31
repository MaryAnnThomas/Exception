# Exception
Exception handling in Java
In java, exception is an event that disrupts the normal flow of the program. It is an object which is thrown at runtime.

There are mainly two types of exceptions:
    1)Checked Exception
      The classes that extend Throwable class except RuntimeException and Error are known as checked exceptions e.g.IOException,SQLException etc. Checked exceptions are checked at compile-time.
   2) Unchecked Exception
      The classes that extend RuntimeException are known as unchecked exceptions e.g. ArithmeticException, NullPointerException, ArrayIndexOutOfBoundsException etc. Unchecked exceptions are not checked at compile-time rather they are checked at runtime.

The Java throw keyword is used to explicitly throw an exception.We can throw either checked or uncheked exception in java by throw keyword. The throw keyword is mainly used to throw custom exception. We will see custom exceptions later.

