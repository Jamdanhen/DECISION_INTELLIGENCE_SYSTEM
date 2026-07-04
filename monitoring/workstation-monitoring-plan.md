# Workstation Monitoring Plan

Status:

```text
Market scan retired for selected workstation; delivery and acceptance monitoring active
```

Decision case:

```text
Primary Development Workstation for the Crucible Registry ecosystem
```

## Default Cadence

Do not continue weekly market scans for this specific workstation purchase.

The GEEKOM IT15 order has been placed, paid for, and processed. The active
monitoring lane is now delivery, setup, validation, and return-window
protection.

Prior automation:

```text
Weekly Workstation Procurement Report
```

Disposition:

```text
Deleted from Codex app on 2026-07-04 after the user confirmed the purchase is
made, confirmed, and going through.
```

Deleted automations:

- `monitor-geekom-it15-32gb-2tb-price`
- `weekly-workstation-procurement-report`

## Delivery and Acceptance Triggers

Refresh the order follow-up record when:

- shipment confirmation appears
- tracking number or carrier becomes available
- delivery estimate changes materially
- the device is delivered
- warranty or return-window terms become available
- first-boot validation begins
- a hardware, activation, driver, network, sleep/wake, thermal, or reliability
  issue appears
- the return-window deadline is approaching

## Market Scan Closure

The specific workstation market scan is closed.

Do not run further candidate, price, promotion, or alternative-market checks for
this purchase.

If the shipped unit has a delivery, support, warranty, configuration, or
hardware problem, handle that as order follow-up and acceptance-window support,
not as renewed shopping.

## Final Acceptance Trigger

Before the device is accepted, validate:

- delivered configuration
- Windows 11 Pro activation
- driver and firmware stability
- Wi-Fi, Ethernet, Bluetooth, HDMI, USB4, and storage behavior
- sleep/wake behavior
- idle and light-work thermals/noise
- repository hub setup
- backup, sync, and recovery readiness
- normal productivity workflow with ChatGPT, Codex, VS Code, GitHub, Markdown
  repositories, and Microsoft Office

## Retired Watch List

The prior candidate watch list is no longer active for this specific purchase:

- GEEKOM A7 Max
- GMKtec NucBox M6 Ultra
- HP EliteDesk 8 Mini G1a
- MINISFORUM MS-A2
- GEEKOM A9 Max
- MINISFORUM MS-01
- Dell business micro desktop options
- ASUS NUC business mini desktop options
