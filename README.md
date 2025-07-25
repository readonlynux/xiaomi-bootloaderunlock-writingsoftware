# ⚠️ DISCLAIMER
⚠️ This method may void your warranty or cause permanent damage to your device if not done correctly. I take no responsibility for any issues that may occur. Use at your own risk. ⚠️

> ⚠️ **These methods are only valid for Xiaomi (Redmi, POCO etc.) devices.**

# 🛠️ REQUIREMENTS
- one USB cable

# 📲 BIND XIAOMI ACCOUNT WITH DEVICE

> 🔒 Once you bind the device with your Xiaomi account, you can unlock the bootloader.

## ✅ For MIUI users;

### 🛠️ REQUIREMENTS
- 🛠️ Activate developer options from settings
  - `Settings > About phone/device > MIUI (POCO etc.) Version (click 7 times)`
- 🛠️ Go to developer options
  - `Settings > Additional settings > Developer Options`
- ⚠️ Activate `USB debugging` and `OEM unlock`.
  - USB debugging ==> `Settings > Additional settings > Developer Options > USB Debugging`
  - OEM unlock ==> `Settings > Additional settings > Developer Options > OEM unlock`


1. 📲 Go to developer options
2. 👆 Press `Mi Unlock Status`.

Accept the privacy policy. Click on `Add account and device`. If you are not logged in with your Xiaomi account, log in.

> 🚫 HyperOS users: If you're running it on HyperOS and it gives an error, it's related to Xiaomi's new restrictions.

> ⚠️ IMPORTANT NOTE (Only MIUI users): After binding your Xiaomi account to your phone, do not factory reset / sign out of the account. Otherwise the timer will be reset to 168 hours. [Source](https://new.c.mi.com/global/post/101245)

## ✅ For HyperOS users;

### 🛠️ REQUIREMENTS

- Xiaomi community app must be version `5.3.31` or `higher`.
- 🛠️ Activate developer options from settings
  - `Settings > About phone/device > OS Version (click 7 times)`
- 🛠️ Go to developer options
  - `Settings > Additional settings > Developer Options`
- ⚠️ Activate `USB debugging` and `OEM unlock`.
  - USB debugging ==> `Settings > Additional settings > Developer Options > USB Debugging`
  - OEM unlock ==> `Settings > Additional settings > Developer Options > OEM unlock`

Launch the Xiaomi Community app and go to the `Me` section. Sign in with your Xiaomi account. Then, click `Unlock bootloader` Click `Apply for unlocking` (`Xiaomi Community > ME > Unlock Bootloader > Apply for unlocking`).

🚫 Limitation: `Application quota limit reached,please try again after XX/XX (mm/dd) 00:00 (GMT+8)` This error message tells you that your application limit has been reached. You must reapply tomorrow at 12:00 AM (00:00) Chinese time.

❌ `There is no unlock bootloader section.` Set `Xiaomi Community > ME > Set up > Change region` to `Global`.

# 🔓 BOOTLOADER UNLOCK


You need to install a tool to unlock the `bootloader`. [Click here to install the tool](https://en.miui.com/unlock/download_en.html)

- Create a directory and extract it into it.
- Start `miflash_unlock.exe`.
- Log in with your Xiaomi account.
- Connect the Xiaomi device to the computer.
- Press the `Unlock` button

> ⛔ `My device cannot be found?`
> - You can find the solution in this guide. [Press](https://c.mi.com/bd/post/11400/)

All done !

# 🌐 MY SOCIAL MEDIA

[GitHub](https://github.com/readonlynux)

[XDA](https://xdaforums.com/m/readonlynux.13205424/)
