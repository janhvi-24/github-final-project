# Simple Interest Calculator

A **Simple Interest Calculator** is a basic financial tool used to compute the interest earned or paid on a principal amount over a fixed period of time at a constant interest rate.

---

## 📌 Features

* Calculate simple interest quickly and accurately
* User-friendly input (Principal, Rate, Time)
* Lightweight and easy to integrate into any project
* Suitable for educational and financial applications

---

## 🧮 Formula

The simple interest is calculated using the formula:

[
SI = \frac{P \times R \times T}{100}
]

Where:

* **P** = Principal amount (initial investment)
* **R** = Rate of interest (per annum)
* **T** = Time (in years)
* **SI** = Simple Interest

---

## 💡 Example

If:

* Principal = 10,000
* Rate = 5% per annum
* Time = 2 years

Then:

[
SI = \frac{10000 \times 5 \times 2}{100} = 1000
]

**Simple Interest = 1000**

---

## 🚀 How It Works

1. Enter the principal amount
2. Enter the annual interest rate
3. Enter the time period in years
4. Click "Calculate"
5. View the computed simple interest instantly

---

## 🛠️ Sample Implementation (JavaScript)

```javascript
function calculateSimpleInterest(principal, rate, time) {
    return (principal * rate * time) / 100;
}

// Example usage
const SI = calculateSimpleInterest(10000, 5, 2);
console.log("Simple Interest:", SI);
```

---

## 📂 Project Structure (Example)

```
simple-interest-calculator/
│── index.html
│── style.css
│── script.js
│── README.md
```

---

## 📖 Use Cases

* Educational tools for students
* Financial planning basics
* Loan interest estimation
* Banking and accounting demos

---

## ⚠️ Limitations

* Does not account for compound interest
* Assumes constant rate and time period
* Not suitable for complex financial calculations

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

---

## 📬 Contact

For questions or suggestions, feel free to reach out or open an issue.

---

⭐ If you found this useful, consider giving it a star!
