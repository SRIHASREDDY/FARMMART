# Farm Mart

## Overview
Farm Mart is a digital platform designed to connect farmers directly with buyers, effectively streamlining agricultural trade and reducing intermediaries. This project aims to create a more efficient marketplace where farmers can get better prices for their produce while buyers can access fresher products at competitive rates.

## Features
- **Direct Farmer-Buyer Connection**: Eliminates middlemen in the agricultural supply chain
- **Product Listings**: Allows farmers to list their products with details and pricing
- **Search & Filter**: Enables buyers to search for specific agricultural products
- **Order Management**: Tracks orders from placement to delivery
- **Payment Integration**: Secure payment processing between parties
- **Rating System**: Feedback mechanism for quality assurance
- **Geolocation Services**: Find farmers/products in specific locations

## Technical Architecture
- **Frontend**: React.js with Bootstrap for responsive design
- **Backend**: .NET Core RESTful API
- **API Documentation**: Swagger UI
- **Version Control**: GitHub
- **IDE**: Visual Studio

## API Implementation
The application uses REST API principles to fetch and manipulate data:
- GET endpoints for retrieving product listings and user profiles
- POST endpoints for creating new listings and placing orders
- PUT endpoints for updating product information and order status
- DELETE endpoints for removing listings and canceling orders

## Setup Instructions

### Prerequisites
- Node.js (v14+)
- .NET Core 6.0+
- Visual Studio 2022
- SQL Server (for database)

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/name/repo.git
   cd farm-mart
   ```

2. Backend Setup:
   - Open the solution file in Visual Studio
   - Restore NuGet packages
   - Update the connection string in `appsettings.json`
   - Run database migrations:
     ```bash
     dotnet ef database update
     ```
   - Start the API server:
     ```bash
     dotnet run
     ```

3. Frontend Setup:
   - Navigate to the React client directory:
     ```bash
     cd ClientApp
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the development server:
     ```bash
     npm start
     ```

4. Access the application at `http://localhost:3000`
5. API documentation is available at `http://localhost:5000/swagger`

## User Roles
1. **Farmers**:
   - Create and manage product listings
   - Process orders
   - Track payments
   - Manage inventory

2. **Buyers**:
   - Browse product listings
   - Place orders
   - Make payments
   - Rate farmers and products

## Future Enhancements
- Mobile application development
- Integration with logistics providers
- Advanced analytics for pricing trends
- Subscription-based ordering options
- Community forums for knowledge sharing

## Contributors
- [Your Name]
- [Team Member Names]

## License
MIT License
