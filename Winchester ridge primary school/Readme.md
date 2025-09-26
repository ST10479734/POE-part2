#Part 1

#part 2 
### `home page.html`
- The main landing page.
- Contains a welcome message and a brief history of the school.
- Includes a header, navigation bar, and footer.
- Uses a **background image** positioned at the **bottom** of the page.

### `about us.html`
- Provides details about the school's **mission**, **vision**, **values**, and **21st-century education approach**.

### `admissions.html`
- Outlines the admissions process and provides a downloadable PDF form.
- Steps for applying are clearly listed with required documents.

### `gallery.html`
- Displays a horizontal image slider of school photos.
- Showcases life at the school including activities and events.

### `contact us.html`
- Contains the school's contact information including:
  - Address
  - Phone number
  - Email
  - Operating hours

---

## Styling

- All pages use a shared external CSS file located at `CSS/stylesheet.css`.
- Each page includes a **header** with a gradient background and a **footer** with a consistent purple theme (`#e295fa`).
- Font Awesome icons are linked via CDN and can be used for visual enhancements.

---

## Background Image Behavior

- Most pages use the background image `Images/school.jpg`.
- The image is set to:
  - `background-repeat: no-repeat;`
  - `background-size: contain;`
  - `background-position: bottom;`



---

## 📥 PDF Download Note

On the **admissions** page, there's a download link for a PDF form:

```html
<a href="file:///C:/Users/.../Winchester%20Ridge%20Primary%20School.pdf">