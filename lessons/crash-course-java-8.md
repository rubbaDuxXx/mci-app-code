# The Math Class
{: .reading}

Java defines a number of useful classes, one of them being the ``Math`` class, which provides predefined methods for mathematical operations.
You do not need to create an object of the ``Math`` class to use it. To access it, just type in ``Math.`` and the corresponding method.

## Examples

``Math.abs()`` returns the absolute value of its parameter.
````java
int a = Math.abs(10);  // 10
int b = Math.abs(-20); // 20
````

``Math.ceil()`` rounds a floating point value **up** to the nearest integer value. The rounded value is returned as a ``double``.
````java
double c = Math.ceil(7.342);  // 8.0
````

Similarly, ``Math.floor()`` rounds a floating point value **down** to the nearest integer value.
````java
double f = Math.floor(7.343);  // 7.0
````

``Math.max()`` returns the largest of its parameters.
````java
int m = Math.max(10, 20);  // 20
````

Conversely, ``Math.min()`` returns the smallest parameter.
````java
int m = Math.min(10, 20);  // 10
````

``Math.pow()`` takes two parameters and returns the first parameter raised to the power of the second parameter.
````java
double p = Math.pow(2, 3); // 8.0
````

>There are a number of other methods available in ``Math``, including:
``sqrt()`` for square root, ``sin()`` for sine, ``cos()`` for cosine, and many more.