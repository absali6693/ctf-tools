## Scripts

### Convert binary to dec

int("binary", 2)

### Convert dec to hex

hex("dec")

### Convert bin to hex

hex(int("binary", 2))

### hex to string

"hex_string".decode('hex') `remove 0x from the hex string`

To remove 0x use "hex_string"[2:]

### base32 decode
import base64
base64.b32decode("string")

### base64 decode
import base64
base64.b64decode("string")
