IP of VM: 52.11.12.254
Port 2200

In ~/.ssh add the private key into into grader_key.rsa

`-----BEGIN RSA PRIVATE KEY-----
MIIEowIBAAKCAQEAw2aQ1oZPT0TrdlmMJvnWiXwyLK7ohO3WVHFi3c3taFgNnCPl
jmvjMw72LSBGnOLy23GfM4klUt6Sr+u+orV753udAET0ABtTA6nTeAA0JtfCaeIJ
JLyJcL56znmwv+ihBqNyWiMiEgf1XVD6yN3K1/0R9BxqkHZV2YW9+HmSf8u2ga8Y
kcAF9vMKDDj3z2u7/JvdcPWGw04SR0ltvuNrbwYoCKmzvMlOL2BgB/LZRaULk+GJ
182Rp7j9x6fs9iib+qASA3CAUzK0pktS8dcuqk/Vhonj6Dj+JHN8CMk65w58S/Mz
BpmfvYsczZkNWBHL052N37uGiOGavUJHxyIqpQIDAQABAoIBAF3rEnrKG5yyN6qu
59pkA2YZt9QaTdB2sKntxeNuc0nP6Nq/tjp6SL3l1xVhig8mVix7tFWE+deW+1Jr
MTnrmR5uH8xdWBolCAWevvHSxz5UPjG+Xz61ECqMo2JSw026dotGTFRexqV8BcdQ
gPnDARhHnzWB4waEmkbvLZwccvnRDWscPqviCrlfh2Tb9nfIakA7gjU5jgTQul0S
JnCzT75DhrXXoAfldom+w5AeD+faPx/iBLThuyOS9PoDJyT5x59PWJDrT2VI0nJG
MTIIAeRgOJOTZAq8c/juPH+Zy+cX9/nOUiXROsE8xKNDkhEy7wv8oJi5s7ykFdc0
SyiiSBECgYEA3/VW72nWu2IeeylT+uq2RI4Zlhd9CAdGRhXiTKtArqBMQCvBSMVG
ZUP04ri0X1UqcMTqIzi02Im3qk0XYbXmum9Wf/uBr/N5fgt9F1F4+kusppZzTzeZ
4MIXZP8UG/GMrqINE3hv9L1TnTFKxAOgu6RpI//cVRXXmFlsxsQ+eAcCgYEA31tG
wSl3Q8q+Hxaerb0XO98zGh//ov58o0iLWNZPvbzJqgWOa6+Xd7NuPfXueV8FW15A
ifdu7xovSa+d1I4r3kjRKXu6JgcKQf1loG6GBwSbFMVGiHtvPbfnFRKQQs7bLN1w
Flq9gmkwVNzEcSVUW1GqcfU+TsCjEayqvJ+Q5PMCgYEAlYssJqeElBD7i3/YLNbn
KDW+jgNXILJC0W+xcUJ06WXuJHdTE/VugRX0giOVhYbH1Q8XzLcDwweKlXPupfch
fuHzX3gga83nFSw0tgpX/sHjIkWZ746P+I2Bs5XD5rjPGJjqpFKqZ0C4gWE1rFdD
z6gD8N7bUBFKqdcklEDb+acCgYA6TkWGHyD3HXHMA8egawAprPZWF4xQLEa1CTb3
FdrzGNk7/P9UtR3BLaHVouGB5YAsfcozOdhHqno1rhZxajuhZzjSr23Eh4nx+AgT
fUaXhmhFX8otzqsXXW6BXbsy9XTZnWSpMT7PUE5BmO/e6XO/8u2fmfmN7VOkRYK8
gpr8aQKBgAdzStVyIWWXvQCK/ELL1nC1yIIZJvoH+7xGuIYYPTgtNvkYDl1wX36x
BMjMYBZD46dtr6FGtZJDT2vIElBsBw3vdVxxii/muzpKe50IIX7ls6Uj9y7MRAr1
1RaKbf9f6RKftrZd5DSgM/d5zl+A9O4DsEKVbp2BA9GqXx/xSemX
-----END RSA PRIVATE KEY-----`

ssh -i ~/.ssh/grader_key.rsa grader@52.11.12.254 -p 2200

Password for sudo is Grader1

Postgres catalog role password is Catalog1
