# SpendWise Dashboard Shell

This project creates a modern spending dashboard landing page that uses CSS Grid and Flexbox to arrange a responsive financial overview. The layout includes a navigation sidebar, header controls, summary cards, and six budget category cards with realistic static values.

## What is included

### Sidebar navigation
The left sidebar includes a brand area and a set of navigation buttons for Dashboard, Transactions, Budgets, Analytics, Goals, and Settings. It uses Flexbox to arrange the menu items cleanly and visually separate the navigation from the main content.

### Header
The top header displays the Dashboard heading and actions such as a search field, a notification button, and a profile summary. This section uses Flexbox to align the content horizontally while keeping it responsive on smaller screens.

### Summary statistics
Three highlight cards show Net Balance, Income, and Expenses. These cards summarize spend performance and visually hint at positive or negative trends using color-coded values.

### Budget category cards
There are six cards for Food, Transport, Rent, Entertainment, Savings, and Utilities. Each card contains a title, amount spent, descriptive text, a budget indicator, and a progress bar, making the dashboard feel like a real finance tool.

### Styling system
The design uses CSS variables on the `:root` selector to define the brand colors, backgrounds, text colors, and accent tones. These variables are reused across the full dashboard for a consistent theme.

### Responsive behavior
A media query collapses the dashboard to a single-column layout under 768px so the interface remains readable on tablets and mobile devices. The layout also adapts from three columns to two columns before the mobile breakpoint.

### Micro-interactions
The category cards include hover and keyboard focus animations with subtle movement and shadow changes. These interactions last under 250ms to keep the UI smooth and polished.

### Dark mode
The stylesheet includes a dark-mode override using `@media (prefers-color-scheme: dark)` to adjust the root color variables and keep the dashboard comfortable in darker environments.

## Files

- `index.html` — page structure and dashboard content
- `style.css` — design system, layout, responsiveness, and interactions
- `README.md` — project overview and component descriptions
