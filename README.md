# darktrace
API token handler class for Darktrace appliances

Example:
```
from darktrace import DarkTrace

host = '192.168.1.1'
token = '00112233445566778899aabbccddeeff00112233'
private = 'ffeeddccbbaa99887766554433221100ffeeddcc'


dt = DarkTrace(host,token,private)

call = 'modelbreaches'
params = {'from':'2017-01-01','to':'2017-01-02'}

resp = dt.api_call(call,params)
```
