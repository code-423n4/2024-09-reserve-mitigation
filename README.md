# Reserve Core Mitigation Review

- Total Prize Pool: 17,500 in USDC
  - HM awards: 14,000 in USDC
  - Judge awards: $3,000 in USDC
  - Scout awards: $500 in USDC
- [Warden guidelines for C4 mitigation reviews](https://code4rena.notion.site/Guidelines-for-C4-mitigation-reviews-ed10fc5cfbf640bd8dcec66f38b343c4)
- Starts September 12, 2024 20:00 UTC
- Ends September 17, 2024 20:00 UTC

## Important note

Each warden must submit a mitigation review for _every_ individual PR listed in the `Scope` section below. **Incomplete mitigation reviews will not be eligible for awards.**

## Findings being mitigated

Mitigations of all High and Medium issues will be considered in-scope and listed here.

- [M-01: RToken can manipulate distribution to avoid paying DAO fees](https://github.com/code-423n4/2024-07-reserve-findings/issues/53)
- [M-02: Broken assumptions can lead to the inability to seize RSR](https://github.com/code-423n4/2024-07-reserve-findings/issues/39)
- [M-03: The default Governor Anastasius is unable to call resetStakes](https://github.com/code-423n4/2024-07-reserve-findings/issues/36)
- [M-04: Dutch auctions can fail to settle if any other collateral in the basket behaves unexpectedly](https://github.com/code-423n4/2024-07-reserve-findings/issues/32)
- [M-05: Users can dodge losses due to StRSR era changes with instant operations](https://github.com/code-423n4/2024-07-reserve-findings/issues/21)
- [M-06: The time available for a canceled withdrawal should not impact future unstaking processes](https://github.com/code-423n4/2024-07-reserve-findings/issues/18)
- [M-07: The traceEnd in BackingManager isn't updating correctly](https://github.com/code-423n4/2024-07-reserve-findings/issues/6)

Additional fixes for QA/L issues were made, additionally some issues deemed invalid were also taken into account.

## Scope

### Branch

https://github.com/reserve-protocol/protocol/pull/1204

### Mitigation of High & Medium Severity Issues

Wherever possible, mitigations should be provided in separate pull requests, one per issue. If that is not possible (e.g. because several audit findings stem from the same core problem), then please link the PR to all relevant issues in your findings repo.

| URL                                                    | Mitigation of |
| ------------------------------------------------------ | ------------- |
| https://github.com/reserve-protocol/protocol/pull/1191 | M-01          |
| https://github.com/reserve-protocol/protocol/pull/1198 | M-02          |
| https://github.com/reserve-protocol/protocol/pull/1193 | M-03          |
| https://github.com/reserve-protocol/protocol/pull/1199 | M-05          |
| https://github.com/reserve-protocol/protocol/pull/1194 | M-06          |
| https://github.com/reserve-protocol/protocol/pull/1195 | M-07          |

### Additional scope to be reviewed

These are additional changes that will be in scope. Changes marked as `MISC` are from reports that were not judged as valid issues but are being included for review.

| URL                                                    | Mitigation of |
| ------------------------------------------------------ | ------------- |
| https://github.com/reserve-protocol/protocol/pull/1192 | MISC          |
| https://github.com/reserve-protocol/protocol/pull/1196 | MISC          |
| https://github.com/reserve-protocol/protocol/pull/1203 | MISC          |
| https://github.com/reserve-protocol/protocol/pull/1197 | QA-15         |
| https://github.com/reserve-protocol/protocol/pull/1201 | QA-33         |
| https://github.com/reserve-protocol/protocol/pull/1188 | QA            |

We'd like some extra eyes on the following changes, since they are not in the "obviously safe" category:

| URL                                                    | Mitigation of |
| ------------------------------------------------------ | ------------- |
| https://github.com/reserve-protocol/protocol/pull/1198 | M-02          |
| https://github.com/reserve-protocol/protocol/pull/1199 | M-05          |

## Out of Scope

Please list any High and Medium issues that were judged as valid but you have chosen not to fix.

- [M-04: Dutch auctions can fail to settle if any other collateral in the basket behaves unexpectedly](https://github.com/code-423n4/2024-07-reserve-findings/issues/32)
