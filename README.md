# RC2-python
==========

RC2 (also known as ARC2) encryption algorithm in pure python. ECB and CBC modes are supported.

## Usage
```python
from rc2 import * 

rc2_ctx = RC2(bytearray('encryptionkey', 'ascii'))
msg = bytearray('Message for encryption', 'ascii')
encrypted = rc2_ctx.encrypt(msg, MODE_ECB)

```
## Requirements

Python 3.2 or above.

(c) 2013, 0xEBFE
