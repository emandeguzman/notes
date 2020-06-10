# Constructor
function __construct() {
    ...
}

# Destructor
function __destruct() {
    ...
}


# Properties


# Methods Access Modifiers for Properties and Methods
public
protected
private


# Constants

    ## Declaration
    class MyClass {
        const MYCONSTANT
    }
    
    ## Accessing
    MyClass::MYCONSTANT


# Inheritance
class <new class name> extends <parent class name> {
    ...
}

# Abstract Class and Methods
> Abstract classes and methods are when the parent class has a named method, but need its child class(es) to fill out the tasks.

abstract class MyAbstractClass {
  abstract public function abstractMethod();
}

# $this keyword
$this keyword refers to the current object, and is only available inside methods.