# My Car Website

## Description
My Car Website is an interactive web application that provides users with information about various car models. It allows users to filter car models based on brand, type, and year. The website also includes a light/dark mode toggle, a FAQ section, and a subscription form for users to stay updated with the latest news.

## Key Features
- **Light/Dark Mode Toggle**: Users can switch between light and dark themes. The chosen theme preference is saved in local storage, ensuring a consistent experience across sessions.
  
- **Car Model Filtering**: Users can filter car models by brand, type, and year using a user-friendly form.

- **Frequently Asked Questions (FAQ)**: The website provides a FAQ section where users can click to reveal answers to common questions about cars.

- **Dynamic Date and Time Display**: The current date and time are displayed and updated in real-time.

- **Subscription Popup**: Users can subscribe to a newsletter by entering their email and name. Basic validation is applied to ensure required fields are filled.

## User Preferences Management
- The website uses **localStorage** to manage user preferences, such as the selected theme (light or dark mode). 
- Upon loading the website, the user's theme preference is retrieved from localStorage, allowing for a personalized experience that persists across page reloads.
- Users can toggle the theme using a button, which updates the theme in real-time and saves the new preference.

## Getting Started
To run this project locally:
1. Clone the repository:
   ```bash
   git clone <repository-url>
