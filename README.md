# Mugraph Improvement Proposals

> [!WARNING]
> Please keep in mind that Mugraph is pre-alpha software, and has not been either audited nor it is feature-complete currently even for early adopters.
> Even if you for some reason decide to use it, do at your own risk.

This project tracks the specification for the Mugraph protocol through **Mugraph Improvement Proposals (MUIPs)**. Specifications present on this folder should guide the implementation itself.

## Implementations

Those are the projects that currently implement either part or the full specification:

- [🦀 Mugraph](https://mugraph.dev): The reference implementation of the protocol.

If you are implementing your own, be free to add and update with details from your own implementation.

## Current Proposals

| ID | Name | Description |
|-|-|-|
| [0001](./muips/0001-append.md) | Append | Sends a transaction, consuming a list of e-cashes and creating new ones in the process. |
| [0002](./muips/0002-invoices.md) | Invoices | Creates a payment request to be fulfilled by an user. |

Status:

- ✅: This MUIP is fully supported on the implementation.
- ❌: This MUIP is not supported on the implementation.
- ⚠️ : This MUIP is either partially implemented or misbehaves according to the spec.

## Compatibility Matrix

| ID | Name | [Mugraph](https://mugraph.dev) |
|-|-|-|
| 0001 | Append | ❌ |
| 0002 | Invoices | ❌ |
