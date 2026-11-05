# [STRU] SOCRadar Threat Research Unit - IOCs

This repository contains indicators of compromise (IOCs) that support and
accompany the threat research published by **SOCRadar**. Each file gathers
the indicators referenced in one of our investigations, so defenders can consume
them for detection and hunting.

Provided "as is" to the public for defensive and research purposes.

## About

Maintained by the Threat Research team at **SOCRadar**. Every set of
indicators links back to the investigation that produced it, to help the
community detect, hunt for, and defend against the threats we cover.

## Structure

Files are named by date and topic:

`YYYY-MM-DD-IOCs-[topic].[txt|md|csv]`

Each file includes the indicators, the publication date, and a reference to the
related investigation.

## Format

Files are plain text. Each one starts with the publication date and a link to the research, followed by indicators grouped by type (URLs, Domains, Hashes, etc.).

Indicators are defanged to prevent accidental clicks, e.g. `https[://]example[.]com` or `example[.]com`. Refang them before ingesting them into your tooling.

## How to use

- Browse or clone the repository to ingest indicators into your own tooling.
- Each file is standalone and maps to one investigation.
- Shared for detection and defensive use only.

## Attribution

Attribution to **STRU** or **SOCRadar** is required when redistributing or adapting
these files: keep the copyright and license notices intact, as required by the
license. When referencing this work in your own research or tooling, a link back
to STRU research is appreciated.

## Feedback

Indicators are shared as TLP:CLEAR. To report a false positive or ask a question, open an issue or contact STRU at info@socradar.io

## Disclaimer

These indicators are published in good faith for defensive and research
purposes, "as is", without warranty of any kind. Validate them in your own
environment before acting; false positives are possible. SOCRadar is not
responsible for any misuse of this information.

## License

Licensed under the [GNU General Public License v3.0](LICENSE)

Copyright (C) 2026 SOCRadar. All rights reserved where applicable.
