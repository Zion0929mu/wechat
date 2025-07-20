# WeChat Web – 微信网页版静态界面克隆

A pixel-perfect static replica of the WeChat desktop interface, built using **pure HTML and CSS**. This project demonstrates responsive layout techniques, icon integration, and visual fidelity, all without JavaScript or external frameworks.

![WeChat UI Preview](./assets/wechat.jpg)

## 💡 Project Overview

This project replicates the WeChat desktop interface (1112×784px) using semantic HTML and handcrafted CSS. It showcases my front-end skills in layout, design implementation, and precision styling—ideal for demonstrating baseline capabilities in UI development.

---

## ✨ Features

### 1. Left Navigation Bar
- Vertical icon list (Chat, Contacts, Collection, etc.)
- User avatar and notification red dot
- Precise spacing and alignment using `flex` layout and pixel-level CSS

### 2. Middle Chat List Panel
- Search bar with icon and add button
- Static message list with avatar, name, preview, and timestamp
- Visual design adapted to mimic real WeChat interface

### 3. Right Chat Content Panel
- Chat bubbles and user avatars
- Timestamp display and horizontal separators
- Bottom input area with functional icons and input box

---

## 🎨 Design System

| Element      | Value |
|--------------|-------|
| **Primary Color** | `#1AAD19` (WeChat Green) |
| **Background**    | `#F7F7F7` |
| **Font Color**    | `#333333` |
| **Border Color**  | `#E5E5E5` |
| **Font Family**   | `-apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', sans-serif` |
| **Font Size**     | `12px` to `16px` depending on importance |
| **Spacing Units** | 8px / 12px / 16px / 24px / 32px |

---

## 🧰 Tools & Resources

- **VSCode** – Code editing
- **Chrome DevTools** – Layout inspection
- **[Photopea](https://www.photopea.com/)** – Color sampling from mockup
- **[IconFont.cn](https://www.iconfont.cn/)** – Icon downloads

---

## 📁 Project Structure
```
wechat-web/
├── index.html # Main HTML layout
├── css/
│ └── style.css # Core stylesheet
├── assets/
│ ├── wechat.jpg # Original design reference
│ └── icons/ # All icons used in the layout
└── README_cn.md # Project documentation Chinese
└── README_en.md # Project documentation English
```