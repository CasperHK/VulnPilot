# VulnPilot / OpenVulner

VulnPilot (also known as OpenVulner) is an open-source vulnerability management platform. It enables users to register and manage their systems, track dependencies, and automatically check for related CVEs (Common Vulnerabilities and Exposures) affecting those dependencies.

## Features

- User management and authentication
- System registration and inventory
- Dependency tracking for registered systems
- Automated CVE lookup and vulnerability reporting
- Dashboard and analytics
- Export reports (Excel, Word)
- Role-based access control

## Tech Stack

- [Nuxt.js](https://nuxt.com/) (Frontend)
- [Fiber](https://gofiber.io/) (Backend, Go)
- [GORM](https://gorm.io/docs/index.html) (ORM for Go)
- [SQLocal](https://sqlocal.dev/) (Local SQL database)
- [Nuxt UI](https://ui.nuxt.com/) (UI Components)
- [ApexCharts.js](https://apexcharts.com/) (Charts & Data Visualization)
- [MariaDB](https://mariadb.org/) (Database)
- [Excelize](https://xuri.me/excelize/) (Excel export)
- [WordZero](https://github.com/ZeroHawkeye/wordZero) (Word export)
- [Casbin](https://casbin.org/) (Authorization)

## Getting Started

### Prerequisites

- [Go](https://go.dev/doc/install) >= 1.20
- [Node.js](https://nodejs.org/en/download/) >= 18

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/VulnPilot.git
   cd VulnPilot
   ```

2. **Install backend dependencies:**
   ```bash
   cd backend
   go mod tidy
   ```

3. **Install frontend dependencies:**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Configure your database and environment variables as needed.**

5. **Run the backend:**
   ```bash
   cd ../backend
   go run main.go
   ```

6. **Run the frontend:**
   ```bash
   cd ../frontend
   npm run dev
   ```

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements and bug fixes.

## License

This project is licensed under the MIT License.
