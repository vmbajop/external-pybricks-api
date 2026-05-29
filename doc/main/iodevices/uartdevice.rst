.. pybricks-requirements:: pybricks-iodevices

Generic UART Device
^^^^^^^^^^^^^^^^^^^

.. |uart-wired| image:: ../../main/cad/output/iodevice-rj12grey.png
   :width: 20 %

.. |uart-wireless| image:: ../../main/cad/output/iodevice-pupdevice.png
   :width: 50 %

|uart-wired| |uart-wireless|

.. autoclass:: pybricks.iodevices.UARTDevice

**Example: Read and write to a UART device**

.. literalinclude::
   ../../../examples/ev3/uart_basics/main.py
