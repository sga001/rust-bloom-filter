rust-bloom-filter
=================

A fast Bloom filter implementation in Rust. Code has been modified to use
metrohash and to not have a random key. This is useful if you need to send
these bloom filters over the network and you need an easy way to initialize
them at the recipient without having to share key material, etc.
