# Discord Desktop Refresh Fixer (BETA)

A theme that aims to improve and undo some of the less popular changes introduced in Discord’s new Desktop Visual Refresh.

### ⚠️ Please Note
- This is a **BETA**, so it’s still a work in progress.
- Some parts may be broken or incomplete.
- Updates and improvements are planned over time.

### 💾 How to Use
You can install and use the theme with any custom Discord client, like [BetterDiscord](https://betterdiscord.app/) or [Vencord](https://vencord.dev/).

### ⚠️ Windows Users & Custom Title Bars

If you're on **Windows** or your client uses the **Discord’s built-in title bar** instead of the system one, make sure to **remove or comment out** the following lines in your CSS file:

```css
bar_c38106, .bar_c38106 *, .title_c38106, .title_c38106 * {
    overflow: hidden !important;
    height: 0 !important;
}

.base_c48ade {
    margin-top: -37px;
}
```

### 💡 Why?
Not everyone loves the new UI. This theme is for those who prefer the old layout and want to revert some of Discord’s recent changes, such as:
- The user bar overlapping both the channels list and server list.
- The bulky top bar that takes up too much space.
- And more tweaks coming soon!

---

### ✅ To-Do
- Revert server icons (guilds bar) to the classic circular style.
- Restore original icon sizes for a less cramped look.
- Fix UI bugs and inconsistencies.

---

### 🤝 Contributing
Contributions are welcome! Whether it's fixing a bug, improving styles, or suggesting changes.
Feel free to open an issue or submit a pull request.
