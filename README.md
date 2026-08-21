# CSV Log Viewer — Downloads

Official downloads for **CSV Log Viewer** by Johnson Tuning, LLC — a Windows
desktop datalog analysis tool built for tuners: stacked time plots, compare
overlays, a heat-mapped all-channels grid, VE-style tables, VE and MAF
correction workbenches, a virtual dyno with factory vehicle profiles, a
drag-race worksheet, an event finder, saved workspaces, and a searchable
offline help guide.

## Download

**[⬇ Download the latest version](https://github.com/johnsontuning/CSV_Log_Viewer_Public_Releases/releases/latest)**

Grab the `CSV-Log-Viewer-X.Y.Z.exe` installer from the latest release and run
it. Windows 10/11, 64-bit. The installer can optionally make CSV Log Viewer
the default program for `.csv` datalogs, so logs open with a double-click.

> **"Windows protected your PC"?** Windows SmartScreen shows this for newer
> software. Click **More info → Run anyway**. The installer is published only
> through this page.

## Supported logs

Over 30 tuning platforms are recognised, and the format is worked out from
what is actually inside the file — there is nothing to pick when you open a
log, and two formats sharing an extension are told apart on content.

**Open natively, with no export step:**

| Platform | Files |
| --- | --- |
| HP Tuners | `.hpl` — both VCM Scanner and MPVI4 standalone (TDN) logging |
| Holley EFI | `.dl`, `.dlz` |
| Hondata | `.kdl` (KPro), `.fpdl` (FlashPro) |
| Link ECU | `.llgx` (PCLink, both generations) |
| Emtron | `.elf` (EMTune) |
| Haltech | `.dl` (NSP container) |

**Read from the tuning software's own CSV export:**

Cobb · EcuTek · MoTeC · **Cummins INSITE** · EvoScan · RomRaider (Subaru
open-source) · MHD · JB4 · MaxxECU · VehiCal · VF Tuner · UpRev · DS1 (VAG
MED17) · JTCANLink · RaceME · SCT · VCDS · ABIT AKM · Januar · ProEFI ·
SPTronic · EZ LYNK · FuelTech · bootmod3 · EFILive — plus the CSV exports of
every natively-supported platform above.

Anything else with a header row and numeric columns still opens as a generic
CSV, taking its channel names, units and time axis from the file's own header.

Channels that report a state rather than a number — knock and fail-safe
flags, limit reasons, gear and mode channels, aftertreatment states — read as
their documented meanings at the cursor and in tables, not as raw numbers.

## Trial and licensing

- Every install starts a **free 14-day trial** with all features unlocked.
- To purchase a license: open **Help → License** in the app, click **Copy**
  next to your machine code, and email it to
  **corbin@johnsontuning.com** with your name/shop name. You'll receive a
  license file that activates the app permanently on that computer.
- Licenses are perpetual — **all updates are free**.

## Updates

The app checks this page on launch and downloads updates automatically in the
background — when one is ready, a green **"Update ready — restart to apply"**
chip appears in the menu bar. No need to come back here after the first
install.

Every release's notes are listed with the download, and the full history is in
the app under **Help → Release Notes**.

## Support

Questions, bug reports, or channel/log-format requests:
**corbin@johnsontuning.com**

Support for a new log format usually only needs one example log — if your
tool is not listed above, send one over.

---

*This repository hosts release artifacts only. CSV Log Viewer is © Johnson
Tuning, LLC — see the EULA shown during installation.*
