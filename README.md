# office2hashcat

### changing a few lines due to deprecated function since Python3.9

[initial source](https://raw.githubusercontent.com/stricture/hashstack-server-plugin-oclhashcat/master/scrapers/office2hashcat.py)

### firstError:
AttributeError: 'ElementTree' object has no attribute 'getiterator'

> change ElementTree.getiterator() to ElementTree.iter()

### secondError:
AttributeError: module 'base64' has no attribute 'decodestring'

> change base64.decodestring() to base64.decodebytes()
