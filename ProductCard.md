# Product Card in HTML

## Objective
Created a simple HTML page that displays three product cards for stationery items.

## Products
1. Ball Pen
2. HB Pencil
3. Soft Eraser

## Each Product Card Includes
- Product Image using the `<img>` tag.
- Product Name using the `<h2>` tag.
- Short Description using the `<p>` tag.
- Product Price using the `<h3>` tag.
- "Buy Now" button using the `<button>` tag.

## HTML Elements Used
- `<div>`: Groups each product into a card.
- `<img>`: Displays the product image.
- `<h2>`: Displays the product name.
- `<p>`: Shows a short description.
- `<h3>`: Displays the price.
- `<button>`: Creates a Buy Now button.
  
## Code block
```
<!DOCTYPE html>
<html>
<head>
    <title>Product Cards</title>
</head>
<body>

    <!-- Product 1 -->
    <div style="border:1px solid black; width:220px; padding:10px; margin:10px;">
        <img src="pen.jpg" alt="Pen" width="200">
        <h2>Ball Pen</h2>
        <p>Smooth writing blue ink pen.</p>
        <h3>$2.00</h3>
        <button>Buy Now</button>
    </div>

    <!-- Product 2 -->
    <div style="border:1px solid black; width:220px; padding:10px; margin:10px;">
        <img src="pencil.jpg" alt="Pencil" width="200">
        <h2>HB Pencil</h2>
        <p>High-quality wooden HB pencil.</p>
        <h3>$1.00</h3>
        <button>Buy Now</button>
    </div>

    <!-- Product 3 -->
    <div style="border:1px solid black; width:220px; padding:10px; margin:10px;">
        <img src="eraser.jpg" alt="Eraser" width="200">
        <h2>Soft Eraser</h2>
        <p>Removes pencil marks cleanly.</p>
        <h3>$0.50</h3>
        <button>Buy Now</button>
    </div>

</body>
</html>
```

## Styling
- Inline CSS is used for:
  - Border
  - Width
  - Padding
  - Margin

## Output
The webpage displays three simple stationery product cards with images, descriptions, prices, and Buy Now buttons.