# CampusKart

A MERN stack-based marketplace where college students can buy and sell products. The platform supports role-based functionalities for buyers, sellers, and admins, ensuring a secure and efficient trading environment.

## Features

- **User Authentication**: Secure login/signup for buyers, sellers, and admins.
- **Role-Based Access**:
  - **Buyer**: Browse products, sort by category and price, view product details, and place bids.
  - **Seller**: List products with images, manage product listings, and review bids.
  - **Admin**: Approve or reject product listings to ensure quality control.
- **Product Sorting**: Filter products by category and price to enhance user experience.
- **Bidding System**: Buyers can place bids on products they are interested in.

## Tech Stack

- **Frontend**: React.js, HTML, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **File Uploads**: Cloudinary (for handling product images)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/itz-kanishk/college-marketplace.git
   cd college-marketplace
   ```

2. **Install server dependencies:**
   ```bash
   cd server
   npm install
   ```

3. **Install client dependencies:**
   ```bash
   cd ../client
   npm install
   ```

4. **Set up environment variables:**
   Create a `.env` file in the `server` directory and add the following:
   ```bash
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

5. **Run the development server:**
   ```bash
   cd server
   npm run dev
   ```

6. **Run the React client:**
   Open a new terminal window and run:
   ```bash
   cd client
   npm start
   ```

## Usage

- **Buyers** can browse products on the homepage, sort by category or price, view product details, and place bids.
- **Sellers** can list new products, upload images via Cloudinary, view their listings, and manage bids.
- **Admins** must approve products before they appear on the homepage, ensuring quality control.

## Contributing

If you'd like to contribute to the project, please fork the repository and create a new branch for your changes. Submit a pull request, and your changes will be reviewed.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


