# Employee Management System

A React-based employee management system built with TypeScript, Chakra UI, and integrated with the ReqRes API.

## Features

- User Authentication (Login)
- Employee List View
- CRUD Operations
  - View employee details
  - Edit employee information
  - Delete employee records
- Pagination
- Responsive Design

## Tech Stack

- React 18
- TypeScript
- Chakra UI
- React Router DOM
- Axios
- Vite

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository
```bash
git clone <repository-url>
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

### Build for Production

```bash
npm run build
```

## Usage

1. Login using the following credentials:
   - Email: eve.holt@reqres.in
   - Password: cityslicka

2. After successful login, you'll be redirected to the users list page
3. You can:
   - View all employees
   - Edit employee details
   - Delete employee records
   - Navigate through pages using pagination

## Project Structure

```
src/
├── components/
│   ├── LoginForm.tsx
│   └── UserList.tsx
├── services/
│   └── api.ts
├── types/
│   └── user.ts
├── App.tsx
└── main.tsx
```

## API Integration

This project uses the ReqRes API (https://reqres.in) for demonstration purposes. The following endpoints are utilized:

- POST /api/login - User authentication
- GET /api/users - Fetch users list
- PUT /api/users/:id - Update user
- DELETE /api/users/:id - Delete user

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.# Employee Management System

A React-based employee management system built with TypeScript, Chakra UI, and integrated with the ReqRes API.

## Features

- User Authentication (Login)
- Employee List View
- CRUD Operations
  - View employee details
  - Edit employee information
  - Delete employee records
- Pagination
- Responsive Design

## Tech Stack

- React 18
- TypeScript
- Chakra UI
- React Router DOM
- Axios
- Vite

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository
```bash
git clone <repository-url>
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

### Build for Production

```bash
npm run build
```

## Usage

1. Login using the following credentials:
   - Email: eve.holt@reqres.in
   - Password: cityslicka

2. After successful login, you'll be redirected to the users list page
3. You can:
   - View all employees
   - Edit employee details
   - Delete employee records
   - Navigate through pages using pagination

## Project Structure

```
src/
├── components/
│   ├── LoginForm.tsx
│   └── UserList.tsx
├── services/
│   └── api.ts
├── types/
│   └── user.ts
├── App.tsx
└── main.tsx
```

## API Integration

This project uses the ReqRes API (https://reqres.in) for demonstration purposes. The following endpoints are utilized:

- POST /api/login - User authentication
- GET /api/users - Fetch users list
- PUT /api/users/:id - Update user
- DELETE /api/users/:id - Delete user

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.
