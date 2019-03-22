---
layout: post
title: The first gRPC Conf is a wrap!
published: true
permalink: blog/grpconf-wrapup
author: Luc Perkins
company: Cloud Native Computing Foundation
company-link: https://cncf.io
---

On Thursday, March 21, I had the distinct pleasure of attending [gRPConf 2019](https://events.linuxfoundation.org/events/grpconf-2019/), the very first conference exclusively devoted to gRPC. Although gRPC has been featured in countless talks at dozens and dozens of conferences, it was nice to see

In this post I'll present a heavily biased, one-sided account of the conference.

## Highlights

### Dogs

No, seriously, I mean it. And not just [Pancake](../hello-pancakes), the gRPC mascot. There were real live dogs on site for part of the conference that attendees could pet and play with. This was a major emotional boost for all involved. Here they are:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">We take this mascot business very serious. <a href="https://twitter.com/hashtag/grpconf?src=hash&amp;ref_src=twsrc%5Etfw">#grpconf</a> <a href="https://t.co/TrdioNIXxq">pic.twitter.com/TrdioNIXxq</a></p>&mdash; gRPC (@grpcio) <a href="https://twitter.com/grpcio/status/1108821926116384768?ref_src=twsrc%5Etfw">March 21, 2019</a></blockquote>

### Seeing gRPC in large deployments

I've used gRPC in some smaller, personal projects (such as my [Colossus](https://github.com/lucperkins/colossus) project). That's cool I guess, but let's face it: gRPC really *thrives* in the large-scale deployments that it was originally built for. For me, the content highlight of the conference 

## General impressions

Since joining the CNCF many months ago, I've had the opportunity to attend many wonderful conferences, including one other first-ever conference ([EnvoyCon](https://envoyconna18.sched.com/) for [Envoy](https://envoyproxy.io) back in December). Service meshes are still very new 

The gRPConf talks were, in general, pretty intense, in a good way. The content was heavy on "here's how we did it!" and pretty light on basics.

## Further exploration

Whenever I go to conferences, I keep a running "things to check out list." Speakers always mention technologies and approaches and vocabulary that's completely new to me and I know I'd be remiss in not taking note. Here's my list for gRPConf:

* **Load balancing strategies** --- In my mind, there are two strategies for load balancing: round robin and, um, some other one? gRPConf convinced me that I need to dig deeper. Speakers mentioned least-N random, absolute least connection, and several other load balancing strategies. Time to bone up.
* **FlatBuffers** --- Most people use gRPC with [Protocol Buffers](https://developers.google.com/protocol-buffers/), which makes sense given Protobuf's huge (and I think justified) momentum. [FlatBuffers](https://google.github.io/flatbuffers/) is a Protobuf alternative, [supported in gRPC](../flatbuffers), mentioned in several talks and conversations.
* **HTTP/2** --- Since its inception, I've understood HTTP/2 only well enough to understand its core differences from HTTP/1.1. gRPConf convinced me that that knowledge won't suffice to understand future developments in the Cloud Native landscape, particularly with [HTTP/3 and the QUIC protocol](https://http3-explained.haxx.se/en/) on the way. I'm hoping that [Google's primer](https://developers.google.com/web/fundamentals/performance/http2/) can help me out.

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>