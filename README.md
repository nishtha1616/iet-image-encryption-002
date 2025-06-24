# iet-image-encryption-002
# 🔐 Image Encryption Tool – Pixel Scrambler

This project is a simple and interactive web tool that allows you to **encrypt and decrypt images** using a custom pixel manipulation algorithm. It includes both **RGB value shifting** and **horizontal pixel swapping** for enhanced scrambling.

Built using **HTML, CSS, and JavaScript** – no backend, just run in any browser!

---

## 🚀 Features

- 🖼 Upload any image (JPG, PNG, etc.)
- 🔐 Encrypt the image (RGB value shift + pixel position swap)
- 🔓 Decrypt multiple times to get back original
- ⬇️ Download encrypted or decrypted image
- 🎨 Simple, modern, and responsive design
- 💡 Perfect for learning how image data works in the browser

---

## 🧠 How It Works

### Encryption:
1. Each pixel's R, G, B values are shifted using a `KEY` (e.g., `+50`)
2. Pixels are **mirrored** horizontally row-by-row
3. Multiple encryption layers are supported

### Decryption:
1. Mirrors the pixels again to original positions
2. Subtracts the `KEY` to restore original colors
3. Repeat as many times as it was encrypted

---

## 🛠 Technologies Used

- HTML5 Canvas API
- JavaScript ES6
- CSS3 (Neon theme + responsive layout)

---

## 📦 How to Use

1. **Clone or Download** the repository:
   git clone https://github.com/nishtha1616/iet-image-encryption-002.git
   image-encryotion-tool.html
