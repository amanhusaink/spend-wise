# SpendWise - Personal Finance Tracker

A responsive finance tracking application built with HTML and Tailwind CSS that allows users to monitor their income, expenses, and savings goals.

## Features

- **Dashboard Summary**: Overview of total balance, income, and expenses
- **Transaction Management**: Add and view income/expense transactions
- **Category Tracking**: Categorize expenses for better financial insights
- **Savings Goals**: Visual progress tracking for financial goals
- **Expense Visualization**: Progress bars showing expense distribution by category
- **Responsive Design**: Works on mobile, tablet, and desktop devices

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Font Awesome (for icons)
- Google Fonts (Inter font family)
- Vanilla JavaScript (for mobile menu toggle)

## How to Run

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process required - it works directly in the browser

## File Structure

```
spend-wise/
├── index.html       # Main HTML file
├── main.css         # Custom CSS styles
└── README.md        # This file
```

## Features Implementation

### Dashboard Summary
- Shows total balance, income, and expenses with color-coded indicators
- Cards have hover effects for better user interaction

### Transaction Management
- Form for adding new transactions with:
  - Transaction type (income/expense)
  - Amount
  - Description
  - Category
  - Date
- Recent transactions table with category badges

### Savings Goals
- Visual progress bars for each savings goal
- Percentage completion indicators

### Expense Categories
- Progress bars showing distribution of expenses by category
- Color-coded for quick visual reference

### Responsive Design
- Mobile-friendly navigation with hamburger menu
- Grid layout that adapts to different screen sizes
- Touch-friendly elements

## Customization

To customize the application:

1. Modify `main.css` to change colors, fonts, or add new styles
2. Update `index.html` to add new features or modify existing ones
3. Add more categories or savings goals by updating the HTML

## Browser Support

This application works in all modern browsers that support:
- Flexbox
- CSS Grid
- ES6 JavaScript

## License

This project is open source and available under the MIT License.