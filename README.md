<p align="center">
  <img src="assets/greeninvest-banner.svg" alt="GreenInvest Pakistan" width="100%">
</p>

<h1 align="center">GreenInvest Pakistan</h1>

<p align="center">
  A consumer solar decision system for Pakistan: one clear recommendation for
  solar, battery storage, inverter capacity, expected cost, and the future bill.
</p>

<p align="center">
  <a href="https://greeninvest-pakistan.vercel.app"><strong>Open the live calculator</strong></a>
  ·
  <a href="https://github.com/GreenInvest-Pakistan/GreenInvest-Consumer/releases/latest/download/GreenInvest-Windows-x64.zip"><strong>Download for Windows</strong></a>
  ·
  <a href="https://github.com/GreenInvest-Pakistan/GreenInvest-Consumer/releases/latest"><strong>Release notes and checksums</strong></a>
</p>

> This public repository contains consumer documentation and compiled release
> packages. It does not contain GreenInvest's proprietary calculation source,
> ranking rules, methodology implementation, pricing catalogue, private owner
> tools, database configuration, or engineering history.

## What GreenInvest answers

GreenInvest turns electricity use, the present bill, a desired future bill,
budget, roof space, backup needs, and selected location into practical answers:

- Should this case proceed with solar now?
- What solar, inverter, and battery sizes should be considered?
- What is the screened system cost?
- What could the electricity bill become?
- Which constraints, risks, and evidence checks matter before purchase?

It offers two starting points:

1. **Build my recommendation** — guided screening from household or business
   requirements.
2. **Check an installer quote** — compare a proposed configuration with the
   entered needs and constraints.

![GreenInvest homepage](assets/homepage.png)

## What the result includes

- A clear install, conditional, or do-not-install outcome.
- Selected and alternative plan comparisons.
- Solar, inverter, battery, and outage-backup sizing.
- Seasonal consumption shaping and monthly bill estimates.
- Roof, budget, bill-target, and equipment checks.
- Risks, sensitivity analysis, and Monte Carlo uncertainty on demand.
- Plain-language, CSV, and machine-readable downloads.
- Pakistan consumption-slab screening with fixed grid charges and an explicit
  warning that taxes, fuel adjustments, duties, surcharges, and other utility
  items can increase the final bill.

![Recommendation result](assets/my-decision-result.png)

## Windows application

The Windows package is portable and standalone:

1. Download [`GreenInvest-Windows-x64.zip`](https://github.com/GreenInvest-Pakistan/GreenInvest-Consumer/releases/latest/download/GreenInvest-Windows-x64.zip).
2. Right-click the ZIP and select **Extract All**.
3. Open the extracted folder and run `GreenInvest.exe`.

The package includes its own Python 3.13 and Qt WebEngine runtimes. It does not
require Python, Node.js, Vercel, a separate browser, or an installer. Windows
10 or 11 on a 64-bit PC is supported. Allow about 400 MiB of extracted disk
space. Because this preview is not code-signed, Windows SmartScreen may ask for
confirmation before the first launch.

Calculations run locally and continue to work offline. The latest draft and
completed result remain on that Windows account. If the device is online, only
the documented minimal anonymous project event and feedback explicitly approved
for evaluation can be sent to the GreenInvest project store.

See [release and checksum instructions](RELEASES.md).

## Privacy

GreenInvest does not request a name, email address, electricity account number,
or home address for a recommendation. The public impact view contains aggregate
project records, not individual responses or comments. Optional comments should
never contain bills, account numbers, addresses, or identifying details.

Read the complete [consumer privacy summary](PRIVACY.md).

## Important decision boundary

GreenInvest is a screening and decision-support tool—not an installer quotation,
engineering design, financing offer, warranty, tax calculation, or guarantee of
savings. Tariffs, taxes, equipment prices, policies, export compensation, and
site conditions can change. Confirm the final design, roof structure, protection
equipment, warranties, utility treatment, and complete bill with qualified local
professionals before spending money.

Read [known limitations](KNOWN-LIMITATIONS.md).

## Support and security

- General help: [support guide](SUPPORT.md)
- Product problem: [open an issue](https://github.com/GreenInvest-Pakistan/GreenInvest-Consumer/issues/new/choose)
- Sensitive security report: [private vulnerability report](https://github.com/GreenInvest-Pakistan/GreenInvest-Consumer/security/advisories/new)
- Live service: [greeninvest-pakistan.vercel.app](https://greeninvest-pakistan.vercel.app)

Do not put electricity bills, addresses, account numbers, private quotations,
owner tokens, or other personal information in a public GitHub issue.

## Ownership and licence

GreenInvest Pakistan remains an independently owned product. Public access to
this repository does not make the proprietary model open source. Consumers may
download and use the unmodified compiled application under [the consumer-use
notice](LICENSE.md). Bundled open-source components retain their own licences;
see [third-party notices](THIRD-PARTY-NOTICES.md).
