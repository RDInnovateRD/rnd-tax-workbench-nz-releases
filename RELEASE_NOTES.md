Desktop application for preparing New Zealand Research and Development Tax Incentive claims.

**Download page: https://blog.rdinnovate.com/workbench-nz/**

### First release

- Claims under subpart LY of the Income Tax Act 2007: eligible R&D expenditure, the 15% tax credit,
  and the figures for the R&D supplementary return.
- Imports the general ledger, trial balance, payroll (including KiwiSaver) and timesheets.
- Contractors, apportionment of shared costs, and the exclusions the Act lists.
- General Approval documents exported to Word.
- AI-assisted steps (ledger classification, narratives, checks) are charged in credits; the cost is
  shown before anything is spent.
- Every tab saves as you type.

### Which file
| Platform | File |
|---|---|
| macOS, Apple silicon (M1–M4) | `RnD-Tax-Workbench-NZ-1.0.0-mac-arm64.dmg` |
| macOS, Intel | `RnD-Tax-Workbench-NZ-1.0.0-mac-x64.dmg` |
| Windows 10/11, 64-bit | `RnD-Tax-Workbench-NZ-1.0.0-win-x64.exe` |
| Linux, 64-bit | `RnD-Tax-Workbench-NZ-1.0.0-x86_64.AppImage` or the `.deb` |

The `.zip`, `.blockmap` and `.yml` files are used by automatic updates and are not needed
for installation.

### Signing
The macOS builds are signed and notarised by Apple. The Windows installer is not yet
code-signed, so Windows SmartScreen shows a warning: choose **More info**, then **Run anyway**.

### Verifying
Checksums are in `SHA256SUMS.txt`. On macOS and Linux: `shasum -a 256 <file>`.
On Windows (PowerShell): `Get-FileHash <file> -Algorithm SHA256`

### Your data
Financial data is stored in a local database on your own machine. Imported files
are not uploaded.

Support: rd@rdinnovate.com
