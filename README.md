# All Font Awesome 5

This project dynamically loads and displays **all Font Awesome 5 icons** in a modal, allowing users to easily select an icon for their project. It supports **Brand**, **Regular**, and **Solid** icon families with the appropriate `fab`, `far`, and `fas` prefixes.

## Features

- Automatically populates a modal with all available Font Awesome 5 icons.
- Icons are stored in a JavaScript array for easy access and modification.
- Includes hover and click effects for user-friendly interaction.
- Allows users to select an icon, and it automatically inserts the chosen icon into an input field.
- No external CSS required—everything is styled inline with JavaScript.

## How It Works

All icons are stored in a JavaScript array called `icons`. This array contains the class names of **all Font Awesome 5 icons**, and it is used to dynamically create the icon grid in the modal. When the modal is shown, it loops through the array, creates each icon element with the appropriate classes (`fab`, `fas`, `far`), and appends them to the modal.

Here’s an example of the array setup in the script:

```javascript
const icons = [
  'fa-address-book', 
  'fa-500px', 
  'fa-accessible-icon', 
  'fa-adjust', 
  // more icon class names
];
