# siemenslogo

Library for connecting to siemens logo over modbus TCP.



## Usage 

1, install `pip install siemenslogo`

```python

from siemenslogo import Unit

logo = Unit(host="192.168.77.155", port=502, unit=1)
inputs = logo.get_inputs_state()

```

