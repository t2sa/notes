#####Useful Commands
----

openssl
```shell
# check if tls 1.0/1.1/1.2 is supported
openssl s_client -connect hostname:port -tls1
openssl s_client -connect hostname:port -tls1_1
openssl s_client -connect hostname:port -tls1_2
```
