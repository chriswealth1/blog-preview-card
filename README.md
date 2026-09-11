# Frontend Mentor - Blog Preview Card 

A clean, modern, and fully **responsive blog preview card component** 
built as a web development practice project. This card adaptively scales down for mobile screens, with a black background box-shadow effect, slick hover and focus states 
for the title link and implementation of flexbox to struturing the layout.
---

###  Features

* **Fully Responsive:** Uses a fluid layout (`width: 100%; max-width: 350px;`) so the card fits perfectly on small mobile viewports without overflowing.
* **Perfect Centering:** Built with CSS Flexbox to keep the card perfectly centered horizontally and vertically on any viewport size.
* **Neobrutalism Design:** Features a bold aesthetic with thick black borders and a distinct `8px` solid block box-shadow.
* **Interactive Hover States:** Includes visual feedback that changes the article title color when a user hovers or focuses on the link.

---

### File Structure

```text
 # Semantic HTML5 document structure
 # Custom CSS layout, typography, and styling
 # Visual graphic assets
    ├── illustration-article.svg
    └── image-avatar.webp
```

---

###  Built With

* Semantic **HTML5** markup
* Custom **CSS3** properties (Flexbox, custom borders, and 3D-effect box shadows)
* Google Fonts (**Figtree**)

---
### Aligning items 

using display flex to center my user image and the title side by side

```css flex
.content-profile {
    display: flex;          /* Activates Flexbox layout */
    align-items: center;    /* Vertically aligns the avatar image and text perfectly in the middle */
    gap: 10px;              /* Creates an even 10px space between the avatar and the text */
    margin: 20px 0 10px 0;  /* Adds spacing above and below the profile row */
}
```

###  Author

* GitHub - [@chriswealth1](https://github.com)
