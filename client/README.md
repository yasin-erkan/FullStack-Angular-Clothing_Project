Angular 

# FullStack E-Commerce Platform

![FullStack E-Commerce Platform](https://github.com/yasin-erkan/Clothing-Angular/blob/main/Clothing.gif)

A modern e-commerce platform built with Angular and Node.js.

## Tech Stack

### Frontend
- Angular 17+
- SCSS for styling
- RxJS for reactive programming
- Angular Material (optional)

### Backend
- Node.js
- Express.js
- MongoDB (assumed)

## Project Structure

```
├── client/                 # Angular frontend
│   ├── src/
│   │   ├── app/
│   │   │   ├── components/ # Reusable components
│   │   │   ├── home/      # Home page components
│   │   │   ├── layout/    # Layout components
│   │   │   ├── modules/   # Feature modules
│   │   │   ├── pipes/     # Custom pipes
│   │   │   └── services/  # API services
│   │   ├── assets/        # Static assets
│   │   └── styles/        # Global styles
│   └── ...
└── server/                # Node.js backend
    └── ...
```

## Getting Started

### Prerequisites
- Node.js (v18+)
- npm or yarn
- Angular CLI

### Installation

1. Clone the repository
```bash
git clone <repository-url>
```

2. Install frontend dependencies
```bash
cd client
npm install
```

3. Install backend dependencies
```bash
cd ../server
npm install
```

### Development

1. Start the backend server
```bash
cd server
npm run dev
```

2. Start the Angular development server
```bash
cd client
ng serve
```

The application will be available at `http://localhost:4200`

## Features

- Product listing and search
- Shopping cart functionality
- User authentication
- Order management
- Admin dashboard

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
