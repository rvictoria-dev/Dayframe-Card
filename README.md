# 🖼️ Dayframe Card

### ₊⊹ About

Is a small personal space built around the idea of turning everyday details into something worth keeping.
Designed with a quiet, nostalgic feel, inspired by the charm of ordinary moments, a little frame for every everyday life.

<img width="1102" height="721" alt="image" src="https://github.com/user-attachments/assets/a8d3da74-66cf-4d15-a522-c65c6fc27821" />

---

### ★ Features

- Integration with the **Inter** font via Google Fonts for better readability.
- Use of soft shadows (`box-shadow`) to add depth to the card on the screen.
- Top image structured with `aspect-ratio (16/9)`, ensuring it doesn’t distort on different screens.
- Circular profile photo with a custom border using advanced CSS properties (`outline-offset`).
- Quick tabs (Home, About, Rules, Interests) organized horizontally using a subtle divider.
- Extensive use of *Flexbox* to ensure the card is perfectly centered on the page.

---

### ⚙️ Tech Stack

- **HTML5**
- **CSS3**
- **Google Fonts:** Integrate the modern **Inter** font directly into the project using `preconnect` links to optimize loading.

---

### 🖿 Project structure

```
Dayframe-Card/
├── Assets/
├── Styles.css
├── index.html
└── README.md
```

---

### .ᐟ.ᐟ How It Works

- **Global Centering (`body`):**
The project uses a global container that occupies 100% of the height of the viewed screen (`min-height: 100vh`). Using the **Flexbox** axis system, the main card is automatically centered both horizontally and vertically, regardless of the size of the monitor or screen.
- **The Main Container (`.profile-card`):**
The entire interface is encapsulated within a semantic `<article>` tag. It has fixed safety dimensions (`500px` wide by `450px` tall), creating a physical frame with smooth edges and a drop shadow on the background.
- **Visual Block Layout**
*The card’s internal structure reads and renders elements from top to bottom in three main blocks:*
1. **Top (Visual):** The banner image maintains the perfect 16:9 aspect ratio (`aspect-ratio`), behaving like a real camera photo that fills the entire width without distorting the pixels.
2. **Center (Identity and Search):** The `<header>` aligns the avatar and the search form on the same horizontal line using `display: flex`. The search bar uses the `flex: 1` property to dynamically expand and occupy all remaining space next to the profile photo.
3. **Footer (Navigation):** The `<nav>` tag inserts a top divider using a styled border and centers the page navigation buttons (`HOME`, `ABOUT`, `RULES`, `INTERESTS`).
