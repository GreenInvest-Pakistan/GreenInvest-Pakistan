# Security policy

## Supported releases

Security corrections apply to the latest published GreenInvest Windows release
and the current hosted service. Older ZIPs, copies from third-party websites,
and modified packages are not supported.

## Reporting a vulnerability

Use GitHub's
[private vulnerability reporting](https://github.com/GreenInvest-Pakistan/GreenInvest-Consumer/security/advisories/new).
Include the affected release, operating system or hosted route, reproduction
steps, impact, and any safe proof of concept.

Do not open a public issue for an unpatched vulnerability. Do not include real
consumer bills, addresses, account numbers, feedback, private quotations,
database credentials, or access tokens.

## Release verification

Download only from this repository's Releases page. Verify the SHA-256 checksum
using [RELEASES.md](RELEASES.md). A mismatched archive should not be opened.

The Windows preview is not presently code-signed, so a valid checksum confirms
file identity but does not replace operating-system reputation or signature
checks.
