
## flutter_ecommerce_app

### Project Snapshots

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <style>
        .gallery {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 10px;
            max-width: 800px;
            margin: auto;
            text-align: center;
        }
        .gallery-item {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .gallery p {
            margin-top: 5px;
            font-size: 14px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="gallery">
        <div class="gallery-item">
            <img src="/snapshots/signup.jpg" alt="Signup Page">
            <p>Signup Page</p>
        </div>
        <div class="gallery-item">
            <img src="/snapshots/login.jpg" alt="Login Page">
            <p>Login Page</p>
        </div>
        <div class="gallery-item">
            <img src="/snapshots/home_page.jpg" alt="Home Page">
            <p>Home Page</p>
        </div>
        <div class="gallery-item">
            <img src="/snapshots/product_by_category.jpg" alt="Products by Category">
            <p>Products by Category</p>
        </div>
        <div class="gallery-item">
            <img src="/snapshots/product_details.jpg" alt="Product Details">
            <p>Product Details</p>
        </div>
        <div class="gallery-item">
            <img src="/snapshots/favorites.jpg" alt="Favorites">
            <p>Favorites</p>
        </div>
        <div class="gallery-item">
            <img src="/snapshots/cart.jpg" alt="Cart">
            <p>Cart</p>
        </div>
        <div class="gallery-item">
            <img src="/snapshots/address_confirmation.jpg" alt="Address Confirmation">
            <p>Address Confirmation</p>
        </div>
        <div class="gallery-item">
            <img src="/snapshots/payment.jpg" alt="Payment">
            <p>Payment(simulation)</p>
        </div>
        <div class="gallery-item">
            <img src="/snapshots/profile.jpg" alt="Profile">
            <p>Profile</p>
        </div>
        <div class="gallery-item">
            <img src="/snapshots/order_tracking.jpg" alt="Order Tracking">
            <p>Order Tracking(Simulation)</p>
        </div>
        <div class="gallery-item">
            <img src="/snapshots/address.jpg" alt="Address">
            <p>Address</p>
        </div>
    </div>
</body>
</html>





### Directory Structure
```
📂lib
 │───main.dart  
 │───📂core  
 |   │──app_data.dart
 |   │──app_theme.dart
 |   │──app_color.dart
 |   └──extensions.dart
 └───📂src
     │────📂model
     │    │──product.dart
     |    │──product_category.dart
     |    │──product_size_type.dart
     |    │──recommended_product.dart
     |    │──categorical.dart
     |    │──numerical.dart
     |    └──bottom_navy_bar_item.dart
     └────📂view
     |    │───📂screen
     |    |   |──home_screen.dart
     |    |   |──product_list_screen.dart
     |    |   |──product_detail_screen.dart
     |    |   |──favorite_screen.dart
     |    |   |──cart_screen.dart
     |    |   └──profile_screen.dart
     |    │───📂widget
     |    |   |──carousel_slider.dart
     |    |   |──product_grid_view.dart
     |    |   |──list_item_selector.dart
     |    |   └──empty_cart.dart
     |    |   └──page_wrapper.dart
     |    └───📂animation
     |        |──animated_switcher_wrapper.dart
     |        └──open_container_wrapper.dart
     └────📂controller
          └──product_controller.dart
```

<br/>

### Dependencies
Package Name        |
:-------------------------|
|[GetX](https://pub.dev/packages/get) 
|[bottom_navy_bar](https://pub.dev/packages/bottom_navy_bar) 
|[smooth_page_indicator](https://pub.dev/packages/smooth_page_indicator)
|[flutter_rating_bar](https://pub.dev/packages/flutter_rating_bar)
|[font_awesome_flutter](https://pub.dev/packages/font_awesome_flutter)
|[animations](https://pub.dev/packages/animations)
|[flutter_launcher_icons](https://pub.dev/packages/flutter_launcher_icons)

<br/>
