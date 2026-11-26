<img width="2704" height="624" alt="nexform-wordmark-dark" src="https://github.com/user-attachments/assets/35686acb-128d-4ab4-8542-628236d98251" />

## What we do

Nexform Consulting helps organisations build, extend, and run SAP systems the right way — clean, upgrade-safe, and grounded. We work close to the code and close to the business.

## Services

- **RAP development** — transactional Fiori apps and OData services with the ABAP RESTful Application Programming Model, managed or unmanaged, with draft
- **Interfaces and integrations** — IDocs, OData and SOAP services, BAPIs and file interfaces between SAP and third-party systems
- **Clean Core development** — extensions built with ABAP Cloud and released APIs that survive every upgrade
- **Custom code modernisation** — moving classic ABAP towards released APIs, wrappers and a clean core
- **Classic ABAP** — reports, enhancements and forms on ECC and S/4HANA, written to today's standards

## Products

| Repository | What it is |
|---|---|
| [Bill of Exchange Manager](https://github.com/Nexform/bill-of-exchange-manager) | Migration workbench and register for cheques and bills of exchange (επιταγές, συναλλαγματικές) in S/4HANA Cloud Public Edition, Private Edition and on-premise. One RAP application for every edition. *Pre-release.* |

## Open source

Libraries written and maintained by our founder, [George Drakos](https://github.com/greltel). All of them are installed with abapGit and tested off-stack in GitHub Actions.

| Repository | What it is |
|---|---|
| [ABAP Cloud Logger](https://github.com/greltel/abap-cloud-logger) | Fluent, unit-tested logging for ABAP Cloud (S/4HANA, SAP BTP) on top of `CL_BALI_LOG` |
| [ABAP Test Kit](https://github.com/greltel/abap-test-kit) | Test doubles and spies for ABAP Unit, with failure messages a developer can read |
| [SALVage](https://github.com/greltel/salvage) | Fluent wrapper around `CL_SALV_TABLE` |
| [IDoctor](https://github.com/greltel/IDoctor) | Object-oriented reading and changing of IDocs |
| [ABAP Point Gate](https://github.com/greltel/abap-point-gate) | Framework for switchable, traceable enhancements |
| [ABAP Cloud Utilities](https://github.com/greltel/abap-cloud-utilities) | Utility library for ABAP for Cloud Development |
| [ABAP Form Translator](https://github.com/greltel/abap-form-translator) | Runtime translation of SAP form labels, maintained in a Fiori Elements app — no SE63, no transport for a changed label |
| [ABAP Dynamic Assignment](https://github.com/greltel/abap-dynamic-assignment) | Runtime parameter framework for ABAP Cloud: variables, ranges and mappings maintained in a Fiori app instead of hardcoded values or TVARVC |

## How we work

- Every deliverable comes with ABAP Unit tests
- abaplint and ATC run clean before anything is handed over
- Unit tests also run off-stack in CI, on every pull request
- Clean ABAP: readable names, small methods, no surprises for the next developer
- AI-assisted delivery, guided by our own ABAP rulebook and reviewed by a person

## Contact

Nexform Consulting L.P. — Athens, Greece
[George Drakos on GitHub](https://github.com/greltel)
