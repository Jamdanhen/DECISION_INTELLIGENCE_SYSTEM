# GEEKOM IT15 Post-Order Setup and Acceptance Checklist

Status:

```text
Working checklist
```

Date:

```text
2026-07-04
```

Decision case:

```text
Primary Development Workstation
```

Selected system:

[GEEKOM IT15 AI Mini PC, Intel Core Ultra 9 285H, 32 GB RAM, 2 TB SSD, Windows 11 Pro](https://www.geekompc.com/geekom-it15-mini-pc/)

Purchase channel:

```text
GEEKOM direct
```

Purpose:

```text
Protect the order record, preserve return options, validate the delivered
machine, set up the workstation and repository hub, and make an accept-or-return
decision before the return window closes.
```

## 1. Order Confirmation Capture

Record these when available:

- [ ] Final order total.
- [ ] Product subtotal.
- [ ] Discount code applied.
- [ ] Tax.
- [ ] Shipping charge.
- [ ] Payment confirmation.
- [ ] Order number or private receipt location.
- [ ] Order confirmation email location.
- [ ] GEEKOM account order page location, if applicable.
- [ ] Estimated shipping date.
- [ ] Estimated delivery date.
- [ ] Return-window deadline.
- [ ] Warranty start date.

Known order facts:

| Field | Current Record |
| --- | --- |
| Order date | 2026-07-03 |
| Channel | GEEKOM direct |
| Configuration | Core Ultra 9 285H, 32 GB RAM, 2 TB SSD, Windows 11 Pro |
| Coupon/code evidence | GKSS300 confirmed good by user |
| Expected price class | About $1,199 before tax if the code applied |

## 2. Delivery Tracking

- [ ] Record carrier.
- [ ] Record tracking number or private tracking location.
- [ ] Record shipped date.
- [ ] Record delivery estimate.
- [ ] Save shipment confirmation.
- [ ] Watch for signature, porch, or delivery-window requirements.
- [ ] Inspect delivery status on delivery day.
- [ ] Record actual delivery date and time.
- [ ] Photograph package condition before opening if damage is visible.

Escalate if:

- Tracking stalls for more than two business days after shipment.
- Carrier marks delivered but the package is not found.
- Package arrives visibly damaged.
- The delivery date pushes close to the return-window deadline.

## 3. Receipt, Warranty, and Return Protection

- [ ] Save receipt/order confirmation in the project evidence location or a
  clearly named private receipt location.
- [ ] Preserve serial number after unboxing.
- [ ] Preserve packaging, accessories, manuals, and inserts until acceptance.
- [ ] Confirm return policy terms from GEEKOM direct.
- [ ] Record exact return-window deadline.
- [ ] Record warranty term and support contact path.
- [ ] Do not discard shipping box until the accept decision is complete.
- [ ] Keep all account, receipt, serial, and warranty evidence together.

Return-window rule:

```text
No final accept decision until the machine has passed hardware validation,
Windows activation, update stability, sleep/wake behavior, network behavior,
repository workflow setup, and backup/recovery readiness.
```

## 4. Unboxing and Physical Validation

- [ ] Confirm the package contains the expected mini PC.
- [ ] Check case, ports, power adapter, and accessories for damage.
- [ ] Record model number.
- [ ] Record serial number in a private location.
- [ ] Confirm included power adapter matches the device requirement.
- [ ] Confirm HDMI/USB cables or other included accessories, if any.
- [ ] Photograph labels only if useful for warranty evidence.

Hardware configuration validation:

- [ ] CPU shows as Intel Core Ultra 9 285H.
- [ ] RAM shows as 32 GB.
- [ ] Primary SSD shows as approximately 2 TB.
- [ ] Windows edition shows Windows 11 Pro.
- [ ] Wi-Fi adapter is present and working.
- [ ] Bluetooth is present and working.
- [ ] Ethernet port is present and working.
- [ ] USB4 ports are detected and functional.
- [ ] HDMI ports output video.
- [ ] SD card reader is detected, if needed.

## 5. First-Boot Validation

Before installing nonessential software:

- [ ] Boot successfully.
- [ ] Complete Windows setup.
- [ ] Create or sign in with the intended Windows account.
- [ ] Confirm Windows 11 Pro edition.
- [ ] Confirm Windows activation.
- [ ] Confirm local time zone and region.
- [ ] Confirm device name.
- [ ] Confirm BitLocker/device encryption status.
- [ ] Confirm Windows Security has no immediate alerts.
- [ ] Run Windows Update until no critical updates remain.
- [ ] Restart after updates.
- [ ] Confirm no boot errors after updates.

Basic stability checks:

- [ ] Idle for 15-30 minutes without crashes or thermal alarms.
- [ ] Restart cleanly.
- [ ] Sleep and wake cleanly.
- [ ] Shut down and start cleanly.
- [ ] Observe fan noise at idle.
- [ ] Observe fan noise during updates or light workload.
- [ ] Confirm no obvious coil whine, clicking, or repeated disconnect sounds.

## 6. Firmware, Drivers, and Vendor Support

- [ ] Check GEEKOM support page for the IT15.
- [ ] Record current BIOS/firmware version if visible.
- [ ] Check whether BIOS update is recommended or necessary.
- [ ] Update chipset, graphics, Wi-Fi, Bluetooth, and network drivers if needed.
- [ ] Prefer official Windows Update, Intel, Microsoft Store, or GEEKOM support
  sources over random driver mirrors.
- [ ] Restart after driver updates.
- [ ] Re-check Device Manager for unknown devices or warnings.

Pause before BIOS update if:

- Instructions are unclear.
- The update is not clearly for the exact IT15 model.
- Power stability is uncertain.
- The system is otherwise working and the BIOS update only offers minor changes.

## 7. Network Validation

Wi-Fi:

- [ ] Connect to primary Wi-Fi network.
- [ ] Confirm stable connection after reboot.
- [ ] Confirm speed and reliability are acceptable in the actual desk location.
- [ ] Confirm Bluetooth can coexist with Wi-Fi without obvious instability.

Ethernet:

- [ ] Connect Cat 6 or better Ethernet cable if the desk allows it.
- [ ] Confirm wired network link.
- [ ] Confirm internet access over Ethernet.
- [ ] Prefer Ethernet for large repository syncs, backup setup, and major
  downloads when convenient.

Escalate if:

- Wi-Fi drops repeatedly.
- Bluetooth devices disconnect under normal desk use.
- Ethernet link is unstable.
- Network behavior is worse than the current laptop in the same location.

## 8. Monitor and Peripheral Setup

Priority order:

1. Good 27-inch or 32-inch 4K monitor.
2. Ethernet cable and surge protector or compact UPS.
3. External backup drive or SSD.
4. Keyboard and mouse only if existing devices are uncomfortable.
5. USB hub or dock only after an actual port or cabling problem appears.

Display setup:

- [ ] Connect primary monitor through HDMI or USB-C/USB4 to DisplayPort.
- [ ] Confirm expected resolution and refresh rate.
- [ ] Set comfortable Windows scaling.
- [ ] Confirm text readability in browser, VS Code, Office, ChatGPT, and Codex.
- [ ] If using a second display, confirm display arrangement and scaling.

Peripheral checks:

- [ ] Keyboard works reliably.
- [ ] Mouse or trackball works reliably.
- [ ] Webcam works, if needed.
- [ ] Audio output works.
- [ ] Microphone works, if needed.
- [ ] External backup drive or SSD connects reliably.

Do not buy a dock on day one unless the physical setup proves that one is
needed.

## 9. Core Software Setup

Install and validate:

- [ ] Browser of choice.
- [ ] Password manager.
- [ ] Microsoft Office or Microsoft 365 apps.
- [ ] Git.
- [ ] GitHub Desktop.
- [ ] VS Code.
- [ ] Codex.
- [ ] ChatGPT app or browser workflow.
- [ ] Windows Terminal or preferred shell setup.
- [ ] Any required language runtimes for current repositories.

Confirm:

- [ ] Git identity is configured correctly.
- [ ] GitHub authentication works.
- [ ] GitHub Desktop can access the intended repositories.
- [ ] VS Code opens repository folders cleanly.
- [ ] Codex can access the intended workspace path.
- [ ] Office files open normally.
- [ ] Browser profile, bookmarks, and extensions are present as needed.

## 10. Repository Hub Setup

Repository authority rule:

```text
The workstation is the execution environment. Durable project authority remains
with the repository and the owning project files.
```

Recommended setup:

- [ ] Choose the local repository root path on the new workstation.
- [ ] Prefer a C-drive project folder for durable local project work unless a
  project explicitly uses another authority.
- [ ] Keep OneDrive as sync, mirror, or backup only unless explicitly chosen as
  the primary authority for a project.
- [ ] Clone or place active repositories in the chosen local project area.
- [ ] Open the repository hub in VS Code.
- [ ] Open the repository hub in GitHub Desktop.
- [ ] Open the same repository hub in Codex.
- [ ] Confirm file edits, Git status, and branch awareness are consistent.
- [ ] Confirm no accidental duplicate authority is created between C-drive,
  OneDrive, and GitHub.

Repository validation:

- [ ] Pull latest repository state.
- [ ] Confirm no unexpected local changes.
- [ ] Open key Markdown project files.
- [ ] Confirm line endings and encoding appear normal.
- [ ] Run a small non-destructive read/test workflow in Codex.
- [ ] Confirm GitHub push/pull authentication.

## 11. Backup, Sync, and Recovery

Minimum readiness before acceptance:

- [ ] Confirm where active repositories live locally.
- [ ] Confirm GitHub remote exists for each important repository.
- [ ] Confirm OneDrive role, if used, is mirror/backup rather than accidental
  authority.
- [ ] Set up Windows backup or a documented equivalent.
- [ ] Set up local external backup for important non-repository files.
- [ ] Confirm BitLocker/device encryption recovery key is preserved.
- [ ] Confirm Microsoft account recovery and password manager access.
- [ ] Confirm there is a recovery path if the IT15 fails.

Optional but useful:

- [ ] Create a restore point after core setup is stable.
- [ ] Export a list of installed apps.
- [ ] Record setup notes for repeatability.
- [ ] Test restore access for one non-sensitive sample file.

## 12. Productivity Acceptance Test

Run a normal-work simulation:

- [ ] Open ChatGPT and Codex together.
- [ ] Open VS Code with an active repository.
- [ ] Open GitHub Desktop.
- [ ] Open browser research tabs.
- [ ] Open a Microsoft Office document.
- [ ] Edit a Markdown file.
- [ ] Review Git diff.
- [ ] Commit only if the change is intentional.
- [ ] Confirm the machine remains responsive.
- [ ] Confirm fan noise remains acceptable.
- [ ] Confirm monitor scaling remains comfortable.
- [ ] Confirm sleep/wake does not disrupt the workflow.

Pass standard:

```text
The IT15 should feel clearly ready for sustained repository, documentation,
research, Office, ChatGPT, Codex, VS Code, and GitHub work without requiring
immediate hardware upgrades or workaround-heavy setup.
```

## 13. Acceptance Decision

Do not make the final accept decision until these are complete:

- [ ] Final order total recorded.
- [ ] Delivery date recorded.
- [ ] Return-window deadline recorded.
- [ ] Receipt and warranty evidence preserved.
- [ ] Hardware configuration validated.
- [ ] Windows 11 Pro activation confirmed.
- [ ] Updates and drivers stable.
- [ ] Network behavior acceptable.
- [ ] Display and peripherals acceptable.
- [ ] Repository hub setup working.
- [ ] Backup, sync, and recovery path established.
- [ ] Normal-work simulation passed.

Accept if:

- The delivered configuration matches the order.
- No serious hardware, activation, thermal, network, or reliability problem is
  observed.
- Setup reaches productive use without immediate upgrades.
- Repository workflow is stable.
- Backup and recovery are credible.

Return or escalate if:

- Wrong configuration arrives.
- Windows 11 Pro activation fails and support does not quickly resolve it.
- RAM or SSD capacity is wrong.
- USB4, Ethernet, Wi-Fi, display output, or storage behavior is materially
  defective.
- Noise, heat, crashes, or sleep/wake failures undermine daily use.
- Return-window risk is rising before validation is complete.

Acceptance decision record:

| Field | Entry |
| --- | --- |
| Return-window deadline | Unknown |
| Validation status | Not started |
| Setup status | Not started |
| Backup/recovery status | Not started |
| Decision | Pending |
| Confidence | Pending |
| Rationale | Pending |

## 14. Next Follow-Up

Next real follow-up:

```text
Record confirmation, shipping, delivery, return-window, warranty, and final
cost facts as they become available.
```

Next decision point:

```text
After delivery and first-boot validation, decide whether the delivered IT15 is
accepted, needs support escalation, or should be returned before the return
deadline.
```
