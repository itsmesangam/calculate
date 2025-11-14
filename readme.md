#### Calculator Project

A collection of web-based calculators built with HTML, CSS, and JavaScript. Features modern UI design with dark mode support.

## 📋 Table of Contents

- [Features](#features)
- [Calculators](#calculators)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)

## ✨ Features

- **Modern UI Design**: Beautiful gradient backgrounds and smooth animations
- **Dark Mode**: Toggle between light and dark themes with persistent preferences
- **Responsive Layout**: Works seamlessly on desktop and mobile devices
- **Input Validation**: Comprehensive error handling for invalid inputs
- **Keyboard Support**: Press Enter key in any input field to calculate

## 🧮 Calculators

### 1. Addition Calculator (`index.html`)

A simple calculator that adds three numbers together.

**Features:**
- Three input fields for numbers
- Real-time addition calculation
- Displays the sum of all three numbers
- Supports decimal numbers

### 2. Simple Interest Calculator (`si.html`)

Calculate simple interest and total amount based on principal, rate, and time.

**Features:**
- Calculate Simple Interest using the formula: **SI = (P × R × T) / 100**
- Displays both Simple Interest and Total Amount (Principal + Interest)
- Formula information displayed at the bottom
- Input fields for:
  - Principal Amount (₹)
  - Rate of Interest (% per annum)
  - Time (in years)

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or installations required

### Installation

1. Clone or download this repository
2. Navigate to the project directory
3. Open the HTML files in your web browser

```bash
# Simply open the HTML files in your browser
open index.html      # For Addition Calculator
open si.html         # For Simple Interest Calculator
```

## 📖 Usage

### Addition Calculator

1. Open `index.html` in your web browser
2. Enter the first number in the first textbox
3. Enter the second number in the second textbox
4. Enter the third number in the third textbox
5. Click the "Add" button or press Enter in any input field
6. View the result displayed below

**Example:**
- First Number: `10`
- Second Number: `20`
- Third Number: `30`
- Result: `60`

### Simple Interest Calculator

1. Open `si.html` in your web browser
2. Enter the Principal Amount (₹)
3. Enter the Rate of Interest (% per annum)
4. Enter the Time Period (in years)
5. Click the "Calculate" button or press Enter in any input field
6. View the Simple Interest and Total Amount displayed

**Example:**
- Principal: `10000`
- Rate: `5`
- Time: `2` years
- Simple Interest: `₹1000.00`
- Total Amount: `₹11000.00`

### Dark Mode

Both calculators support dark mode:

1. Click the **🌙 Dark** button in the top-right corner
2. The theme will switch to dark mode
3. Click **☀️ Light** to switch back to light mode
4. Your preference is automatically saved and will be restored on next visit

## 📁 Project Structure

```
calculate/
│
├── index.html          # Addition Calculator (3 numbers)
├── si.html            # Simple Interest Calculator
├── README.md          # Project documentation
└── readme.md          # Legacy readme file
```

## 🛠️ Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling, animations, and responsive design
- **JavaScript**: Calculation logic and dark mode functionality
- **LocalStorage API**: Persistent dark mode preference storage

## 🎨 Design Features

- Gradient backgrounds with smooth color transitions
- Card-based UI with shadow effects
- Hover effects on interactive elements
- Smooth transitions between light and dark themes
- Clean, modern typography
- Intuitive user interface

## 📝 Notes

- All calculations are performed client-side in the browser
- No data is sent to external servers
- Dark mode preferences are stored locally in your browser
- Supports decimal numbers for precise calculations

## 🔧 Customization

You can customize the calculators by:

- Modifying color schemes in the CSS `<style>` section
- Adjusting container sizes and padding
- Changing gradient colors for backgrounds
- Updating button styles and hover effects

## 📄 License

This project is open source and available for personal and educational use.

## 👤 Author

Calculator Project - Simple web-based calculators

---

**Enjoy calculating! 🎉**
