## HTTP/3 test servers

URLs to HTTP/3 test servers (usually) available.

| URL | Alt-Svc | Implemenation |
|-----|---------|---------------|
| [quic.aiortc.org](https://quic.aiortc.org/) [pgjones.dev](https://pgjones.dev) |      yes | [aioquic](https://github.com/aiortc/aioquic) |
| [cloudflare-quic.com](https://cloudflare-quic.com/) [quic.tech](https://quic.tech:8443/) | yes | [Cloudflare Quiche](https://github.com/cloudflare/quiche) |
| [facebook.com](https://facebook.com/) [fb.mvfst.net](https://fb.mvfst.net:4433/) | no | [mvfst](https://github.com/facebookincubator/mvfst) |
| [quic.rocks](https://quic.rocks:4433/) |            yes | [Google quiche](https://quiche.googlesource.com/quiche/) |
| [f5quic.com](https://f5quic.com:4433/) |             no | F5            |
| [www.litespeedtech.com](https://www.litespeedtech.com) |       yes | [lsquic](https://github.com/litespeedtech/lsquic)        |
| [nghttp2.org](https://nghttp2.org:4433/) |            no | [ngtcp2](https://github.com/ngtcp2/ngtcp2)        |
| [test.privateoctopus.com](https://test.privateoctopus.com:4433/) |no | [picoquic](https://github.com/private-octopus/picoquic)      |
| [www.dnshome.de](https://www.dnshome.de/) | yes | [nginx/1.26.1 with OpenSSL 1.1.1w](http://nginx.org/en/docs/quic.html) |
| [h2o.examp1e.net](https://h2o.examp1e.net) |         yes | h2o/quicly    |
| [quic.westus.cloudapp.azure.com](https://quic.westus.cloudapp.azure.com) |yes| msquic       |
| [docs.trafficserver.apache.org](https://docs.trafficserver.apache.org/en/latest/) | yes | Apache Traffic Server


Submit [updates as PRs](https://github.com/bagder/HTTP3-test/pulls)
