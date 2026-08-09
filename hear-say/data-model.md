# HEAR SAY data model

The platform should store structured records rather than only free-text stories.

## Experience

- contributor_id (pseudonymous)
- submission_date
- anonymity_choice
- location/region (optional, broad only)
- court/system area
- date_range
- narrative
- claimed events
- requested outcome
- publication status

## Event

- event_id
- experience_id
- date
- event_type
- description
- source_ids
- verification_status

## Source

- source_id
- experience_id
- source_type
- date
- description
- public_url or stored reference
- redaction_status
- verification_status

## Outcome

- outcome_id
- experience_id
- date
- authority
- response
- result
- source_ids

## Editorial rules

Never infer guilt, fraud, misconduct or unlawful conduct merely from a pattern. Pattern detection is a research aid that identifies material for human review. Publication requires a clear distinction between allegation, evidence and verified finding.

## Python analysis layer

Python can later produce:

1. Chronology validation and date-gap detection.
2. Duplicate/near-duplicate document detection using hashes and text similarity.
3. Entity and event linking across records.
4. Aggregate counts by issue type, process stage and outcome.
5. Trend analysis over time.
6. Network graphs showing relationships between events, documents and institutions.
7. An evidence index for each published story.

Any automated output should be labelled as analysis, not proof.
