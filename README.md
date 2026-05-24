# Business Card — Hover Theme Toggle

A sleek, minimal developer business card that switches between **light and dark themes** on hover. Built with HTML & CSS — no JavaScript required.

<img width="1280" height="687" alt="ezgif-8787fdac4b9e6552" src="https://github.com/user-attachments/assets/ad953560-e82c-4f3a-b33b-ea9abeea9e40" />

---

## ✨ Features

- 🌗 **Theme toggle on hover** — smooth transition between light and dark mode
- 📍 Name, username handle, role, and location display
- 📱 Responsive layout for all devices

---

## 🎨 Customization

To make this card your own, update the following in `index.html`:

```html
<img src="your-avatar.png" alt="Avatar" class="avatar" />
<h2 class="name">Your Name</h2>
<p class="handle">@your-handle</p>
<p class="role">Your Role</p>
<p class="location">Your City, Country</p>
```

To adjust theme colors, modify the `:hover` block in `style.css`.

---

## 📦 Usage

No build tools or dependencies needed. Just open `index.html` in any modern browser:

---

## 🧪 Browser Support

Chrome | Firefox | Safari | Edge

---

## 🛠️ How It Works

The theme switch is driven entirely by CSS using the `:hover` pseudo-class on the card container:

```css
/* Light theme (default) */
.card {
  background-color: #ffffff;
  color: #1a1a1a;
  transition: background-color 0.3s ease, color 0.3s ease;
}

/* Dark theme (on hover) */
.card:hover {
  background-color: #111111;
  color: #ffffff;
}
```
