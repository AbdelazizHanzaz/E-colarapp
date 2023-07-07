
# Artisan Home Goods

Artisan Home Goods is an e-commerce platform that specializes in handmade home decor items crafted by skilled artisans. The platform allows users to browse and purchase unique and high-quality products for their homes.

## Installation

1. Clone the repository:

    git clone https://github.com/your-username/artisan-home-goods.git

2. Navigate to the project directory:

    cd artisan-home-goods

3. Install the PHP dependencies using Composer:

    composer install

4. Copy the `.env.example` file and rename it as `.env`:

    cp .env.example .env

5. Generate an application key:

    php artisan key:generate

6. Configure the database connection by updating the `.env` file with your database credentials.

7. Run the database migrations and seed the database with sample data:

    php artisan migrate --seed

8. Install the JavaScript dependencies using npm:

    npm install

9. Build the frontend assets:

    npm run dev

10. Start the development server:
 ```
 php artisan serve
 ```

11. Visit `http://localhost:8000` in your web browser to access the Artisan Home Goods platform.

## Features

- **Product Management**: Add, update, and manage home decor products with details such as name, description, price, and images.

- **Category Management**: Organize products into categories for easy browsing and navigation.

- **User Authentication**: Allow users to register, log in, and manage their profiles.

- **Shopping Cart**: Enable users to add products to their shopping cart, update quantities, and proceed to checkout.

- **Order Processing**: Handle order placement, calculate total amounts, and update order status.

- **Wishlist**: Provide a wishlist functionality for users to save products for future reference.

## Technologies Used

- **Laravel**: A PHP web framework for building the backend of the e-commerce platform. Laravel provides a robust set of tools and features for rapid application development.

- **Vue.js**: A progressive JavaScript framework used for building the frontend of the application. Vue.js enables the creation of dynamic and interactive user interfaces.

- **MySQL**: A relational database management system used for storing product data, user information, and order details.

- **Tailwind CSS**: A utility-first CSS framework for designing responsive and modern user interfaces. Tailwind CSS allows for quick and customizable styling of the platform.

- **Laravel Socialite**: A Laravel package that simplifies social authentication with providers like Google and Facebook.

- **Payment Gateway Integration**: Integration of a payment gateway such as Stripe or PayPal to handle secure payment processing.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


