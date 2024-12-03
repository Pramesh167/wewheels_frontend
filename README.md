# WeWheels

A React-based frontend for the WeWheels eCommerce website, offering tailored interfaces for both customers (User) and administrators (Admin) to browse and purchase products, manage orders, and handle inventory and customer information.

Youtube link: https://youtu.be/6lm5szeoMas?si=o8KebZ8stieJH_FF

## Features

### Admin Role

- **Dashboard**: Overview of eCommerce operations, including current orders, product inventory, and sales statistics.
- **Product Management**: Manage product listings, add new products, and update product details.
- **Order Management**: View, process, and update orders placed by customers.
- **Customer Management**: Access customer profiles, view order history, and update customer information.
- **Billing & Invoices**: Generate and manage invoices for customer payments and track payment status.

### User Role

- **Google Login**: Secure login using Google account for seamless access to the website.
- **Product Search**: Browse and filter products based on categories, price, and preferences.
- **Cart & Checkout**: Add products to the cart, review orders, and proceed to checkout.
- **Order History**: View and manage personal order history.
- **Profile Management**: Update personal details, addresses, and payment methods.

### Technologies

- ![React.js Logo](path/to/react-logo.png) **React.js**: Core frontend library

- ![Tailwind CSS Logo](path/to/tailwind-logo.png) **Tailwind CSS**: UI styling

### API Integration

The frontend communicates with the backend via a RESTful API, handling operations for both Admin and User roles, such as product management, order processing, customer data handling, and AR try-on functionality.



### Future Works


- **Enhanced Personalization**: Implement AI-driven recommendations based on user preferences and past behavior to suggest products more accurately.
- **In-Store Pickup Option**: Introduce an option for users to reserve products online and pick them up at a physical store location.
- **Social Media Integration**: Enable users to share their try-on experiences and favorite products directly on social media platforms.


### Challenges

- **State Management**: Managing complex state across various components, particularly with features like virtual try-on, user authentication, and shopping cart, was challenging but effectively handled using React's Context API and useReducer hook.
- **Responsive Design**: Ensuring that the user interface remained consistent and functional across a wide range of devices and screen sizes was challenging, but Tailwind CSS provided the flexibility needed to create a responsive design.
- **API Integration**: Handling API requests for real-time product updates, user authentication, and AR data processing while maintaining smooth and secure communication was crucial and required thorough testing.


### Environment Variables

- `REACT_APP_API_URL`: http://localhost:5000
- `REACT_APP_GOOGLE_CLIENT_ID`: 3233117944548-o7084j6cjqtrv1gkj1tt0dr0nvc7thp5.apps.googleusercontent.com
- `REACT_APP_KHALTI_URL`: https://test-pay.khalti.com/
- `REACT_APP_KHALTI_PUBLIC_KEY`: 723a1de3679647e2993b8537e48ec876

 
![alt text](<Get yourself your automobile products at best price (2).png>)

![alt text](qwqw.png)
