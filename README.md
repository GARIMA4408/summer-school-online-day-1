#  Personal Portfolio Website - Garima Sharma

This is a simple HTML-based portfolio website created as part of an HTML Fundamentals assignment.

---

## Files Included

- `portfolio.html` – Main portfolio page
- `about.html` – About me page
- `contact.html` – Contact form page
- `garima.jpg` – Profile image
- `README.md` – Project documentation

---

## HTML Elements Used

- `<!DOCTYPE html>` – Declares HTML5 document type
- `<html>` – Root element of the page
- `<head>` – Contains meta information, title
- `<title>` – Sets page title in the browser tab
- `<body>` – Holds the content shown on the page

### Content & Structure:
- `<h1>` to `<h6>` – Heading tags for content hierarchy
- `<p>` – Paragraph text
- `<img>` – Displays an image
- `<ul>` / `<ol>` / `<li>` – Lists used for skills and education
- `<table>` – Displays project/work experience
- `<nav>` / `<a>` – Navigation menu and links between pages

### Form Elements (`contact.html`):
- `<form>` – Main tag wrapping the contact form
- `<input type="text">` – User's name input
- `<input type="email">` – Email input with built-in validation
- `<input type="tel">` – Accepts phone number input with validation
- `<textarea>` – Allows longer user message
- `<input type="checkbox">` – For preferred contact method
- `<input type="radio">` – For selecting a single inquiry type
- `<input type="date">` – Choose a contact date
- `<input type="range">` – For urgency/priority slider
- `<select>` – Dropdown for selecting country

---

## Why These Input Types?

- **Text**: For name input
- **Email**: Ensures correct email format
- **Tel**: Allows numeric phone input
- **Checkbox**: Supports selecting multiple contact preferences
- **Radio**: Useful when only one option must be chosen
- **Textarea**: For longer text like user messages
- **Date**: Lets users choose a specific contact date
- **Range**: Visual urgency selector (1 to 10 scale)
- **Select**: Makes it easier to pick from preset choices (like country)

---

## 🔗 Navigation Structure

The navigation menu helps users move between pages:

- `Home (portfolio.html)`
- `About (about.html)`
- `Contact (contact.html)`

### Example:
```html
<nav>
  <a href="portfolio.html">Home</a>
  <a href="about.html">About</a>
  <a href="contact.html">Contact</a>
</nav>
