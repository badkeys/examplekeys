# examplekeys
Example private and public keys in various formats

Subdirectories / key formats:

* `pkcs8-pem-private`: Keys in PKCS #8 (RFC 5958) PEM format format with the
  `-----BEGIN PRIVATE KEY-----` header. The most commonly used private key format.

* `spki-pem-public`: Subject Public Key Info (RFC 5280) PEM format with the
  `-----BEGIN PUBLIC KEY-----` header.

* `traditiona-pem-private`: The "traditional" private key format shows the algorithm in
  the header, e.g., `-----BEGIN RSA PRIVATE KEY-----`, `-----BEGIN EC PRIVATE KEY-----`.
  It is not supported for modern key types like Ed25519.


# copyright

This README file and other documentation in this repository is licensed as CC0.

The keys are examples from various IETF RFCs. Computer-generated cryptographic keys
should not generate any copyright. In case creating this collection creates any
intellectual ownership, it shall also be licensed as CC0.
