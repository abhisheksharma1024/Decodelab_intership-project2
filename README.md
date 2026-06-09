
## ✅ Features

✔️ Semantic HTML structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)  
✔️ Sticky responsive navigation bar  
✔️ Hamburger menu with slide-in overlay for mobile  
✔️ Hero section with code block visual  
✔️ Stats strip layout  
✔️ Article grid — featured card + sidebar cards  
✔️ Topics section with auto-fit grid  
✔️ Newsletter signup section  
✔️ Responsive footer with multi-column layout  
✔️ Accessible touch targets (minimum 44×44px)  
✔️ WCAG compliant — no `user-scalable=no`  

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Styling and layout |
| CSS Grid | Macro page layout |
| Flexbox | Component-level layout |
| Media Queries | Responsive breakpoints |
| clamp() | Fluid typography |

---

## 📐 Concepts Used

- Mobile-first CSS architecture
- CSS Grid (`repeat(auto-fit, minmax())`)
- Flexbox for navigation and components
- Fluid typography with `clamp()`
- CSS custom properties (variables)
- Viewport meta tag
- Responsive breakpoints at 600px and 900px
- Hamburger navigation for mobile
- Semantic HTML tags
- Accessible touch targets

---

## 📏 Breakpoints

| Breakpoint | Target |
|---|---|
| Default | Mobile (< 600px) |
| 600px+ | Tablet layout enhancements |
| 900px+ | Full desktop layout |

---

## 📸 Screenshots

<img width="1898" height="912" alt="image" src="https://github.com/user-attachments/assets/69b4f79c-bc05-43ac-beb2-2a72de36cdac" />


![Homepage](screenshot.png)

---

## 🧠 What I Learned

- Mobile-first is a mindset, not just a media query order
- `grid-template-columns: repeat(auto-fit, minmax())` handles most layouts without extra breakpoints
- `clamp()` eliminates hard jumps in font sizes across screen sizes
- The viewport meta tag is non-negotiable — without it, media queries don't work on real devices
- Breakpoints should be set where content breaks, not where devices change

---

## 👤 Author

Abhishek Sharma 


---

## 📄 License

This project is open source and free to use.

