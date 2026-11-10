Desktop application for preparing New Zealand Research and Development Tax Incentive claims.

**Download page: https://blog.rdinnovate.com/workbench-nz/**

### What's new in 1.0.1

- **Actual hours only.** Employee costs are apportioned on each employee's own hours worked. The
  app no longer assumes a 40-hour, 52-week year when hours are missing: the employee is flagged
  and their costs are left out until the hours are entered on Payroll.
- **New Zealand throughout.** Remaining Australian wording, references and currency in screens,
  exports and AI instructions now use New Zealand terms (Inland Revenue, IRD number, subpart LY, NZD).
- **Timesheet template** rewritten for New Zealand: blank rows for actual hours worked.
- **Newer AI models.** AI-assisted steps now use Claude Opus 5.5 and Sonnet 5.5.
- **Where AI steps are processed** is stated in Settings (see "Your data" below).

Existing claims are kept. Installed 1.0.0 apps offer the update automatically.

### Which file
| Platform | File |
|---|---|
| macOS, Apple silicon (M1–M4) | `RnD-Tax-Workbench-NZ-1.0.1-mac-arm64.dmg` |
| macOS, Intel | `RnD-Tax-Workbench-NZ-1.0.1-mac-x64.dmg` |
| Windows 10/11, 64-bit | `RnD-Tax-Workbench-NZ-1.0.1-win-x64.exe` |
| Linux, 64-bit | `RnD-Tax-Workbench-NZ-1.0.1-x86_64.AppImage`, the `.deb` or the `.rpm` |

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
