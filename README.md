# crud-operations-js
# Product Management System (CRUD Operations)

This is a simple CRUD (Create, Read, Update, Delete) product management system implemented in HTML, CSS, and JavaScript. The system allows users to interact with product data, including adding new products, updating existing ones, and performing searches. The product information is displayed in a tabular format.

## Files

- `index.html`: The main HTML file containing the structure of the CRUD system's user interface.

- `crud.css`: The stylesheet file for styling the user interface.

- `crud.js`: The JavaScript file containing the logic for CRUD operations, including product creation, updating, deletion, and search functionality.

## Usage

1. Open the `index.html` file in a web browser.

2. Fill in the product details in the input fields (title, price, taxes, ads, discount, count, category).

3. Click the "Create" button to add a new product. Click the "Update" button to modify an existing product.

4. The total cost is automatically calculated based on the provided information.

5. Use the search bar to filter products by title or category.

6. The product data is displayed in a table, showing various details such as title, price, taxes, ads, discount, total, and category.

7. Individual products can be deleted, and there is an option to delete all products.

## Functions

- `getTotal()`: Calculates the total cost of the product based on the provided details.

- `submit.onclick()`: Handles the submission of the product form, either creating a new product or updating an existing one.

- `clearData()`: Clears the input fields after submission.

- `showData()`: Displays the product data in a table format.

- `deleteData(i)`: Deletes a specific product based on its index.

- `deleteAll()`: Clears all product data.

- `updateData(i)`: Updates the input fields with the details of a selected product for modification.

- `getSearchMood(id)`: Sets the search mode based on the selected search type (title or category).

- `searchData(value)`: Filters and displays products based on the search mode and input value.

## Additional Notes

- The product data is stored using the browser's localStorage, allowing for data persistence between sessions.

- The application provides basic error handling by checking if the product title is not empty before submission.

- The UI is styled using the `crud.css` file to enhance the user experience.

---


