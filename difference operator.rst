.. code:: ipython3

    Days1={"Mon","Tue","Wed","Sat"}
    Days2={"Thr","Fri","sat","Sun","Mon"}
    print("Days1-Days2 is :", Days1-Days2)
    print("Days2-Days1 is :", Days2-Days1)
    print("Days1-Days2 is :", Days1.difference(Days2))
    print("Days2-days1 is:", Days2.difference(Days1))


.. parsed-literal::

    Days1-Days2 is : {'Tue', 'Wed', 'Sat'}
    Days2-Days1 is : {'Sun', 'sat', 'Fri', 'Thr'}
    Days1-Days2 is : {'Tue', 'Wed', 'Sat'}
    Days2-days1 is: {'Sun', 'sat', 'Fri', 'Thr'}


