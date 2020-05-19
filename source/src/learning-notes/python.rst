===============
Python学习笔记
===============

常用操作
---------

日期操作
^^^^^^^^^

**获取指定时间的时间戳**

.. code-block:: python

  # python 2
  import time
  dt = '2020-12-12 06:12:12'
  time_array = time.strptime(dt, '%Y-%m-%d %H:%M:%S')
  timestamp = time.mktime(time_array)

  # python 3.3
  from datetime import datetime
  datetime(year=20120, month=12, day=12, hour=06, minute=12, second=12)
  timestamp = datetime.timestamp(dt)




