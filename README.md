# 🍙 Onigiri E-Card

A simple, lightweight interactive 3D e-card template built with pure HTML, CSS, and JavaScript. Click the envelope to slide open the card, and click the pages to flip through them with clean 3D animations.

**Vibe coded with the help of Gemini :)**

### ✨ Screenshots
<img width="440" height="300" alt="image" src="https://github.com/user-attachments/assets/a3f6b319-6fd7-4459-8c96-4ae17c2c58ba" />
<img width="440" height="300" alt="image" src="https://github.com/user-attachments/assets/bde532c9-69f5-4e96-8371-01b5cccd7c14" />


### 🚀 How to Customize
Open `index.html` in any text editor to modify the card:

1. Resize the Card
Change the size of the entire project uniformly by adjusting the `--scale` value in the CSS:

```
:root {
    --scale: 0.80; /* 1.0 is full size, 0.50 is half size, etc. */
}
```

2. Edit the Content
Update the text variables at the top of the `<script>` tag.

```
const PAGE_1_CONTENT = `Write your message here.`
```

3. Add or Remove Pages
Add or duplicate objects inside the `PAGES_DATA` array to expand your card. The layout engine will handle the 3D book math automatically:

```
{
    type: "standard",
    date: "Optional Date",
    to: "Dear Onigiri,",
    content: PAGE_1_CONTENT,
    signoff: "Love, <br> goldberl"
}
```

### 📄 License
MIT License. Free to use and modify for any personal or commercial greetings!
