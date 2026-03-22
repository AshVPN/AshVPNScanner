<div align="center">

```
███╗   ███╗██████╗  █████╗ ███████╗██╗  ██╗██╗   ██╗██████╗ ███╗   ██╗
████╗ ████║██╔══██╗██╔══██╗██╔════╝██║  ██║██║   ██║██╔══██╗████╗  ██║
██╔████╔██║██████╔╝███████║███████╗███████║██║   ██║██████╔╝██╔██╗ ██║
██║╚██╔╝██║██╔══██╗██╔══██║╚════██║██╔══██║╚██╗ ██╔╝██╔═══╝ ██║╚██╗██║
██║ ╚═╝ ██║██║  ██║██║  ██║███████║██║  ██║ ╚████╔╝ ██║     ██║ ╚████║
╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝  ╚═══╝  ╚═╝     ╚═╝  ╚═══╝
```

# ⚡ V2Ray Config Tester

**Test 1800+ configs in minutes. Find the fastest ones. No BS.**

[![Telegram](https://img.shields.io/badge/Telegram-@WHITEIPCHECK__Bot-blue?style=flat&logo=telegram)](https://t.me/WHITEIPCHECK_Bot)
[![GitHub](https://img.shields.io/badge/GitHub-AshVPN-black?style=flat&logo=github)](https://github.com/AshVPN)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat&logo=windows)]()
[![Free](https://img.shields.io/badge/Price-FREE-green?style=flat)]()

🇮🇷 **Built for Iran. Works everywhere.**

</div>

---

## 🔥 What is this?

You have 1000+ V2Ray configs. Most are dead. Some are slow. **A few are gold.**

This tool finds the gold ones — automatically.

- ✅ Tests **real HTTP delay** through xray (not fake ping)
- ✅ Tests **TCP connection** to every server
- ✅ Downloads **fresh configs from GitHub** every time
- ✅ Supports **VLESS · VMESS · TROJAN · Shadowsocks**
- ✅ Run **multiple windows at once** — they split the work automatically
- ✅ **One `.exe` file** — no install, no Python, nothing else needed

---

## 📥 Download

> **[⬇ Download Latest Release]([../../releases/latest](https://github.com/AshVPN/AshVPNScanner/releases/latest))**

Just download `AshVPNScanner_V1.exe` — that's it.

---

## 🚀 How to Use

### Step 1 — Run it
Open PowerShell in the folder where you saved the `.exe`:
```
.\MRASHVPN_Tester.exe
```
> ⚠️ First run? It extracts xray and creates folders automatically. Takes 3 seconds.

---

### Step 2 — Add your configs *(optional)*
The app auto-downloads fresh configs from GitHub on every start.

Want to add your own? Two ways:
- Click **📂 Add Files** → pick any `.txt` config file
- Or just drop `.txt` files into the `Configs` folder next to the `.exe`

---

### Step 3 — Press ▶ START
The app will:
1. Download fresh configs from GitHub
2. Test every config with **real HTTP delay** (3 rounds each)
3. Show you live results — green ✅ = working, yellow 🟡 = TCP only, red ❌ = dead
4. Save best configs to `working_configs_bot1.txt` — sorted fastest first

---

### Step 4 — Copy your best config
Results tab shows all working configs. Click **📋 Copy** or **💾 Save**.

---

## ⚡ Run Multiple Windows = Faster Results

This is where it gets powerful.

Open **2, 3, or 4 windows** at the same time:

```
Window 1 → Bot ID: 1 → tests Sub1.txt, Sub2.txt, Sub3.txt, Sub4.txt
Window 2 → Bot ID: 2 → tests Sub5.txt, Sub6.txt, Sub7.txt, Sub8.txt
Window 3 → Bot ID: 3 → tests Sub9.txt, Sub10.txt, Sub11.txt, Sub12.txt
```

They **auto-detect each other**. No setup. No conflicts. No duplicate testing.
Results saved as `working_configs_bot1.txt`, `bot2.txt`, `bot3.txt` separately.

> 💡 4 windows = 4x faster. Simple math.

---

## ⚙️ Settings

| Setting | Default | What it does |
|---|---|---|
| Parallel Workers | 20 | How many configs tested at same time |
| Test Rounds | 3 | Times each config is tested (keeps best) |
| HTTP Timeout | 6s | Max wait for real delay test |
| TCP Timeout | 3s | Max wait for TCP ping |
| Files Per Bot | 4 | How many files each window claims |

---

## 📁 Folder Structure

After first run:
```
📁 YourFolder\
    ├── AshVPNScanner_v1.exe       ← the app
    ├── xray.exe                  ← auto-extracted
    ├── geoip.dat                 ← auto-extracted
    ├── geosite.dat               ← auto-extracted
    ├── 📁 Configs\               ← config files go here
    ├── 📁 Temp\                  ← auto-managed, don't touch
    └── working_configs_bot1.txt  ← your results
```

---

## ❓ FAQ

**Q: Do I need Python or anything else?**
A: No. One `.exe`. That's it.

**Q: Why does Windows Defender flag it?**
A: It's a PyInstaller app — Defender is suspicious of compiled Python. Click **More info → Run anyway**. The source code is right here if you want to check.

**Q: Where do results go?**
A: Same folder as the `.exe` — `working_configs_bot1.txt`

**Q: It says "all files claimed by other bots"?**
A: Another window already took all the files. Either close one window or add more `.txt` files to the `Configs` folder.

**Q: Can I add my own config sources?**
A: Yes — Settings tab → Remote Sources → click **+ Add New Source**

---

## 🛡️ Privacy

- No data is sent to us. Ever.
- Configs are tested locally using xray-core on your machine.
- Source code is in this repo. Read it yourself.

---

## 📌 Contact

| | |
|---|---|
| Telegram | [@WHITEIPCHECK_Bot](https://t.me/WHITEIPCHECK_Bot) |
| GitHub | [github.com/AshVPN](https://github.com/AshVPN) |

---

<div align="center">

**If this saved you time — give it a ⭐ star. It helps others find it.**

Made with ❤️ for the people of Iran 🇮🇷

</div>
