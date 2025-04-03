# 📸 Camera Capture Prototype

This is a minimal HTML/JavaScript prototype to test capturing images using the device camera directly in the browser. It uses **AlpineJS** for reactivity and **TailwindCSS** for styling — both loaded via CDN. No backend is required.

---

## ✅ Features

- "Take Picture" button opens the **native camera** on supported mobile devices.
- After capturing an image, a **preview** is shown.
- Users can choose to **retake** or **(fake) save** the image.
- Built with:
  - [TailwindCSS CDN](https://tailwindcss.com/docs/installation/play-cdn)
  - [AlpineJS CDN](https://alpinejs.dev/start-here)

---

## 📱 Compatibility

Tested on:

- ✅ iPhone (Safari, iOS 18)
- ✅ iPad Pro (Safari, iPadOS 18)
- ✅ Android (Chrome & Firefox – device-dependent)

> ⚠️ iOS **requires Safari** for camera access via file inputs. Other browsers may not trigger the camera.

---

## 🚀 Quick Preview via Netlify

You can test this live by uploading the `index.html` file to [Netlify Drop](https://app.netlify.com/drop).

---

## 📂 File Structure

```text
.
├── index.html      # Full AlpineJS + Tailwind prototype
└── README.md       # You're here!
```

---

## 📦 Coming Later

This is a frontend-only prototype. In a later stage, the captured image can be sent to a **Laravel 12 backend** for storage.

---

## 🛠️ License

MIT – free to use and modify.