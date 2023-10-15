# JavaScript Product Lister

This JavaScript repository contains a function called `listAllItems` designed to work with an array of product objects. Each product object includes information such as the name, price, and available sizes. The `listAllItems` function generates a descriptive string based on the number of items in the array, using template literals and the `join()` method.

## Functionality

Depending on the number of items in the array, the function returns different strings:

1. If there are no items, it returns: "There are no items for sale."

2. If there is only one item, it returns: "There is 1 item for sale: [Item Name]."

3. If there are two items, it returns: "There are 2 items for sale: [Item 1 Name] and [Item 2 Name]."

4. If there are more than two items, it returns: "There are [Number of Items] items for sale: [Item 1 Name], [Item 2 Name], [Item 3 Name], ...".

## Usage

You can use this function to generate informative product listings based on the provided product data. Simply pass an array of product objects to the `listAllItems` function.
