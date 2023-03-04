The email system, while conceptually sound as a communication means, is structurally obsolete and functionally deficient. Given that, we introduce [Cargomail](https://github.com/cargomail-org/cargomail) — an OAuth2-based email system.

We propose an authentication mechanism through the [Global Reference Identity Protocol (GRIP)](https://github.com/cargomail-org/grip). This mechanism is beneficial in the email system to protect [MTA-to-MTA](https://github.com/cargomail-org/mta) communication.

Cargomail uses a newly designed [Resource Retrieval System (RRS)](https://github.com/cargomail-org/rrs) to transfer email resources using a pull mode. This mode helps to overcome the email system's data storage and transmission limitations.

