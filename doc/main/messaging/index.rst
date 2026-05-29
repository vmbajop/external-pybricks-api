:mod:`messaging <pybricks.messaging>` -- Send and receive messages
==================================================================

.. automodule:: pybricks.messaging
    :no-members:

.. pybricks-requirements:: pup

.. autoclass:: pybricks.messaging.BLERadio
    :no-members:

    .. automethod:: pybricks.messaging.BLERadio.broadcast

    .. automethod:: pybricks.messaging.BLERadio.observe

    .. automethod:: pybricks.messaging.BLERadio.signal_strength

    .. automethod:: pybricks.messaging.BLERadio.version

.. autoclass:: pybricks.messaging.AppData
    :no-members:

    .. automethod:: pybricks.messaging.AppData.get_bytes

    .. automethod:: pybricks.messaging.AppData.write_bytes

    .. automethod:: pybricks.messaging.AppData.configure

    .. automethod:: pybricks.messaging.AppData.close

BLERadio examples
------------------

Broadcasting data to other hubs
*******************************

.. literalinclude::
    ../../../examples/pup/ble_radio/ble_broadcast.py

Observing data from other hubs
******************************

.. literalinclude::
    ../../../examples/pup/ble_radio/ble_observe.py
