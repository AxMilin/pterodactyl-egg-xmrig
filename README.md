# 🦖 Pterodactyl Egg: XMRig ⛏️

This is a custom Pterodactyl egg for deploying the XMRig CPU miner on your panel. It allows you to easily spin up and manage mining containers via the Pterodactyl interface.

## 📂 Egg File

- Location: `eggs/egg-xm-rig.json` 📁

## 🛠 Features

- ⚙️ Supports custom mining pool configuration
- 🎛️ CPU affinity and priority flags
- 🔧 Environment variable setup for wallet, pool, and other options

## 🧪 Tested On

- 🐉 Pterodactyl Panel v1.11+
- 🐳 Docker images with necessary dependencies

## 📊 Benchmarks

Tested with:

- 🖥️ Intel Core i3-6100 (2 cores, 4 threads)
- 🧠 2048 MB RAM allocation
- ⚙️ CPU Limit: 200%
- ⛏️ Avg Hashrate: ~221.7 H/s (60s)
- 🎯 Max Hashrate: 234.0 H/s

| CPU # | Affinity | 10s H/s | 60s H/s |
|-------|----------|---------|---------|
| 0     | 0        | 38.97   | 57.39   |
| 1     | 1        | 63.28   | 62.57   |
| 2     | 2        | 60.76   | 54.48   |
| 3     | 3        | 60.35   | 47.29   |
| —     | —        | 223.4   | 221.7   |

🎱 Pool Results:

- ✅ Accepted: 3 (100%)
- ⏳ Avg Result Time: 258.4s
- 🎲 Difficulty: 100001

## 🚀 Installation

1. 🔐 Go to your Pterodactyl panel admin dashboard.
2. 🐣 Navigate to `Nest` → `Import Egg`.
3. 📤 Upload the `egg-xm-rig.json` file or paste the raw JSON.
4. 🗂 Assign it to a nest (or create a new one).
5. ⚡ Create a new server using this egg.

## 🔗 Resources

- 🐉 Pterodactyl GitHub: [https://github.com/pterodactyl/panel](https://github.com/pterodactyl/panel)
- ⛏️ XMRig GitHub: [https://github.com/xmrig/xmrig](https://github.com/xmrig/xmrig)

## 💰 Donate Wallets

- 🟣 Solana: `Dm1Di7eec24Yug4UYUpz3BBY84be3V8hERJfWA3QkFoo`
- ₿ Bitcoin: `bc1qvfa423wxkqm7mw7m8mg2rpqqa7plx8rflwy8nd`
- 🔷 Sui: `0x47f39de09455952effefed73be231ca10ba9a8aa5dccfc376c291573c11d2c6a`

## 📎 Notes

- ⚠️ Make sure the host node has proper CPU resources.
- 📚 Intended for educational and personal use only. Always follow legal and ethical guidelines.

## 📄 License

This project is licensed under the MIT License.

---

Made with 💻 by [AxMilin](https://axmilin.in.th/) ✌️

---

## 🏷️ Tags

`pterodactyl` `egg` `xmrig` `mining` `cryptocurrency` `cpu-mining` `docker` `automation` `opensource` `monero` `crypto` `miner` `server` `linux` `devops` `blockchain` `pool` `hashrate` `performance`
