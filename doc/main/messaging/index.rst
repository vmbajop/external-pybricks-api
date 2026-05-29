:mod:`messaging <pybricks.messaging>` -- Send and receive messages
==================================================================

.. automodule:: pybricks.messaging
    :no-members:

.. pybricks-requirements:: ble

.. autoclass:: pybricks.messaging.BLERadio
    :no-members:

    .. automethod:: pybricks.messaging.BLERadio.broadcast

    .. automethod:: pybricks.messaging.BLERadio.observe

    .. automethod:: pybricks.messaging.BLERadio.signal_strength

    .. automethod:: pybricks.messaging.BLERadio.version

BLERadio examples
------------------

Broadcasting data to other hubs
*******************************

.. literalinclude::
    ../../../examples/pup/hub_common/build/ble_broadcast_cityhub.py

Observing data from other hubs
******************************

.. literalinclude::
    ../../../examples/pup/hub_common/build/ble_observe_cityhub.py
