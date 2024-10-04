# ReactPizza

**ReactPizza** is a comprehensive pizza ordering application built with React and Redux that allows users to browse a menu, manage their cart, and place orders seamlessly, all while utilizing geolocation features for personalized address input.

## Features

- **User-Friendly Menu**: Users can view a dynamic menu of pizzas with detailed descriptions and pricing.
- **Geolocation Integration**: Automatically fetches and displays the user's address based on their current geolocation.
- **Shopping Cart Management**: Users can add, remove, and update quantities of items in their cart.
- **Order Creation**: Facilitates the process of placing orders through a user-friendly form.
- **Responsive Design**: Optimized for an excellent user experience across various devices.
- **Tailwind CSS**: Utilizes Tailwind CSS for styling, enabling rapid UI development with a utility-first approach.

## Components

The project is organized into the following React components:

- **App**: The main component that integrates routing and layout for the application.
- **Home**: The landing page with introductory content.
- **Menu**: Displays the list of available pizzas, leveraging an API to fetch data.
- **Cart**: Shows items added to the cart and allows users to manage them.
- **CreateUser**: A form for users to enter their names before ordering.
- **Order**: Displays the details of a user's order and allows updates.
- **Error**: Displays error messages when issues arise during data fetching.
- **Button**: A reusable button component for various actions.
- **LinkButton**: A link styled as a button for navigation.

## How It Works

1. Users start on the **Home** page and are prompted to enter their name using the **CreateUser** component.
2. Upon entering their name, they are redirected to the **Menu** component, where they can browse and add pizzas to their cart.
3. Users can view their cart, adjust quantities, and remove items as needed.
4. When ready to order, users can proceed to the order form, where their geolocation is used to suggest their address.
5. Finally, users can submit their order, which is processed and saved using a REST API.

## Technologies Used

- **React**: For building the user interface and managing component state.
- **Redux Toolkit**: For global state management, particularly for user data and cart items.
- **React Router**: For handling navigation and routing between components.
- **Tailwind CSS**: For styling, enabling a responsive and visually appealing design with utility classes.
- **CSS**: For styling and ensuring responsive design.
- **JavaScript (ES6+)**: Core language for application logic and functionality.
- **Geolocation API**: For obtaining the user's current location.

## Screenshots

![image](https://github.com/user-attachments/assets/99f5f8b7-52d0-4d0c-b459-e869e31fb2f1)
![image](https://github.com/user-attachments/assets/67c7f896-992c-406b-9fd3-c47ba57a67bf)
![image](https://github.com/user-attachments/assets/2d67d2e9-329d-49bc-bf00-58ac1e3b8bcc)
![image](https://github.com/user-attachments/assets/0ba3201a-fb58-4b60-b1ba-f5a303e1688c)

## Installation

To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ReactPizza.git
   ```
2. **Install the dependencies**:
   ```bash
   npm install
   ```
3. **Start the application**:
   ```bash
   npm dev
   ```

   The app will be available at `http://localhost:5173`.
