# AI Venture Studio

**9 free macOS apps. Built autonomously, one every morning.**

Every morning an automated pipeline picks an opportunity, researches the market,
writes the code, compiles it, tests it, and ships a signed-off installer — with no
human in the loop. These are the results. All free, no signup, no tracking.

[**Browse all 9 apps with screenshots →**](https://kdylan1010-alt.github.io/venture-studio-portfolio/)

<p align="center">
  <a href="https://kdylan1010-alt.github.io/venture-studio-portfolio/v/contract-drift-finder.html"><img src="shots/contract-drift-finder.png" width="720" alt="ContractDriftFinder"></a>
  <br><sub><i>ContractDriftFinder — one of 9 tools below</i></sub>
</p>

---

## Download

| App | What it does | Get it |
|---|---|---|
| **[ContractDriftFinder](https://kdylan1010-alt.github.io/venture-studio-portfolio/v/contract-drift-finder.html)** | A native macOS app for SMB owners, ops managers, and freelancers that opens PDFs locally,… | [⬇ Download](https://github.com/kdylan1010-alt/venture-studio-portfolio/releases/download/contract-drift-finder/ContractDriftFinder.dmg) <br><sub>60 KB</sub> |
| **[LocalSecretsPIISweeper](https://kdylan1010-alt.github.io/venture-studio-portfolio/v/local-secrets-pii-sweeper.html)** | A privacy-first native macOS utility for consultants, agencies, and small businesses that scans… | [⬇ Download](https://github.com/kdylan1010-alt/venture-studio-portfolio/releases/download/local-secrets-pii-sweeper/LocalSecretsPIISweeper.dmg) <br><sub>142 KB</sub> |
| **[BidTriage](https://kdylan1010-alt.github.io/venture-studio-portfolio/v/local-rfp-triage.html)** | Local RFP/Bid Triage Assistant for small contractors: target users are small… | [⬇ Download](https://github.com/kdylan1010-alt/venture-studio-portfolio/releases/download/local-rfp-triage/BidTriage.dmg) <br><sub>57 KB</sub> |
| **[GatewayControlCenter](https://kdylan1010-alt.github.io/venture-studio-portfolio/v/mac-secret-sweep.html)** |  | [⬇ Download](https://github.com/kdylan1010-alt/venture-studio-portfolio/releases/download/mac-secret-sweep/GatewayControlCenter.dmg) <br><sub>83 KB</sub> |
| **[TaxGapScout](https://kdylan1010-alt.github.io/venture-studio-portfolio/v/offline-tax-gap-scanner.html)** | A local-only macOS desktop app for freelancers and microbusinesses that scans receipts, bank… | [⬇ Download](https://github.com/kdylan1010-alt/venture-studio-portfolio/releases/download/offline-tax-gap-scanner/TaxGapScout.dmg) <br><sub>62 KB</sub> |
| **[DownloadTriageAssistant](https://kdylan1010-alt.github.io/venture-studio-portfolio/v/download-triage-assistant.html)** | A native macOS desktop utility for security-conscious users, consultants, and IT admins that… | [⬇ Download](https://github.com/kdylan1010-alt/venture-studio-portfolio/releases/download/download-triage-assistant/DownloadTriageAssistant.dmg) <br><sub>67 KB</sub> |
| **[AirgapGatewayControl](https://kdylan1010-alt.github.io/venture-studio-portfolio/v/airgap-redaction-workbench.html)** | Air-gapped Redaction Workbench: target users are law firms, compliance teams, journalists, and… | [⬇ Download](https://github.com/kdylan1010-alt/venture-studio-portfolio/releases/download/airgap-redaction-workbench/AirgapGatewayControl.dmg) <br><sub>112 KB</sub> |
| **[ReceiptSentinel](https://kdylan1010-alt.github.io/venture-studio-portfolio/v/receipt-sentinel.html)** | Receipt Sentinel: a native macOS app for freelancers, contractors, and very small businesses… | [⬇ Download](https://github.com/kdylan1010-alt/venture-studio-portfolio/releases/download/receipt-sentinel/ReceiptSentinel.dmg) <br><sub>70 KB</sub> |
| **[DepositPacket](https://kdylan1010-alt.github.io/venture-studio-portfolio/v/tenant-deposit-dispute-packet.html)** | A local macOS app for renters moving out that turns move-in photos, receipts, inspection notes,… | [⬇ Download](https://github.com/kdylan1010-alt/venture-studio-portfolio/releases/download/tenant-deposit-dispute-packet/DepositPacket.dmg) <br><sub>61 KB</sub> |

<sub>9 apps · 0.7 MB total · macOS 12+</sub>

---

## First launch: "cannot be opened because the developer cannot be verified"

These apps are **unsigned** — Apple charges $99/year for a signing certificate, and
these are free. macOS will block the first open. To run one:

> **Right-click** (or Control-click) the app → **Open** → **Open** again in the dialog.

You only do this once per app. Or from Terminal: `xattr -dr com.apple.quarantine /Applications/<AppName>.app`

Everything is open source — the Swift source for each app is in
[its release](https://github.com/kdylan1010-alt/venture-studio-portfolio/releases), so you can read
exactly what it does before running it.

---

## How these get made

```
scan opportunities → score on 8 axes → research market → write spec
      → build → verify → independent review → package → publish
```

Each app is chosen by scoring candidates 1–10 across eight competing perspectives
— profit, change, effort, viability, future, market, population, availability —
and picking the best *balance*, not the best single score. The per-app pages show
that scoring, the market research, and the review that approved it.

[**See the full record for every app →**](https://kdylan1010-alt.github.io/venture-studio-portfolio/)
