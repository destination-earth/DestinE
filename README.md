# DestinE

## About DestinE

[Destination Earth](https://www.destination-earth.eu/) is a European Union initiative to build a highly accurate digital model of the Earth, used to monitor natural and human activity, anticipate extreme events, and support climate-related policy. It is part of the European Commission's Green Deal and Digital Strategy and contributes to the twin green and digital transition.

## What's in this organisation

This GitHub organisation gathers:

- Open source software developed under DestinE contracts with the Entrusted Entities (ECMWF, ESA, EUMETSAT), including Use Cases.
- Documentation released under the openness principle and open to community review (user requirements, community engagement strategy, exploitation roadmap, and similar).
- Tools for contributing content to the DestinE website.
- Links to external open source repositories that are highly relevant to DestinE but developed outside the initiative.

## Repository naming convention

Every repository (except this one) is prefixed with a label that identifies its funding line and, where applicable, the Entrusted Entity:

- `DestinE_<EE>_<name>` — funded by DestinE, developed by an Entrusted Entity. Example: `DestinE_ESA_UseCase42`.
- `HorizonE_<name>` — funded under Horizon Europe.
- `Partnership_<name>` — funded through other partnerships.

When the actual code lives outside this organisation, the placeholder repository uses the `XRL` (eXternal Repository Link) tag after the funding line. It contains a short project description and a link to the real repository. Example: `Partnership_XRL_Project17`.

This convention applies to every new repository.

### Special repositories

- **DestinE** — this repository; landing page for the community.
- **DestinE_ESA_DESP_Use_Cases_Management** — project outputs open to community contribution (DESP user requirements, Community Building and Management Strategy, DestinE Exploitation Roadmap).
- **DestinE_ESA_Website** — where the community proposes content for the DestinE website.
- **DestinE-DataLake-Lab** — examples of how to use DestinE Data Lake services.

## Creating a new repository

To request a new repository, contact one of the three Entrusted Entities (ECMWF, ESA, or EUMETSAT).

### Choosing public or private

The choice depends on the funding source (European Commission vs. ESA), the project's objectives, and its type (commercialisation, innovation, startup, hackathon, open source). Public is the default for open source deliverables; private is used when confidentiality is required by the contract or when internal checks are still pending.

### Setup process

1. **Creation.** The repository is created following the DestinE GitHub repository generation guide (link TBD).
2. **Ownership.** The repository is assigned to a specific project or service with a dedicated management team. The Entrusted Entity that creates the repository invites the future admins.
3. **Initial visibility.** The repository is created as private and remains private until the internal checks are complete. The owner then either flips it to public or keeps it private, depending on the project.
4. **Roles.** The repository admin has full control (settings, collaborators, security) and is fully responsible for the repository. Collaborators are invited by the admin and do not receive admin rights, to keep ownership clear.

## Repository requirements

Every repository in this organisation must include the following:

| Item | Notes |
|---|---|
| Name following the convention above | See "Repository naming convention". |
| `README.md` | Purpose, usage, and how to contribute. |
| `LICENSE` | Open source licence appropriate to the project. |
| `CODE_OF_CONDUCT.md` | See [Code of Conduct](CODE_OF_CONDUCT.md). |
| `RULE_OF_PARTICIPATION.md` | See [Rule of Participation](RULE_OF_PARTICIPATION.md). |
| `.gitignore` | Appropriate to the languages used. |
| Installation guide | Inside the README or a dedicated file. |
| Documentation | Sufficient for a new user to understand and use the project. |
| Tagged releases | Follow semantic versioning where practical. |
| At least one admin | Responsible for the repository's health. |

Recommended: an issue template (`.github/ISSUE_TEMPLATE/`) to make it easier for the community to report bugs and request features.

## Contributing

See the [Rule of Participation](RULE_OF_PARTICIPATION.md) for how to contribute to DestinE open source repositories.

## Code of Conduct

The DestinE open source community follows this [Code of Conduct](CODE_OF_CONDUCT.md).

## More information

Visit [destination-earth.eu](https://www.destination-earth.eu/).
