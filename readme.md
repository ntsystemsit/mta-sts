
The `mta-sts.txt` file is served from the following well-known endpoint: `https://mta-sts.onprem.wtf/.well-known/mta-sts.txt`

```
_mta-sts.onprem.wtf. 3600 IN  TXT v=STSv1; id=20220204000000Z;
```

```
_smtp._tls.onprem.wtf. 3600 IN  TXT TLSRPTv1;rua=mailto:reports@onprem.wtf
```
