# NailBase User Guide

*[Русский](user-guide.ru.md) · [Українська](user-guide.uk.md)*

NailBase is an offline app for nail masters and salons: clients, visits,
reporting. All data is stored on your device only, unless you explicitly
enable Google Drive sync (see "Backup" below).

## 1. Master profile and business card

Settings → **Master profile**: name, phone, address, working hours (you can
switch to "24/7" instead of specific hours). This data is used on your
business card and in the text of referral invitations sent to clients.

Settings → **Business card** — a shareable card with your contact details
(the "Share" button opens the system share sheet — messenger, email, etc.).
Logo, accent color, font and slogan are customized on the same screen, but
customization is a Pro feature (see section 6); name/phone/address/hours on
the card are always taken from the master profile and can be edited for
free.

## 2. Clients and visits — the basic flow

1. On the clients screen, add a new client (name, phone — you can import
   these from your phone's contacts with one tap) or open an existing one.
2. On the client's card, tap "Add visit" and pick services — their duration
   and total price are calculated automatically.
3. The visit appears on the day dial as a colored sector; its status
   (upcoming, completed, no-show, voided) is set manually after the visit —
   the app never auto-marks a visit "Completed" just because its time has
   passed.
4. If a new visit's time overlaps an existing one, the app warns you before
   saving, showing whose visit it is and by how many minutes it overlaps.

## 3. Referral system — inviting a client

On a client's card there's a **"Show referral QR code"** button. This is
that specific client's personal QR code: a new client who scans it is
automatically marked as having been referred by them. The **"Share"**
button sends both the QR image and ready-made invitation text (with your
contact details from the master profile) through the system share sheet —
for example, straight into the client's messenger.

Referral tiers (how many friends need to be referred for a discount) and
the loyalty bonus for repeat visits are configured under Settings →
**Referral program** — this is a free feature, available without Pro.

## 4. Backup

Settings → **Data**:

- **Create a backup** — bundles the database and client/business-card
  photos into a single ZIP file and opens the system "Share" sheet: save it
  wherever you want (cloud storage, computer, a message to yourself). The
  file is never uploaded automatically — only through your own choice.
- **Restore from backup** — pick a previously created ZIP file. **Warning:**
  this fully replaces all current data in the app and cannot be undone —
  the app asks for confirmation before restoring.

Separately, **Sync with Google Drive**: automatic background backup to a
private folder in your own Google account (not visible in your regular
Drive file list, not accessible to us or anyone else). Off by default. This
is a Pro feature.

## 5. Report for the salon owner

If you work in a salon and need to show your revenue/commission owed to the
owner, the **"Report for the salon"** screen (available from the "Reports"
section) calculates income for a chosen period and the amount due based on
the salon's commission percentage, and turns this into a QR code ("Generate
QR").

Delivery is hand-to-hand, no internet required: show the QR code on your
screen, and the salon owner scans it with **their own** phone in NailBase
(the "Master reports" screen, "Salon owner" role, scan button) — this adds
the report to their list of reports across all masters, with no file
transfer and no server involved.

## 6. Free vs Pro

The Free plan is limited to **150 clients and 600 visits** — enough for a
small independent master's full workflow; once you hit the limit, the app
will offer to upgrade to Pro. Pro additionally includes:

- advanced statistics (revenue chart, breakdown by service category, top
  referrers);
- business card customization (logo, accent color, font);
- Google Drive sync and client reminders — in development, coming later.

**Important:** in the current version, buying Pro inside the app is not yet
technically wired up (billing is still being set up) — the "Buy" button on
the Pro screen currently shows "Not available for purchase yet". This guide
will be updated once purchasing goes live.

## 7. Changing language and currency

Settings → **General**: **Language** — leave it on your device's "System
language" or pick one of the supported interface languages manually;
**Currency** — choose from the full ISO 4217 list by code or name (with
search), or enter a custom symbol via "Other currency" if yours isn't
listed. Both switch instantly, with no app restart.

---

*This document describes the functionality of the current version of
NailBase and may be updated as the app evolves.*
