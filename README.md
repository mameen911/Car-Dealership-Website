# Car Dealership Website

### Overview
This **Car Dealership Website** is a full-featured platform built using **C#** and the **MVC** framework. It integrates live vehicle data from platforms like **Autotrader** and **Cars.co.za** using API tokens, offering users access to up-to-date car listings and information.

### Features
- **Live Vehicle Data:**
  - Fetch real-time car listings from external platforms such as Autotrader and Cars.co.za using live API tokens.
  
- **Car Listings:**
  - Browse detailed listings with vehicle information such as make, model, price, mileage, and more.

- **Search and Filter:**
  - Search for cars based on various criteria (e.g., make, model, price range).
  - Advanced filters allow users to narrow down results based on preferences.

- **Admin Panel:**
  - Admins can manage car listings, view API data, and configure settings.

### Key Functionalities
- **C# MVC Framework:**
  - Developed with ASP.NET MVC for structured and maintainable code.

- **API Integration:**
  - Uses live API tokens to fetch dynamic data from car platforms.
  - Supports data integration with platforms like **Autotrader** and **Cars.co.za**.

- **User-Friendly Interface:**
  - Designed with ease of navigation in mind, providing users with a simple interface to view, search, and explore car listings.

### Installation
1. Clone the repository:
2. Open the project in **Visual Studio**.
3. Restore NuGet packages and ensure the necessary dependencies are installed.
4. Configure the API keys:
   - Update the API token values in the `appsettings.json` file to access Autotrader and Cars.co.za data.
5. Run the application in **IIS Express** or a local web server environment.

### API Integration
- **Autotrader API**: Provides real-time car listings, specifications, and details.

Ensure valid API tokens are stored in the configuration to enable seamless integration.

### Technologies Used
- **C#**: Primary programming language.
- **ASP.NET MVC**: Backend framework used to structure the application.
- **Entity Framework**: ORM used for database management.
- **Bootstrap**: Frontend framework for responsive design.
- **API Integration**: For real-time vehicle data using Autotrader and Cars.co.za.

### Future Enhancements
- **User Authentication**: Add login and registration features for personalized experiences.
- **Payment Integration**: Allow users to make secure payments for bookings or purchases.
- **Test Drive Booking**: Enable users to schedule test drives through the website.

