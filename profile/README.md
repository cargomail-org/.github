The email system, while conceptually sound as a communication means, is structurally obsolete and functionally deficient. Our goal is to overcome the current data storage and transfer limitations in the email system.

We introduce an authentication mechanism through the [Identity Propagation and Assertions](https://github.com/cargomail/identity-propagation-and-assertions) concept. This mechanism is beneficial in the email system to protect MTA-to-MTA communication.

As a proof of concept, we developed [Cargomail](https://github.com/cargomail/cargomail) — a revised email system. This email system uses an [Intermodal Message Transfer Agent (iMTA)](https://github.com/cargomail/imta) to transfer email resources from one server to another using push and pull modes.
