<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Product Management</title>
</head>
<body>

    <h2>Add Product</h2>
    <form id="add-product-form">
        <label for="productName">Product Name:</label>
        <input type="text" id="productName" required>
        <label for="sellingPrice">Selling Price:</label>
        <input type="number" step="0.01" id="sellingPrice" required>
        <button type="button" onclick="addProduct()">Add Product</button>
    </form>

    <h2>Product List</h2>
    <ul id="product-list">
        <!-- Product list will be displayed here -->
    </ul>

    <h2>Update Product</h2>
    <form id="update-product-form">
        <label for="updateProductName">Product Name:</label>
        <input type="text" id="updateProductName" required>
        <label for="updateSellingPrice">Selling Price:</label>
        <input type="number" step="0.01" id="updateSellingPrice" required>
        <button type="button" onclick="updateProduct()">Update Product</button>
    </form>

    <h2>User Input</h2>
    <div id="user-input">
        <label for="userName">User Name:</label>
        <input type="text" id="userName" required>
        <button type="button" onclick="displayUserInput()">Display User Input</button>
        <p id="displayedUserInput"></p>
    </div>

    <script src="script.js"></script>
</body>
</html>
