# iso20022

[ISO 20022] Universal Financial Message Scheme in Rust.

[![drone]](https://cloud.drone.io/keithnoguchi/iso20022-rs)

[drone]: https://cloud.drone.io/api/badges/keithnoguchi/iso20022-rs/status.svg

Here is the list of currently supported message schemes:

- [Business Application Header]
  - [head.001.001.02] BusinessApplicationHeaderV02
- [Payments Messages]
  - [pain.001.001.10] CustomerCreditTransferInitiationV10
  - [pain.002.001.11] CustomerPaymentStatusReportV11

[iso 20022]: https://www.iso20022.org/
[business application header]: https://www.iso20022.org/bah.page
[payments messages]: https://www.iso20022.org/payments_messages.page
[head.001.001.02]: proto/head.001.001.02.proto
[pain.001.001.10]: proto/pain.001.001.10.proto
[pain.002.001.11]: proto/pain.002.001.11.proto