# Discord Desktop Refresh Fixer (BETA)

A theme that aims to improve and undo some of the less popular changes introduced in Discord’s new Desktop Visual Refresh.

### ⚠️ Please Note
- This is a **BETA**, so it’s still a work in progress.
- Some parts may be broken or incomplete.
- Updates and improvements are planned over time.

### 💾 How to Use
You can install and use the theme with any custom Discord client, like [BetterDiscord](https://betterdiscord.app/) or [Vencord](https://vencord.dev/).

### 💡 Why?
Not everyone loves the new UI. This theme is for those who prefer the old layout and want to revert some of Discord’s recent changes, such as:
- The user bar overlapping both the channels list and server list.
- Removing Discord's built-in title bar for users that prefers system's one.
- And more tweaks coming soon!

### ⚠️ Windows Users & Custom Title Bars

If you're on **Windows** and/or your client uses the **Discord’s built-in title bar** instead of the system one, make sure to **remove or comment out** the following lines in your CSS file:

```css
bar_c38106, .bar_c38106 *, .title_c38106, .title_c38106 * {
    overflow: hidden !important;
    height: 0 !important;
}

.base_c48ade {
    margin-top: -37px;
}
```

### 📜 Credits
> **Note:** The following individuals are not direct contributors to this project. They're credited because parts of their code were used within this project.

- **Guild Icons:** [scattagain](https://github.com/scattagain)
- **Message Timestamp Revert:** [Relevant Message](https://discord.com/channels/1015060230222131221/1028106818368589824/1354458308714696816) from the [Vencord Server](https://discord.gg/vencord)

---

### 🤝 Contributing
Contributions are welcome! Whether it's fixing a bug, improving styles, or suggesting changes.
Feel free to open an issue or submit a pull request.
