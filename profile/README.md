# FortuneLabs

Direct semantic communication for constrained hardware.

We build the case, piece by piece, for a protocol that transfers meaning
instead of raw data. We proved the mechanism first between two
independently trained language models. Now we're taking the same claim
to the radios and microcontrollers that never get that luxury.

## What we're building

**ESCP**, the Elision Semantic Communication Protocol: a wire format and
reference SDK for transferring semantic representations across
constrained hardware, agnostic to the device or the medium carrying it.

[`cache-2-cache-lite`](https://github.com/fortunelabs-io/cache-2-cache-lite)
is where the mechanism was proven: a small trained bridge between two
language models that beats raw-data transfer, measured and reproducible.

[`direct-semantic-comm`](https://github.com/fortunelabs-io/direct-semantic-comm)
is where the same mechanism gets re-tested on real hardware, one
falsifiable stage at a time.

[`fortunelabs-mainboard-l`](https://github.com/fortunelabs-io/fortunelabs-mainboard-l)
is the hardware and firmware everything above gets tested on.

[`latent-c`](https://github.com/fortunelabs-io/latent-c) carries the
reference SDK for ESCP.

## Follow along

We build in public: [Instagram](https://instagram.com/fortunelabs.io) · hello.fortunelabs@gmail.com
