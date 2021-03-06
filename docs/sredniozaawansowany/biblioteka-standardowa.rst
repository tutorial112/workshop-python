**********************
Biblioteka standardowa
**********************

``datetime``
============

.. code-block:: python

    import datetime

    datetime.datetime.now()
    datetime.date.today()
    datetime.datetime.now() - datetime.timedelta(hours=3)
    datetime.datetime.now().replace(tzinfo=datetime.timezone.utc)

``time``
========


``os``
======

.. code-block:: python

    import os

    os.path
    os.walk
    os.path.join
    os.path.abspath
    os.path.dirname

``sys``
=======

.. code-block:: python

    import sys

    sys.path
    sys.path.append
    sys.platform


``warnings``
============

.. code-block:: python

    import warnings

    warnings.warn('Wersja API jest już nieaktualna', PendingDeprecationWarning)

``pprint``
==========

.. code-block:: python

    from pprint import pprint

    data = [
       {'first_name': 'Baked', 'last_name': 'Beans'},
       {'first_name': 'Lovely', 'last_name': 'Spam'},
       {'first_name': 'Wonderful', 'last_name': 'Spam'}
    ]

    pprint(data)

``csv``
=======

.. code-block:: python

    import csv

    csv.DictReader()
    csv.DictWriter()

``memoize``
===========

``json``
========

.. code-block:: python

    import json

    json.loads()
    json.dumps()

``sqlite``
==========

``re``
======

.. code-block:: python

    import re

    re.search()
    re.findall()
    re.match()
    re.compile()

``httplib``
===========

``urllib``
==========

``socket``
==========

``tempfile``
============

``io``
======

.. code-block:: python

    import io

    io.StringIO

``functools``
=============

``itertools``
=============

``math``
========

.. code-block:: python

    import math

    math.sin()
    math.cos()
    math.tan()
    math.pi

``statistics``
==============

.. code-block:: python

    import statistics

    statistics.avg()
    statistics.mean()
    statistics.stdev()

``random``
==========

.. code-block:: python

    import random

    random.sample()
    random.random()

``subprocess``
==============

.. code-block:: python

    import subprocess

    subprocess.Popen()

``doctest``
===========

.. code-block:: python

    import doctest

    doctest.testmod()


Collections
===========

================  ====================================================================
Name              Description
================  ====================================================================
``namedtuple()``  factory function for creating tuple subclasses with named fields
``deque``         list-like container with fast appends and pops on either end
``ChainMap``      dict-like class for creating a single view of multiple mappings
``Counter``       dict subclass for counting hashable objects
``OrderedDict``   dict subclass that remembers the order entries were added
``defaultdict``   dict subclass that calls a factory function to supply missing values
``UserDict``      wrapper around dictionary objects for easier dict subclassing
``UserList``      wrapper around list objects for easier list subclassing
``UserString``    wrapper around string objects for easier string subclassing
================  ====================================================================
