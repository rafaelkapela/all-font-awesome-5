# All Font Awesome 5 Icons Picker - Font Awesome 5 icons in Arrays

This project provides a **dynamic modal** that allows users to browse and select from **all Font Awesome 5 icons**, organized into **Brand**, **Regular**, and **Solid** icon families, with the corresponding `fab`, `far`, and `fas` prefixes. This solution simplifies icon selection for web projects and integrates seamlessly into HTML forms.

## Key Features

- **Complete Icon Set**: Displays the full collection of Font Awesome 5 icons, categorized by icon family (`fab`, `far`, `fas`).
- **Icons Stored in Arrays**: All Font Awesome icons are stored in easy-to-access JavaScript arrays (`brandIcons`, `regularIcons`, and `solidIcons`) for efficient loading and management.
- **Dynamic Icon Picker**: Automatically generates a **grid of icons** inside a modal using JavaScript, without needing external CSS.
- **User-Friendly UI**: Hover and click effects for better user interaction. Icons change color on hover, making it easier to identify selected icons.
- **No External CSS**: All styles are applied via JavaScript, so no need to manage additional CSS files.
- **Efficient Icon Selection**: Clicking an icon automatically inserts its class name into an input field for use in your project.

## How It Works

The icons are organized into JavaScript arrays named `brandIcons`, `regularIcons`, and `solidIcons`. Each array contains the class names for **all Font Awesome 5 icons** in their respective families. When the modal is triggered, the script dynamically generates a grid of icons from these arrays. Users can click on an icon, and the corresponding class name is inserted into a form input field.

### Example of the Icons Array:

```javascript
const solidIcons = [
  'fa-address-book', 
  'fa-500px', 
  'fa-accessible-icon', 
  'fa-adjust', 
  // more icon class names
];
