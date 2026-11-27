# Prasiddh Bharat — Public Data

This repository contains reviewed, approved public information used by Prasiddh Bharat applications and the public portal.

## Ratnagiri district dataset

- Public JSON: `data/ratnagiri/records.json`
- Published records: 168 approved records
- Dataset status: approved records only
- Every record includes its official source name, source URL, fetched timestamp and verification timestamp where available.

## Publishing and privacy rules

- Only human-reviewed and approved records are published.
- Pending, rejected, needs-correction, inactive and superseded records are excluded.
- Internal review notes, reviewer details, audit logs and source-monitoring queues are never published.
- Personal mobile numbers are not published unless explicitly verified as official public contact channels. Redacted values remain redacted.
- Changes should use clear commit messages and preserve source attribution.

## Data contract

The canonical record structure is maintained in the private `prasiddh-bharat-engine` repository. Public records are transformed to remove internal review metadata before publication.
