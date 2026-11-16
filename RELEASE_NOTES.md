Desktop application for preparing New Zealand Research and Development Tax Incentive claims.

**Download page: https://blog.rdinnovate.com/workbench-nz/**

### What's new in 1.0.3

A maintenance release of fixes. The law the app applies is unchanged from 1.0.2.

**Feedstock, contractors and expenses**
- Feedstock: the inputs excluded are matched to the feedstock product, first through its linked
  activity and then across the claim, before other goods.
- Contractors follow the New Zealand rules throughout: approved research providers, associated
  persons at cost, and overseas R&D under the 10% cap. Cards and allocations show the claimable
  amount at cost for associates.
- Number fields no longer show a leading 0.

**Financials and classification**
- Unticking a profit and loss or balance sheet item as R&D also clears the matching general ledger
  account.
- The reconciliation check reads a balance sheet whose liabilities and equity are entered as
  negative (credit) figures correctly.
- The "No items classified as R&D" warning appears only when cost lines were reviewed.

**Projects, payroll and outputs**
- Narratives are written from the project notes you pasted in, as well as the activity details.
- Payroll uses New Zealand terms: PAYE and employer KiwiSaver.
- The general approval checklist is tucked away once every project is approved.
- The IRD number is formatted, and the carried-forward note on the accounting page appears only
  when there is an amount carried forward.
- Feedstock & Grants shows as started once a feedstock item or grant is entered.

**Other**
- After a top-up, the confirmation page waits for the new balance instead of showing "0 credits".
- First sign-in no longer fails when several screens ask for the account at the same moment.
- British spelling and singular wording ("1 account", "1 activity", "1 section exceeds").

Existing claims are kept. Installed 1.0.2 apps offer the update automatically.

### Which file
| Platform | File |
|---|---|
| macOS, Apple silicon (M1–M4) | `RnD-Tax-Workbench-NZ-1.0.3-mac-arm64.dmg` |
| macOS, Intel | `RnD-Tax-Workbench-NZ-1.0.3-mac-x64.dmg` |
| Windows 10/11, 64-bit | `RnD-Tax-Workbench-NZ-1.0.3-win-x64.exe` |
| Linux, 64-bit | `RnD-Tax-Workbench-NZ-1.0.3-x86_64.AppImage`, the `.deb` or the `.rpm` |

The `.zip`, `.blockmap` and `.yml` files are used by automatic updates and are not needed
for installation.

### Signing
The macOS builds are signed and notarised by Apple. The Windows installer is not yet
code-signed, so Windows SmartScreen shows a warning: choose **More info**, then **Run anyway**.

### Verifying
Checksums are in `SHA256SUMS.txt`. On macOS and Linux: `shasum -a 256 <file>`.
On Windows (PowerShell): `Get-FileHash <file> -Algorithm SHA256`

### Your data
Financial data is stored in a local database on your own machine. Imported files stay there;
only the text an AI-assisted step needs is sent for processing. AI processing takes place in
Australia (Amazon Web Services) when capacity there is available, and otherwise in the United
States through Anthropic's Claude API.

Support: rd@rdinnovate.com
