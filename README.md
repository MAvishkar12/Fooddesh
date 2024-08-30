
Link : https://fooddesh.netlify.app


https://github.com/user-attachments/assets/3a736551-666a-4f20-b0ec-1b372b3f3eb9



# Food-Delivery React App

This is a React-based food-delivery web application built using `npx create-react-app`. The app showcases a user interface for browsing food items, adding them to a cart, and placing an order. It fetches real-time data from third-party APIs using the **Cross-Origin Resource Sharing (CORS) proxy** via a browser extension.

## Features

- **React Router**: Handles routing for different pages of the application.
- **React Redux Toolkit**: Manages global state for the cart and other UI states.
- **Material-UI**: Provides a responsive and stylish design for the UI components.
- **CORS Proxy Extension**: Used for fetching real-time data from third-party APIs securely.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/en/download/) (v14 or above)
- [npm](https://www.npmjs.com/get-npm) (comes with Node.js)
- A browser with a CORS proxy extension like [Moesif CORS](https://chrome.google.com/webstore/detail/moesif-origin-cors-change/anepbdekljkcmpnpbdkkdkceokbfljlm) or [Allow CORS](https://chrome.google.com/webstore/detail/allow-cors-access-control/hnkcfpcejkafcihlgbojoidoihckciin).

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/food-delivery-app.git
   cd food-delivery-app
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run the application:**

   ```bash
   npm start
   ```

   The app should now be running on [http://localhost:3000](http://localhost:3000).

### Using the CORS Proxy

To fetch real-time data from third-party APIs:

1. Install a CORS proxy browser extension.
2. Enable the extension and configure it if necessary.
3. The app should now be able to fetch data from external sources.

### Project Structure

```
├── public
├── src
│   ├── components
│   ├── Utils 
│   |
│   │   
│   │   
│   ├── index.css
│   ├── index.js
│   └── ...
├── package.json
|__ package-lock.json
└── README.md
```

- **components/**: Reusable React components like buttons, cards, etc.
- **pages/**: Page components such as Home, Cart, etc.
- **redux/**: Contains the Redux store and slices for state management.

### Key Technologies

- **React.js**: Frontend library for building user interfaces.
- **React Router**: For navigation between different pages.
- **React Redux Toolkit**: For state management.
- **Material-UI**: For consistent and responsive UI design.
- **CORS Proxy**: To securely fetch real-time data from external APIs.

### Available Scripts

- `npm start`: Runs the app in development mode.
- `npm build`: Builds the app for production.
- `npm test`: Runs tests.
- `npm eject`: Ejects the app configuration (not recommended unless necessary).



