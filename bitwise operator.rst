.. code:: ipython3

    x=int(input("Enter the first number"))
    y=int(input("Enter the second number"))
    a1=x&y
    a2=x|y
    a3=~x
    a4=x^y
    a5=x>>2
    a6=x<<2
    print("bitwise AND=",a1)
    print("bitwise OR=",a2)
    print("bitwise NOT=",a3)
    print("bitwise XOR=",a4)
    print("bitwise Right shift=",a5)
    print("bitwise Left shift=",a6)
          
          


.. parsed-literal::

    Enter the first number 2
    Enter the second number 4


.. parsed-literal::

    bitwise AND= 0
    bitwise OR= 6
    bitwise NOT= -3
    bitwise XOR= 6
    bitwise Right shift= 0
    bitwise Left shift= 8


