[![Build Status](https://travis-ci.org/ernado/rtc.svg)](https://travis-ci.org/ernado/rtc)
[![GoDoc](https://godoc.org/github.com/ernado/rtc?status.svg)](http://godoc.org/github.com/ernado/rtc)
[![Coverage Status](https://coveralls.io/repos/github/ernado/rtc/badge.svg?branch=master)](https://coveralls.io/github/ernado/rtc?branch=master)
[![Go Report](https://goreportcard.com/badge/github.com/ernado/rtc)](http://goreportcard.com/report/ernado/rtc)

# rtc
Package rtc implements real time communications in go using ice, stun, turn and sdp.

Currently in active development. Do not use this package at all. API will definitely break. 

Needs go 1.7 or better.

## RFCs

The package aims to implement the follwing RFCs.

rfc | status | requirement | description
----|--------|-------------|----
[WebRTC](https://tools.ietf.org/html/draft-ietf-rtcweb-overview) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | Real Time Protocols for Browser-based Applications
[SDP for SCTP/DTLS](https://tools.ietf.org/html/draft-ietf-mmusic-sctp-sdp) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | SDP Offer/Answer Procedures For SCTP over DTLS
[SDP for Data channel](https://tools.ietf.org/html/draft-ietf-rtcweb-sdp-09#section-5.2.3) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | SDP for Data channel
[Data channel](https://tools.ietf.org/html/draft-ietf-rtcweb-data-channel) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | WebRTC Data Channels
[Data channel Protocol](https://tools.ietf.org/html/draft-ietf-rtcweb-data-protocol) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | WebRTC Data Channel Establishment Protocol
[Protocol identification](https://tools.ietf.org/html/draft-ietf-rtcweb-alpn) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | Application Layer Protocol Negotiation for WebRTC
[WebRTC QoS](https://tools.ietf.org/html/draft-ietf-tsvwg-rtcweb-qos) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-SHOULD-green.svg)](https://tools.ietf.org/html/rfc2119) | DSCP Packet Markings for WebRTC QoS
[Multiplex Negotiating](https://tools.ietf.org/html/draft-ietf-mmusic-sdp-bundle-negotiation) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-SHOULD-green.svg)](https://tools.ietf.org/html/rfc2119) | Negotiating Media Multiplexing Using SDP
