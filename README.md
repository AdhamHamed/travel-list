# Travel-List
 A simple React application where users can add items they want to pack for their travel, along with the quantity, and view the list of items with checkboxes to mark them as packed. This project demonstrates the core skills required to build a basic interactive UI in React, including action handling, state management, and controlled components.

## Features
- Add items to the packing list.
- Specify the quantity of each item.
- Mark items as packed using checkboxes.
- Dynamic rendering of the packing list.

## Skills Demonstrated
1. State Management (useState)
The application uses React's useState hook to manage the state of the travel list and the input fields.
State is used to store the list of items and their quantities, as well as to control the input fields (item name and quantity).
2. Handling Input and Forms
Controlled components are used for the input fields to allow the user to input the item name and quantity.
The onChange event handler updates the component state, ensuring the form values are reflected in the UI.
3. Action Handling (onClick, onSubmit)
The app handles user interactions through events such as onClick for buttons.
When the "Add Item" button is clicked, the input values are added to the list, and the form is reset.
4. Rendering Lists (Dynamic UI)
The list of items is rendered dynamically using map(). Each list item includes a checkbox for the user to mark it as packed.
5. Component Structure
The application is structured in functional components, allowing for a clean separation of concerns and easy scalability.
6. Conditional Rendering
Based on the packing status (packed or unpacked), different UI elements are rendered conditionally (e.g., changing styles for packed items).
7. Basic Styling (Optional)
Basic CSS is applied to enhance the user interface and improve user experience.

## Usage
- Enter the name of the item you want to pack.
- Enter the quantity of the item.
- Click "Add Item" to add it to the packing list.
- Check off items as you pack them.
