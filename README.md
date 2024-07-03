#### App Design 
The app is a straightforward e-commerce platform featuring two primary screens: HomeScreen and CartScreen. It offers a sleek and contemporary design for a seamless shopping experience.

### HomeScreen Design
Header: Contains a logo and icons for menu and search.
Product List: Shows products in a grid layout with image, title, subtitle, price, and an add-to-cart button.
Compact Product Display: Reduced padding and margins to fit more products on the screen.
"View your Items" Button: Enables navigation to the CartScreen for reviewing selected items.

### CartScreen Design
Header: Contains a logo, an optional search icon, and a "CHECKOUT" title.
Cart Items: Shows items in the cart, each with an image, title, subtitle, price, and a remove button.
Total Calculation: Displays the estimated total cost of the items in the cart.
Checkout Button: Prominently featured with a shopping bag icon for proceeding to purchase.

### Data Storage Implementation
AsyncStorage: Utilized for saving cart data locally on the device.
Add to Cart: Updates and stores the cart state in AsyncStorage whenever a new product is added.
Remove from Cart: Updates and stores the cart state in AsyncStorage when items are removed.
Load Cart on Startup: Retrieves cart data from AsyncStorage when the app initializes.

### Screenshots
![photo_2024-07-03_21-48-26](/ShoppingApp/images/photo_2024-07-03_21-48-26.jpg)
![photo_2024-07-03_21-48-42](/ShoppingApp/images/photo_2024-07-03_21-48-42.jpg)
![photo_2024-07-03_21-52-49](/ShoppingApp/images/photo_2024-07-03_21-52-49.jpg)