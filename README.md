# Expense Tracker System

A web-based application developed using ASP.NET Core MVC framework for efficient personal financial management.

## Overview

The Expense Tracker System simplifies personal and household finance management by enabling users to record, categorize, and analyze financial transactions through a secure web interface.

## Key Features

- User authentication and authorization using ASP.NET Identity
- Interactive dashboard with real-time financial overview
- Transaction management for income and expenses
- Custom category creation and management
- Automatic balance calculation and budget tracking
- Visual analytics with charts and reports
- Responsive design for all devices
- Light and dark mode interface
- Secure data storage with SQL Server

## Technology Stack

### Backend
- **Framework:** ASP.NET Core MVC
- **Language:** C#
- **ORM:** Entity Framework Core
- **Database:** Microsoft SQL Server

### Frontend
- **Markup:** HTML5
- **Styling:** CSS3, Bootstrap Framework
- **Scripting:** JavaScript
- **Charts:** Chart.js Library

### Development Tools
- **IDE:** Visual Studio 2022
- **Database Management:** SQL Server Management Studio

## Architecture

The project follows the Model-View-Controller (MVC) architectural pattern with Entity Framework Core for data access and SQL Server for data storage.

## Getting Started

### Prerequisites
- .NET 6.0 SDK or higher
- Microsoft SQL Server (LocalDB or full version)
- Visual Studio 2022 (recommended)

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/expense-tracker.git
cd expense-tracker
```

2. Update the database connection string in `appsettings.json`
```json
"ConnectionStrings": {
  "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=ExpenseTrackerDB;Trusted_Connection=True;"
}
```

3. Apply database migrations
```bash
dotnet ef database update
```

4. Run the application
```bash
dotnet run
```

5. Open your browser and navigate to `https://localhost:5001`

## Database

The system uses Microsoft SQL Server with Entity Framework Core for efficient data management and CRUD operations.

## References

- [Microsoft Docs – ASP.NET MVC Framework](https://docs.microsoft.com/aspnet/mvc)
- [Entity Framework Core Documentation](https://docs.microsoft.com/ef/core)
- [SQL Server Management Studio Guide](https://docs.microsoft.com/sql)
- [Bootstrap Documentation](https://getbootstrap.com/docs)
- [Chart.js Documentation](https://www.chartjs.org/docs)

## License

This project is available for educational and personal use.
