# \# ThreadCart – Full Stack E-commerce Platform

A full-stack e-commerce platform for browsing,

searching, and purchasing fashion products.



Built using React.js, Django, and Django REST Framework.Mindmap

You can check the project mindmap [here](https://coggle.it/diagram/ZjMdhx8BY6Wpk0y2/t/api-d)

!\[ecom\_project\_mindmap](https://github.com/codersingh74/ ThreadCart/assets/95096218/9bd5029a-3ae0-47cf-991f-0e532580f40d)

## Features

* **User Authentication**: Users can sign up, log in, and manage their accounts.
* **Product Catalog**: Browse through a wide range of t-shirts categorized by season.
* **Shopping Cart**: Add items to the cart, update quantities, and proceed to checkout.
* **Payment Processing**: Secure payment processing for seamless transactions.
* **Order Management**: View past orders and track current orders.
* **User Dashboard**: User can allow to view his own dashboard
* **Admin Panel**: Admins can manage products, users, orders, and other aspects of the website.

## Technologies Used

* **Django**: A high-level Python web framework for rapid development and clean, pragmatic design.
* **Django REST Framework**: A powerful and flexible toolkit for building Web APIs in Django.
* **React**: A JavaScript library for building user interfaces.
* **React Router**: Declarative routing for React.
* **Redux**: A predictable state container for JavaScript apps.
* **SQLite**: Lightweight, serverless, and self-contained SQL database engine.
* **Stripe API**: Payment processing API for handling online transactions securely.

## Setup

1. Clone the repository:

&#x20;   `git clone https://github.com/your-username/E-Commerce-website-using-Django-React.git`

2. Navigate to the project directory:

&#x20;   `cd E-Commerce-website-using-Django-React`

3. Install dependencies of  Backend:

&#x20;   `pip install pipenv pipenv shell pipenv install`

4. Install dependencies of frontend:

&#x20;   `cd projfrontend npm install`

5. Set up environment variables:

   * Create a `.env` file in the root directory.
   * Add the following variables:

```
        REACT\\\_APP\\\_BACKEND=http://localhost:8000/api/
        ```

6. Apply database migrations:

\&#x20;   ```
    python manage.py migrate
    ```

7. Run the development server:

\&#x20;   ```
    cd ecom
    python manage.py runserver
    ```

8. Start the React frontend:

\&#x20;   ```
    cd projfrontend
    npm start
    ```

9. Open your browser and navigate to `http://localhost:3000` to view the website.



# Pages

!\\\[homepage](https://github.com/SaiKumarOfficial/E-Commerce-website-using-Django-React/assets/95096218/b9b627da-b0ec-4625-9c30-1f8ce7cfa9ca)

!\\\[signuppage](https://github.com/SaiKumarOfficial/E-Commerce-website-using-Django-React/assets/95096218/129ad0c9-d9a9-46cd-a423-0c5f56ed28a3)

!\\\[singinpage](https://github.com/SaiKumarOfficial/E-Commerce-website-using-Django-React/assets/95096218/9fb9e6e6-4d7f-4387-908e-ca6c065eb8dc)



!\\\[cartpage](https://github.com/SaiKumarOfficial/E-Commerce-website-using-Django-React/assets/95096218/b77d70e1-0a34-4753-b5f7-9990fa84f276)


