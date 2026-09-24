# Mama Fua - Professional Laundry Services

Mama Fua is a modern, comprehensive Next.js web application built to streamline laundry service operations in Nairobi. It offers a seamless experience for customers to book services, view pricing, and manage their laundry orders, while providing a powerful administrative dashboard for managing operations.

## Features

*   **User-Friendly Booking System:** Customers can easily calculate their laundry costs based on weight and select from various service plans (Basic Wash, Premium Care, Express Service).
*   **Customer Dashboard:** Users can log in to view their booking history, manage their profiles, and track current orders.
*   **Administrative Dashboard:** A comprehensive admin panel featuring statistics charts, booking management, and data export capabilities (CSV).
*   **Authentication & Security:** Secure login system for both customers and administrators with form validation and session handling.
*   **Dark Mode Support:** Built-in theme toggle allowing users to switch between light and dark modes for optimal viewing comfort.
*   **Responsive Design:** Fully responsive layout built with Tailwind CSS, ensuring a great experience on desktop, tablet, and mobile devices.
*   **Keyboard Shortcuts:** Integrated keyboard shortcuts for power users to navigate the application efficiently.
*   **Automated Notifications:** Email templates for booking confirmations and status updates.

## Tech Stack

*   **Framework:** Next.js (React)
*   **Language:** TypeScript
*   **Styling:** Tailwind CSS
*   **State Management:** React Context API (ThemeContext)
*   **Routing:** Next.js App Router

## Project Structure

*   `app/`: Contains the main application routing, pages, and layout.
    *   `admin/`: Administrative dashboard and management interfaces.
    *   `api/`: Backend API routes for authentication, bookings, and plans.
    *   `components/`: Reusable UI components (Toasts, Charts, Loading Skeletons, ThemeToggle).
    *   `contexts/`: Global state management contexts.
    *   `user/`: Customer dashboard and profile pages.
    *   `utils/`: Helper functions for validation, exports, email templates, and keyboard shortcuts.

## Getting Started

### Prerequisites

Ensure you have Node.js (version 20 or higher recommended) installed on your machine.

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/Dr-Rank1/Mama-Fua.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd Mama-Fua
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```
4.  Start the development server:
    ```bash
    npm run dev
    ```
5.  Open your browser and navigate to `http://localhost:3000` to view the application.

## Credits

Developed by Ian Gicheha Mbae (Dr-Rank1).
