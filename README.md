# DWSC 100 Club — Public Verification Data

This repository holds the public verification data for the
Draycote Water Sailing Club 100 Club, a Small Society Lottery
registered with Rugby Borough Council.

## What's here

`draws.json` — a structured record of every completed monthly draw,
including the eligible credit count, prize fund, winning entry numbers,
prize amounts, and the random.org reference used to select winners.

The file is automatically updated when each monthly draw runs.

## Privacy

Winners are identified by entry number only. Member names are not
published in this repository. Names are announced to club members
through the club's monthly newsletter.

## Verification

Each draw record includes a reference to the random.org request that
selected the winners. The reference can be used to retrieve the original
random.org response and verify that the winning numbers were selected at
random and have not been altered.

## Audit trail

The complete history of every change to `draws.json` is preserved in
this repository's git history. Any modification of past draw data
(beyond the addition of a new draw) is therefore visible to anyone
auditing the repository.

## Contact

https://draycotewater.co.uk
