# scapy2dict
Scapy packet to dict

Usage
-----

```python
from scapy.all import sniff
from scapy2dict import to_dict
pkt = sniff(count=1)[0]

# To dict
data = to_dict(pkt)
```
