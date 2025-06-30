# Pricing Cards UI – Tailwind CSS + GSAP

A responsive and animated pricing cards component built with **Tailwind CSS** and **GSAP 3**.

## 🔧 Tech Stack

- **HTML5**
- **Tailwind CSS**
- **JavaScript (GSAP 3)**
- **RemixIcon** for icons

## 🚀 Features

- Four pricing cards: Starter, Premium, Unlimited, and Enterprise
- Smooth entrance animations using `gsap.fromTo()`
- Reusable design system with custom CSS variables (`:root`)
- Styled buttons, dividers, and color-coded feature tags
- Clean layout with responsive structure (max-width container)
```
## 📂 Project Structure

tailwind/
├── js/
│ └── main.js # GSAP animations
├── src/
│ ├── input.css # Tailwind input styles
│ └── output.css # Compiled Tailwind CSS
├── index.html # Main HTML file
├── package.json # NPM config with Tailwind dependencies
├── README.md # Project description
```

## ⚙️ Setup & Run

```bash
# 1. Clone the repository
git clone https://github.com/VladislavProhorov123/Thailwind_1.git

# 2. Navigate into the project folder
cd Thailwind_1

# 3. Install dependencies
npm install

# 4. Start Tailwind in watch mode
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

Then open index.html in your browser to see the result.

👨‍💻 Author
Created by Vladivlav Prohorov