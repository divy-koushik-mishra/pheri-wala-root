
### Authentication

1. POST `/api/auth/login`: Endpoint for user login.
2. POST `/api/auth/register`: Endpoint for user registration.
3. POST `/api/auth/logout`: Endpoint for user logout.
4. POST `/api/auth/reset-password`: Endpoint for resetting user password.

### Product Management

5. GET `/api/products`: Endpoint to retrieve a list of products.
6. GET `/api/products/:id`: Endpoint to retrieve a specific product by ID.
7. POST `/api/products/search`: Endpoint to search for products based on certain criteria (e.g., keyword, category).
8. GET `/api/categories`: Endpoint to retrieve a list of product categories.
9. GET `/api/products/:category`: Endpoint to retrieve products by category.

### Cart Management

10. GET `/api/cart`: Endpoint to retrieve the user's cart items.
11. POST `/api/cart/add`: Endpoint to add a product to the user's cart.
12. POST `/api/cart/remove`: Endpoint to remove a product from the user's cart.
13. POST `/api/cart/update`: Endpoint to update the quantity of a product in the user's cart.

### Checkout and Orders

14. POST `/api/orders/place`: Endpoint to place an order.
15. GET `/api/orders`: Endpoint to retrieve the user's order history.
16. GET `/api/orders/:id`: Endpoint to retrieve a specific order by ID.
17. POST `/api/orders/:id/cancel`: Endpoint to cancel an order.

### User Profile

18. GET `/api/users/:id`: Endpoint to retrieve user profile information.
19. PUT `/api/users/:id/update`: Endpoint to update user profile information.
20. GET `/api/users/:id/orders`: Endpoint to retrieve user's orders.

### Miscellaneous

21. GET `/api/featured`: Endpoint to retrieve featured products.
22. GET `/api/promotions`: Endpoint to retrieve ongoing promotions or discounts.
23. GET `/api/reviews/:product_id`: Endpoint to retrieve product reviews by product ID.
24. POST `/api/reviews/add`: Endpoint to add a review for a product.
25. GET `/api/notifications`: Endpoint to retrieve user notifications.
