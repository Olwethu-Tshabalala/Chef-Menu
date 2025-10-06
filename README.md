# Chef-Menu
Chef Christoffel’s Menu App

Author: Olwethu Tshabalala
Date: 6 September 2025

Project Overview

Chef Christoffel’s Menu App is a mobile application developed with React Native and TypeScript to help Chef Christoffel, a private chef, manage personalized menus efficiently.

Since each evening may feature a different menu, the app allows the chef to:

Quickly add new dishes

Remove outdated items

Display a polished, client-ready menu

The app is cross-platform, working on both Android and iOS, and emphasizes usability, flexibility, and clean design. Data exists only for the session, allowing quick updates and resets.

Key Features
1. Home Screen

Central hub displaying the current menu, total dishes, and average price

Navigation to add new dishes

Consistent branding with the restaurant logo

2. Add Menu Item Screen

Enter dish details: name, description, course type, price

Predefined course categories via dropdown: Starters, Mains, Desserts, Beverages

Automatically updates the Menu List Screen

3. Menu List Screen

Review all selected dishes

Remove items as needed

Real-time calculation of total menu cost

4. Final Menu Screen

Presents a client-ready menu with item names, prices, and total cost

Consistent headers, breadcrumb navigation, and functional buttons

Technical Implementation

Navigation: Smooth transitions via React Navigation

State Management: Temporary data handled with React useState

Component Usage: <View>, <Text>, <Button>, <TextInput>, <FlatList>

Dropdown Selection: Picker component for course type

Styling: StyleSheet API ensures consistent UI across devices

Project Structure

Screens: Dedicated files for Home, Add Menu Item, Menu List, and Final Menu

Assets: Images, logos, and media files

Types: types.ts defines data shapes and screen navigation types, improving code reliability
