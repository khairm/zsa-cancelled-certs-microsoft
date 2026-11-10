# zsa-cancelled-certs-microsoft

Public certificate revocation list (CRL) for the private root CA "Service App for Testing - Root CA".

- `root.crl`: DER CRL signed by that CA, served at http://khairm.github.io/zsa-cancelled-certs-microsoft/root.crl
- `ledger.tsv`: certificates issued by the CA.
- `revoked.tsv`: certificates revoked; `root.crl` is re-signed from it.

No secrets live here.
