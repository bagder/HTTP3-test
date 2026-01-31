## HTTP/3 test servers

URLs to HTTP/3 test servers (usually) available.

| URL | Alt-Svc | Implemenation |
|-----|---------|---------------|
| [cloudflare-quic.com](https://cloudflare-quic.com/) [quic.tech](https://quic.tech:8443/) | yes | [Cloudflare Quiche](https://github.com/cloudflare/quiche) |
| [facebook.com](https://facebook.com/) [fb.mvfst.net](https://fb.mvfst.net:4433/) | no | [mvfst](https://github.com/facebookincubator/mvfst) |
| [www.litespeedtech.com](https://www.litespeedtech.com) |       yes | [lsquic](https://github.com/litespeedtech/lsquic)        |
| [nghttp2.org](https://nghttp2.org:4433/) |            no | [ngtcp2](https://github.com/ngtcp2/ngtcp2)        |
| [test.privateoctopus.com](https://test.privateoctopus.com:4433/) |no | [picoquic](https://github.com/private-octopus/picoquic)      |
| [h2o.examp1e.net](https://h2o.examp1e.net) |         yes | h2o/quicly    |


Submit [updates as PRs](https://github.com/bagder/HTTP3-test/pulls)
