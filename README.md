

# Toggle App - Random Number Generator

## Project Description

This Toggle App is a React based web application that demonstrates the creation of reusable components, data passing with props, and conditional rendering. The app generates random numbers between 1 and 100 and displays them in three reusable `Card` components. Each `Card` shows the number and a label ("High" if > 50, "Low" if ≤ 50) using a ternary operator for conditional rendering. The project uses modern JavaScript (arrow functions with implicit returns) and CSS for styling.

This project fulfills the requirements of a lab focused on React fundamentals, showcasing component based architecture, props, and dynamic rendering.


## Project Structure

```plaintext
toggle_app/
├── public/
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── App.js           # Main component with random number generator and Card rendering
│   ├── Card.js          # Reusable Card component with conditional rendering
│   ├── App.css          # Styles for the app
│   ├── index.js
│   └── index.css
├── package.json         # Project dependencies and scripts
├── README.md            
└── node_modules/
```

- **App.js**: Defines the `App` component, which uses an arrow function (`randNum`) to generate random numbers and renders three `Card` components with `num` props.
- **Card.js**: A functional component that accepts a `num` prop and conditionally renders "High" (> 50) or "Low" (≤ 50) using a ternary operator.
- **App.css**: Contains styles for centering the app, styling cards, and setting a clean background.

## Key Features

- **Reusable Components**: The `Card` component is reused three times with different random numbers.
- **Props**: Random numbers are passed from the `App` component to `Card` components via the `num` prop.
- **Conditional Rendering**: Each `Card` uses a ternary operator to display "High" or "Low" based on the number.
- **Arrow Functions**: The `randNum` function uses an arrow function with implicit return for random number generation.
- **Styling**: CSS ensures a responsive layout with centered cards.

## Key Takeaways

- **React Components**: The app demonstrates building React applications with modular, reusable components (`App` and `Card`).
- **Props**: Data is passed from the parent (`App`) to child (`Card`) components using props.
- **Arrow Functions**: The `randNum` function showcases concise JavaScript with implicit returns.
- **Conditional Rendering**: The ternary operator in `Card` dynamically displays content based on prop values.
- **Reusable Design**: The `Card` component can display any number, making it highly reusable.

