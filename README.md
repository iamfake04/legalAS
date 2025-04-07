# LegalAS - Legal Guidance Platform for India

A comprehensive legal guidance platform connecting users with verified lawyers across multiple case types in India.

## Features

- Legal Assessment Module with interactive questionnaire
- Case type identification
- Jurisdiction determination
- Urgency assessment
- Potential compensation estimation
- Lawyer matching system
- User dashboard
- Lawyer profile management

## Tech Stack

- Frontend: React.js with TypeScript
- Backend: Node.js with Express
- Database: MongoDB
- Authentication: JWT
- Styling: Tailwind CSS

## Project Structure

```
legalAS/
├── client/                 # Frontend React application
├── server/                 # Backend Node.js application
├── shared/                 # Shared types and utilities
└── README.md
```

## Getting Started
`
1. Clone the repository
2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd server
   npm install

   # Install frontend dependencies
   cd ../client
   npm install
   ```

3. Set up environment variables:
   - Create `.env` files in both client and server directories
   - Configure MongoDB connection string and JWT secret

4. Start the development servers:
   ```bash
   # Start backend server
   cd server
   npm run dev

   # Start frontend server
   cd ../client
   npm start
   ```

## License

MIT 