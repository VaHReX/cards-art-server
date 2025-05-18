<h1 align="center">🃏 Cards Art Server - Evolution YGO</h1>

<p align="center">
  <strong>Official repository for managing custom cards in the Evolution YGO project.</strong><br>
  Submit and play your own cards across compatible platforms!
</p>

---

## 📦 Custom Card Submission Guidelines

To contribute custom cards, follow these structure and rules:

### 📁 Required Files

- `cards.cdb` → A **unique** SQLite file containing your custom card IDs.
- `script/` → A folder containing all your `.lua` scripts for each card.

```
cards.cdb
script/
├── c10202101.lua
└── c10202102.lua
```

### 🆔 ID Rules

- The `cards.cdb` file must have a **unique filename**.
- ❌ Do **not** name your file `cards.cdb`. Choose a different, identifiable name (e.g., `yourname_cards.cdb`).

- All card IDs **must start with `102021xx`** (e.g., `10202101`, `10202102`, etc.).
- Avoid conflicts by checking the [`ids.txt`](./ids.txt) file before submitting.
- ⚠️ **Users are responsible for making sure their IDs are unique.**

---

## 🖥️ Play Your Custom Cards on Our Server

You can use your custom cards directly in the Evolution YGO game server using the `art` command:

> 🔗 **Server Info**
>
> - 🌐 **Host:** `server.evolutionygo.com`  
> - 🔌 **Port:** `7711`  
> - 💬 **Command:** `art`

### ✅ Supported Platforms

- 📱 **MDPro3**  
- 📱 **YGO Mobile**  
- 🖥️ **EDOPro (LAN Mode Only)**

---

## 🚀 How to Contribute

1. 🍴 Fork this repository.
2. 📂 Add your `cards.cdb` and `script/` folder to the **root** of the repo.
3. 🔍 Check `ids.txt` to avoid using duplicate IDs.
4. ✅ Create a Pull Request and wait for review.

---

## 💡 Best Practices

- ✅ Use consistent naming: `c<ID>.lua`.
- ♻️ Keep updates backward-compatible.
- ❓ Not sure about an ID? [Open an Issue](https://github.com/evolutionygo/cards-art-server/issues) first.

---

## 📬 Contact & Community

Need help or want to join the discussion?  
Join us on **Discord**: [discord.gg/cTSJV8CsNV](https://discord.gg/cTSJV8CsNV)  
Or [open an issue](https://github.com/evolutionygo/cards-art-server/issues) right here on GitHub.

---

## 📄 License

This repository is maintained by the community and provided for **non-commercial use** within the Evolution YGO environment.