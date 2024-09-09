# Reserve Core Mitigation Review
- Total Prize Pool: 17,250 in USDC
  - HM awards: 14,000 in USDC
  - Judge awards: $3,000 in USDC
- [Warden guidelines for C4 mitigation reviews](https://code4rena.notion.site/Guidelines-for-C4-mitigation-reviews-ed10fc5cfbf640bd8dcec66f38b343c4)
- Starts September 12, 2024 20:00 UTC 
- Ends September 17, 2024 20:00 UTC 

## Important note 

Each warden must submit a mitigation review for *every* individual PR listed in the `Scope` section below. **Incomplete mitigation reviews will not be eligible for awards.**

## Findings being mitigated

Mitigations of all High and Medium issues will be considered in-scope and listed here.

- [M-01: RToken can manipulate distribution to avoid paying DAO fees](https://github.com/code-423n4/2024-07-reserve-findings/issues/53)
- [M-02: Broken assumptions can lead to the inability to seize RSR](https://github.com/code-423n4/2024-07-reserve-findings/issues/39)
- [M-03: The default Governor Anastasius is unable to call resetStakes](https://github.com/code-423n4/2024-07-reserve-findings/issues/36)
- [M-04: Dutch auctions can fail to settle if any other collateral in the basket behaves unexpectedly](https://github.com/code-423n4/2024-07-reserve-findings/issues/32)
- [M-05: Users can dodge losses due to StRSR era changes with instant operations](https://github.com/code-423n4/2024-07-reserve-findings/issues/21)
- [M-06: The time available for a canceled withdrawal should not impact future unstaking processes](https://github.com/code-423n4/2024-07-reserve-findings/issues/18)
- [M-07: The traceEnd in BackingManager isn't updating correctly](https://github.com/code-423n4/2024-07-reserve-findings/issues/6)

[ ⭐️ SPONSORS ADD INFO HERE ]

## Overview of changes

Please provide context about the mitigations that were applied if applicable and identify any areas of specific concern.

## Scope

### Branch
[ ⭐️ SPONSORS ADD A LINK TO THE BRANCH IN YOUR REPO CONTAINING ALL PRS ]

### Mitigation of High & Medium Severity Issues
[ ⭐️ SPONSORS ADD ALL RELEVANT PRs TO THE TABLE BELOW:]

Wherever possible, mitigations should be provided in separate pull requests, one per issue. If that is not possible (e.g. because several audit findings stem from the same core problem), then please link the PR to all relevant issues in your findings repo. 

| URL | Mitigation of | Purpose | 
| ----------- | ------------- | ----------- |
| https://github.com/your-repo/sample-contracts/pull/XXX | H-01 | This mitigation does XYZ | 

### Additional scope to be reviewed
[ ⭐️ CAS PLEASE REMOVE THIS SECTION IF THE SPONSOR IS ONLY MITIGATING HMS]

[ ⭐️ SPONSORS ADD ALL RELEVANT PRs TO THE TABLE BELOW:]

These are additional changes that will be in scope.

| URL | Mitigation of | Purpose | 
| ----------- | ------------- | ----------- |
| https://github.com/your-repo/sample-contracts/pull/XXX | H-01 | This mitigation does XYZ | 

## Out of Scope

Please list any High and Medium issues that were judged as valid but you have chosen not to fix.
