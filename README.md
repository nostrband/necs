# NECs

NECs stand for Nostr Enclave Conventions.

They exist to document how services running in TEEs (Trusted Execution Environments like AWS Nitro Enclaves) can use [Nostr](https://github.com/nostr-protocol/nips) to interoperate with clients and with each other.

## List

- [NEC-01 AWS Nitro Enclave Attestations](./01.md)
- [NEC-02 Enclaved Service Announcements](./02.md)
- [NEC-03 Code Builder Signatures](./03.md)
- [NEC-04 Enclave Launcher Signatures](./04.md)
- [NEC-05 Code Release Signatures](./05.md)
- [NEC-06 TEE Key Storage](./06.md)
- [NEC-07 Code Upgrades in TEE](./07.md)

## Event Kinds

| kind | description | NEC |
|------|-------------|-----|
| 23793 | TEE Attestation | [01](./01.md) |
| 13793 | Service Announcement | [02](./02.md) |
| 23794 | Builder Signature | [03](./03.md) |
| 23795 | Instance Signature | [04](./04.md) |
| 63794 | Release Signature | [05](./05.md) |
