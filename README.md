# FFXIV Random Job Generator

A sleek, web-based tool designed for **Final Fantasy XIV** players to randomly assign jobs based on party compositions. Whether you are running a standard "Dailies Roulette", a chaotic "1 Tank 3 DPS" session, or a chaotic "Free-for-all" party, this tool handles the distribution logic based on your group's specific job unlocks.

## ✨ Features

* **Smart Composition Logic**: Supports standard 4-man (1T/1H/2D), 8-man (2T/2H/4D), and specialized modes like 1T/3D or 1T/2H/5D.
* **Flexible "FREE" Mode**: A dedicated mode for non-standard player counts that automatically assigns roles without strict population checks.
* **Role-Based Visuals**: High-fidelity role and job icons integrated directly into the selection and result interfaces for a native FFXIV feel.
* **Persistent Settings**: Uses `localStorage` to save your group's names and job preferences, ensuring data persists across browser refreshes.
* **Intelligent Allocation**: Features a backtracking algorithm to ensure every player is assigned a job they have actually unlocked and selected.

## 🎮 How to Use

1.  **Select a Composition**: Choose your party type from the dropdown menu. 
2.  **Manage Members**: The list will automatically adjust to the required number of players; you can also manually add or delete members.
3.  **Toggle Jobs**: Click on individual job tags to enable/disable them, or click the **Role Icon/Name** (e.g., "Tank") to toggle the entire category.
4.  **Generate**: Click "Roll" to see your assigned jobs! The results will display each player's name alongside their assigned job and role icon.

## 🙏 Acknowledgments & Credits

This project uses assets and inspiration from the following sources:

* **Job & Role Icons**: Special thanks to **[xivapi/classjob-icons](https://github.com/xivapi/classjob-icons)** for the FFXIV icons. This project credits their repository for the visual assets.
* **Square Enix**: All Final Fantasy XIV assets are property of Square Enix Co., Ltd.

---

*Note: This tool is for personal use and party organization. It does not interact with the FFXIV game client.*