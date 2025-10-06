# Chef-Menu

Chef Christoffel’s Menu App

Author: Olwethu Tshabalala

Date: 6 September 2025

Project Overview

Chef Christoffel’s Menu App is a mobile application developed with React Native and TypeScript to help Chef Christoffel, a private chef, manage his personalized menus efficiently. Each evening brings a different menu, so the app allows the chef to quickly add, remove, and display dishes in a visually appealing and client-ready format.

The app is designed to work on both Android and iOS, prioritizing usability, flexibility, and a clean design. Since it does not use permanent storage, menu data exists only for the session, allowing quick updates and resets.

Key Features

Home Screen

Central hub showing the current menu, total number of dishes, and average price.

Navigation options to add new dishes.

Displays the restaurant’s logo for branding consistency.

Add Menu Item Screen

Allows entering details such as name, description, course type, and price.

Course type is selected via a dropdown with predefined options: Starters, Mains, Desserts, Beverages.

Newly added items automatically appear in the Menu List screen.

Menu List Screen

Displays all selected dishes with real-time updates on total cost.

Items can be removed as needed.

Final Menu Screen

Presents a polished, client-ready menu with item names, prices, and total estimated cost.

Consistent headers, breadcrumb navigation, and functional buttons across all screens.

Technical Implementation

Navigation: React Navigation manages screen transitions smoothly.

State Management: Temporary data handled via React’s useState hook. Data is passed between screens through navigation parameters.

Components: Core React Native components like <View>, <Text>, <Button>, <TextInput>, and <FlatList> are used to build the interface.

Dropdown Selection: The Picker component is used for course type selection.

Styling: Applied via React Native’s StyleSheet API for consistent appearance across devices.

Project Structure

Screens: Separate files for Home, Add Menu Item, Menu List, and Final Menu screens.

Assets: Contains images, logos, and other media files.

Types: types.ts defines menu item shapes and screen navigation types, enhancing code reliability and reducing errors.
