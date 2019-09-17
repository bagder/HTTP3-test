# HTTP3-test
Documentation for early HTTP/3 testing (with curl and more)

## HTTP/3 test servers

URLs to HTTP/3 test servers (usually) available. Most on draft h3-23 level.

| URL | Alt-Svc | Implemenation |
|-----|---------|---------------|
| https://quic.aiortc.org::4433/ |      yes | aioquic |
| https://cloudflare-quic.com/ https://quic.tech:8433/ | yes | Quiche |
| https://facebook.com/ https://fb.mvfst.net:4433/ | no | mvfst |
| https://quic.rocks:4433/ |            yes | Google quiche |
| https://f5quic.com:4433/ |             no | F5            |
| https://www.litespeedtech.com |       yes | lsquic        |
| https://nghttp2.org:4433/ |            no | ngtcp2        |
| https://test.privateoctopus.com:4433/ |no | picoquic      |
| https://kazuhooku.com:8443 |           no | quicly        |
| https://quic.westus.cloudapp.azure.com |no| winquic       |

Submit [updates as PRs](https://github.com/bagder/HTTP3-test/pulls)

[Original source](https://github.com/NTAP/quant/blob/master/test/test_public_servers.sh#L41) - I removed non-responding ones!
