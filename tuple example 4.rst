.. code:: ipython3

    num=(1,3,2,4,6,5)
    print("the original tuple num is :",num)
    num2 = sorted(num)
    print("the sorted list num2 is :",num2)
    num3 = sorted(num2 , reverse = True)
    print("The sorted list num 3 is descending order using sorted is :", num3 )
    num4 = tuple(num2)
    print("The sorted tuple num4 is :", num4)
    print("The original tuple num is :", num)


.. parsed-literal::

    the original tuple num is : (1, 3, 2, 4, 6, 5)
    the sorted list num2 is : [1, 2, 3, 4, 5, 6]
    The sorted list num 3 is descending order using sorted is : [6, 5, 4, 3, 2, 1]
    The sorted tuple num4 is : (1, 2, 3, 4, 5, 6)
    The original tuple num is : (1, 3, 2, 4, 6, 5)


