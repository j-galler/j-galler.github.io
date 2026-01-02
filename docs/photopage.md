<div class="image-grid">
    <img src="assets/images/BlueAngels.png" alt="Description 1">
    <img src="assets/images/Bike.png" alt="Description 2">
    <img src="assets/images/Market.png" alt="Description 3">
    <img src="assets/images/Beetle.png" alt="Description 4">
    <img src="assets/images/River.jpg" alt="Description 5">
    <img src="assets/images/Grass.jpg" alt="Description 6">
</div>

.image-grid {
    display: grid;
    /* Creates 3 columns of equal width */
    grid-template-columns: repeat(3, 1fr);
    /* Sets a fixed height for rows to keep uniformity, adjust as needed */
    grid-auto-rows: 200px; 
    /* Adds space between grid items */
    gap: 10px;
    /* Centers all items horizontally and vertically within their grid cells */
    place-items: center; 
}

.image-grid img {
    /* Ensures images fit nicely within their grid cells */
    width: 100%;
    height: 100%;
    /* Crops images to cover the entire area while maintaining aspect ratio */
    object-fit: cover; 
    /* Removes default vertical spacing issues with inline elements */
    display: block; 
}