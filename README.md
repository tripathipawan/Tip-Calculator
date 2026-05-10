# 🧾 Tip Calculator

A simple browser-based tip calculator that computes both the tip amount and total bill from user inputs — built with HTML, CSS, and JavaScript.

---

## 📌 Overview

This web app takes 2 inputs from the user — the bill amount and the desired tip percentage — and instantly calculates the tip amount and the final total bill on button click. The results appear in 2 disabled, read-only output fields so they are clearly distinguishable from the inputs. The app is built with no frameworks and runs entirely in the browser by opening `Index.html`.

---

## ✨ Features

- **Bill Amount Input (`#billAmount`)** — A text input where the user enters the total bill amount before tip.
- **Tip Percentage Input (`#tipPersentage`)** — A text input where the user manually types the desired tip percentage (e.g., `10`, `15`, `20`).
- **Tip Amount Output (`#tipAmount`)** — A disabled, read-only text input that displays the calculated tip amount after clicking the Calculate button. Being disabled prevents accidental edits while keeping the value visible.
- **Total Bill Output (`#totalBill`)** — A disabled, read-only text input that shows the final total (bill + tip) after calculation.
- **Calculate Button** — A single button that calls `tipcalcy()` on click, which reads the 2 input values, runs the tip calculation, and writes the results into the 2 output fields.
- **Responsive Design** — CSS media queries ensure the layout works cleanly across desktop, tablet, and mobile screen sizes.
- **No Dependencies** — Pure HTML, CSS, and JavaScript. Open `Index.html` directly in any browser.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | 4-field layout — 2 user inputs (bill, tip %), 2 disabled outputs (tip amount, total) |
| CSS3 | Input styling, layout, responsive media queries |
| JavaScript (ES6+) | `tipcalcy()` function — reads inputs, calculates tip and total, updates output fields |

---

## 📁 Project Structure

```
Tip-Calculator/
├── Index.html    # Main HTML — bill input, tip % input, tip amount output, total output, Calculate button
├── Style.css     # All styling — form layout, input fields, button, responsive breakpoints
├── Script.js     # Calculation logic — tipcalcy() function, tip formula, DOM output update
└── README.md     # Project documentation
```

---

## 🚀 Getting Started

No setup needed. Just 3 steps:

**1. Clone the repository**
```bash
git clone https://github.com/tripathipawan/Tip-Calculator.git
```

**2. Navigate into the project folder**
```bash
cd Tip-Calculator
```

**3. Open in browser**
```
Open Index.html directly in any modern browser
— or use VS Code Live Server
```

---

## 🧭 How to Use

1. Open the app in your browser.
2. Enter the **bill amount** in the first input field (e.g., `500`).
3. Enter the **tip percentage** in the second input field (e.g., `15`).
4. Click the **Calculate** button.
5. The **Tip Amount** field shows how much tip to pay.
6. The **Total Billed** field shows the full amount (bill + tip).

---

## 🧠 Calculation Logic

| Field | Formula |
|---|---|
| Tip Amount | `(Bill Amount × Tip Percentage) / 100` |
| Total Billed | `Bill Amount + Tip Amount` |

Both output fields (`#tipAmount` and `#totalBill`) are `disabled` to show results clearly without allowing manual edits.

---

## 🌱 What I Learned

- Reading multiple input field values simultaneously using `document.getElementById`
- Performing arithmetic calculations on user-provided string values (with proper type conversion)
- Displaying computed results into `disabled` input fields to separate inputs from outputs visually
- Using an inline `onclick` attribute to call a named JavaScript function directly from HTML
- Building a focused, single-purpose utility with minimal code

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -m 'Add: your feature description'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Pawan Tripathi**
- GitHub: [@tripathipawan](https://github.com/tripathipawan)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
