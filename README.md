## Spice Safari Admin Dashboard - Frontend Documentation

This documentation outlines the functionalities and components of the Spice Safari admin dashboard, built using Next.js 13.

**Technologies Used:**

* Next.js 13 (Frontend Framework)
* React (JavaScript Library for Building User Interfaces)
* Redux Toolkit (State Management Library)
* Tailwind CSS (Utility-First CSS Framework)
* Chart.js (Library for Creating Charts)

**Project Setup:**

1. **Prerequisites:**
    * Node.js and npm (or yarn) installed on your machine.

2. **Cloning the Repository:**
    ```bash
    git clone https://github.com/your-username/spice-safari-admin.git
    ```

3. **Installing Dependencies:**
    ```bash
    cd spice-safari-admin
    npm install
    ```

4. **Running the Development Server:**
    ```bash
    npm run dev
    ```

    This will start the development server and make the application accessible at http://localhost:3000 by default (port might vary).

**User Interface (UI) Components:**

* **Layout:** The overall structure of the dashboard with navigation, header, and content sections.
* **Sidebar:** Provides navigation options for different functionalities.
* **Header:** Displays application logo, username, and potentially other relevant information.
* **Content Area:** Displays dynamic content based on the selected navigation option. This could include:
    * User Management: View all users, search for specific users, edit user details (potentially including suspension/activation).
    * Order Management: View all orders, filter orders by status (pending, processing, delivered, canceled), view details of individual orders.
    * Product Management: View all products, add new products, edit existing products (including details, images, and prices).
    * Analytics and Reporting: Visualize user statistics, order trends, and other relevant data using charts.

**Data Fetching and State Management:**

* Data fetching is implemented using Next.js data fetching methods and external libraries like Axios.
* Redux Toolkit is used for managing application state across components.


**Styling:**

* Tailwind CSS provides utility classes for building responsive layouts and UI components.


**Future Considerations:**

* Implement unit tests for critical components using a testing framework like Jest.
* Integrate error handling and user feedback mechanisms for a better user experience.

