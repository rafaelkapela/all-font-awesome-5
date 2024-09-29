# All Font Awesome 5 Icons Picker

This project provides a **dynamic modal** that allows users to browse and select from **all Font Awesome 5 icons**, organized into **Brand**, **Regular**, and **Solid** icon families, with the corresponding `fab`, `far`, and `fas` prefixes. This solution simplifies icon selection for web projects and integrates seamlessly into HTML forms.

## Key Features

- **Complete Icon Set**: Displays the full collection of Font Awesome 5 icons, categorized by icon family (`fab`, `far`, `fas`).
- **Dynamic Icon Picker**: Automatically generates a **grid of icons** inside a modal using JavaScript, without needing external CSS.
- **User-Friendly UI**: Hover and click effects for better user interaction. Icons change color on hover, making it easier to identify selected icons.
- **No External CSS**: All styles are applied via JavaScript, so no need to manage additional CSS files.
- **Efficient Icon Selection**: Clicking an icon automatically inserts its class name into an input field for use in your project.

## How It Works

All icons are stored in JavaScript arrays called `brandIcons`, `regularIcons`, and `solidIcons`. Each array contains the class names for **all Font Awesome 5 icons** in their respective families. The script dynamically loads and displays these icons in a modal window when triggered, allowing users to click and select an icon. The selected icon class is inserted into a form input field for easy integration.

### Example of the Icons Array:

```javascript
const solidIcons = [
  'fa-address-book', 
  'fa-500px', 
  'fa-accessible-icon', 
  'fa-adjust', 
  // more icon class names
];
