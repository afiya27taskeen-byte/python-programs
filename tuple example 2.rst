.. code:: ipython3

    tup=('Python','C','Java','php')
    tup [3]="html"
    tup=('Python','C','Java','php')
    del tup[3]
    tup=('Python','C','Java','php')
    print(tup)
    del tup
    print(tup)


::


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    Cell In[3], line 2
          1 tup=('Python','C','Java','php')
    ----> 2 tup [3]="html"
          3 tup=('Python','C','Java','php')
          4 del tup[3]


    TypeError: 'tuple' object does not support item assignment


