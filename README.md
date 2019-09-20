# HTTP3-test
Documentation for early HTTP/3 testing (with curl and more)

## HTTP/3 test servers

URLs to HTTP/3 test servers (usually) available. Most on draft h3-23 level.

| URL | Alt-Svc | Implemenation |
|-----|---------|---------------|
| [quic.aiortc.org](https://quic.aiortc.org:4433/) [pgjones.dev](https://pgjones.dev:4433) |      yes | aioquic |
| [cloudflare-quic.com](https://cloudflare-quic.com/) [quic.tech](https://quic.tech:8433/) | yes | Quiche |
| [facebook.com](https://facebook.com/) [fb.mvfst.net](https://fb.mvfst.net:4433/) | no | mvfst |
| [quic.rocks](https://quic.rocks:4433/) |            yes | Google quiche |
| [f5quic.com](https://f5quic.com:4433/) |             no | F5            |
| [www.litespeedtech.com](https://www.litespeedtech.com) |       yes | lsquic        |
| [nghttp2.org](https://nghttp2.org:4433/) |            no | ngtcp2        |
| [test.privateoctopus.com](https://test.privateoctopus.com:4433/) |no | picoquic      |
| [h2o.examp1e.net](https://h2o.examp1e.net) |         yes | h2o/quicly    |
| [quic.westus.cloudapp.azure.com](https://quic.westus.cloudapp.azure.com) |no| winquic       |

Submit [updates as PRs](https://github.com/bagder/HTTP3-test/pulls)

[Original source](https://github.com/NTAP/quant/blob/master/test/test_public_servers.sh#L41) - I removed non-responding ones!
