.. _badge_self_help:

Help Yourself!
===============

In a Python interpreter
-----------------------

``dir()``

Without arguments, return the list of names in the current local scope. With an argument, attempt to return a list of valid attributes for that object.

.. code-block:: python

    >>> import datetime
    >>> dir(datetime)
    ['MAXYEAR', 'MINYEAR', '__doc__', '__file__', '__name__', '__package__', 'date', 'datetime', 'datetime_CAPI', 'time', 'timedelta', 'tzinfo']
    >>> dir(datetime.datetime)
    ['__add__', '__class__', '__delattr__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__gt__', '__hash__', '__init__', '__le__', '__lt__', '__ne__', '__new__', '__radd__', '__reduce__', '__reduce_ex__', '__repr__', '__rsub__', '__setattr__', '__sizeof__', '__str__', '__sub__', '__subclasshook__', 'astimezone', 'combine', 'ctime', 'date', 'day', 'dst', 'fromordinal', 'fromtimestamp', 'hour', 'isocalendar', 'isoformat', 'isoweekday', 'max', 'microsecond', 'min', 'minute', 'month', 'now', 'replace', 'resolution', 'second', 'strftime', 'strptime', 'time', 'timetuple', 'timetz', 'today', 'toordinal', 'tzinfo', 'tzname', 'utcfromtimestamp', 'utcnow', 'utcoffset', 'utctimetuple', 'weekday', 'year']

``help()``

``help()`` without an argument opens an interactive help environment. If the argument is a string (i.e. ``help('int')``), then the string is looked up as the name of a module, function, class, method, keyword, or documentation topic, and a help page is printed on the console. If the argument is any other kind of object (i.e. ``help(datetime)``), a help page on the object is generated.

In a UNIX environment
----------------------

``man``

``man`` is short for "manual" and prints out the manual page for a particular command (i.e. ``man grep``). It can be helpful for remembering what arguments a UNIX command takes and in which order. 
