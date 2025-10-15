# Awesome-HTTP3 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of HTTP/3 and QUIC-related implementations, articles, security blogs, and tools

- [Awesome-HTTP3]
  - [Articles](#articles)
    - [QUIC](#quic)
  - [Security Related](#security-related)
  - [Tools](#tools)
    - [Online Tools](#online-tools)
  - [Implementations](#implementations)
  - [Other Related Awesome Lists](#other-related-awesome-lists)
  - [Credit note](#credit-note)

## Articles

- [README | HTTP/3 explained](https://http3-explained.haxx.se/) - a collaborative effort to document the HTTP/3 and the QUIC protocols.
- [The Ultimate Guide To The HTTP/3 And QUIC Protocols | DebugBear] -(https://www.debugbear.com/blog/http3-quic-protocol-guide)
- [Why HTTP/3 is eating the world | APNIC Blog](https://blog.apnic.net/2023/09/25/why-http-3-is-eating-the-world/)
- [QUIC, a multiplexed transport over UDP](https://www.chromium.org/quic/) - Chromium
- [HTTP/3: the past, the present, and the future](https://blog.cloudflare.com/http3-the-past-present-and-future/)
- [HTTP/2 and HTTP/3 explained - AlexandreHTRB blog](https://alexandrehtrb.github.io/posts/2024/03/http2-and-http3-explained/)
- [Information on RFC 9114 » RFC Editor](https://www.rfc-editor.org/info/rfc9114) - HTTP/3 RFC

### QUIC

- [RFC 9000: QUIC: A UDP-Based Multiplexed and Secure Transport](https://www.rfc-editor.org/rfc/rfc9000)
- [RFC 9369: QUIC Version 2](https://www.rfc-editor.org/rfc/rfc9369.html) - QUIC Version 2 RFC
- [QUIC (quic)](https://datatracker.ietf.org/wg/quic/documents/) - IETF (Work Group) QUIC Documentation

## Security Related

- [A hands-on gaze on HTTP/3 security through the lens of HTTP/2 and a public dataset - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0167404822004436)
- [Security and Service Vulnerabilities with HTTP/3 | IEEE Conference Publication | IEEE Xplore](https://ieeexplore.ieee.org/document/10427406)
- [6 ways HTTP/3 benefits security (and 7 serious concerns) | CSO Online](https://www.csoonline.com/article/569541/6-ways-http-3-benefits-security-and-7-serious-concerns.html)
- [HTTP/3 connection contamination: an upcoming threat? | PortSwigger Research](https://portswigger.net/research/http-3-connection-contamination)

## Tools

- https://github.com/cyberark/quicdraw - QuicDraw is a security research tool designed for fuzzing and racing HTTP/3 servers.
- [HTTP/3 with curl](https://curl.se/docs/http3.html) - curl is a command-line tool for transferring data specified with URL syntax.
- [Wireshark • Go Deep](https://www.wireshark.org/) - The world's leading network protocol analyzer
- [Mitmproxy 11: Full HTTP/3 Support](https://www.mitmproxy.org/posts/releases/mitmproxy-11/)
- [Open sourcing h3i: a command line tool and library for low-level HTTP/3 testing and debugging](https://blog.cloudflare.com/h3i/)
- [https://caniuse.com/http3](https://caniuse.com/http3 "https://caniuse.com/http3") - browsers HTTP/3 support
- [qvis: tools and visualizations for QUIC and HTTP/3](https://qvis.quictools.info/#/files) - Visualization (tool) for QUIC/HTTP/3 traffic

```bash
curl --http3 https://yoursite.com -I
```

### Online Tools

- [https://http3check.net/](https://http3check.net/ "https://http3check.net/") -  Online HTTP/3 Support test

## Implementations

- [GitHub - aiortc/aioquic: QUIC and HTTP/3 implementation in Python](https://github.com/aiortc/aioquic)
- [GitHub - ngtcp2/nghttp3: HTTP/3 library written in C](https://github.com/ngtcp2/nghttp3)
- [GitHub - cloudflare/quiche: Savoury implementation of the QUIC transport protocol and HTTP/3](https://github.com/cloudflare/quiche)
- [Perform network operations using Cronet  |  Connectivity  |  Android Developers](https://developer.android.com/develop/connectivity/cronet) - Android (chromium network stack)
- [Http3Session and Streams — Firefox Source Docs documentation](https://firefox-source-docs.mozilla.org/networking/http/http3.html)
- [Implementations · quicwg/base-drafts Wiki · GitHub](https://github.com/quicwg/base-drafts/wiki/Implementations) - Known implementations of QUIC
- [https://github.com/httpwg/wiki/wiki/HTTP-Testing-Resources](https://github.com/httpwg/wiki/wiki/HTTP-Testing-Resources "https://github.com/httpwg/wiki/wiki/HTTP-Testing-Resources") - Testing resources for HTTP implementations

## Other Related Awesome Lists

- [GitHub - mmmarcos/awesome-quic: A curated list of awesome QUIC and HTTP/3 resources](https://github.com/mmmarcos/awesome-quic)
- [GitHub - sharat/awesome-http3](https://github.com/sharat/awesome-http3/)

---

## Credit note

This list was originally collected during a CyberArk Labs Research: Fuzzing and Racing HTTP/3: Introducing QuicDraw.
