# payON Frontend

The frontend application for payON - a modern digital payment platform designed to simplify financial transactions and provide a seamless payment experience.

## Overview

payON is a comprehensive payment solution that enables users to send and receive money, manage their finances, and perform various payment operations through an intuitive user interface. This repository contains the frontend codebase for the payON platform.

## Features

- **User Authentication**: Secure signup, login, and account management
- **Dashboard**: Personal finance overview with transaction history and account balance
- **Money Transfer**: Send and receive payments to/from other users
- **Bill Payments**: Pay utilities, subscriptions, and other recurring bills
- **QR Code Payments**: Generate and scan QR codes for quick payments
- **Transaction History**: View and filter past transactions
- **Profile Management**: Update personal information and security settings
- **Notifications**: Real-time alerts for account activities
- **Responsive Design**: Optimized user experience across all devices

## Technologies Used

- **React.js**: Frontend framework for building the user interface
- **Redux**: State management across the application
- **React Router**: Navigation and routing
- **Axios**: API requests handling
- **Styled Components/SCSS**: Styling and theming
- **Material UI/Bootstrap**: UI component libraries
- **JWT Authentication**: Secure user sessions

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Git

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/harryhome1/payONFrontend.git
   cd payONFrontend
   ```

2. Install dependencies:
   ```
   npm install
   # or
   yarn install
   ```

3. Create environment configuration:
   Create a `.env` file in the root directory with the following variables:
   ```
   REACT_APP_API_URL=your_backend_api_url
   REACT_APP_ENV=development
   ```

4. Start the development server:
   ```
   npm start
   # or
   yarn start
   ```

5. The application will open in your default browser at `http://localhost:3000`

## Project Structure

```
src/
├── assets/         # Images, icons, and other static files
├── components/     # Reusable UI components
├── config/         # Configuration files
├── constants/      # Application constants
├── containers/     # Stateful components and page layouts
├── context/        # React context providers
├── hooks/          # Custom React hooks
├── redux/          # Redux store, actions, and reducers
├── routes/         # Application routes
├── services/       # API service integrations
├── styles/         # Global styles and themes
├── utils/          # Helper functions and utilities
├── App.js          # Main application component
└── index.js        # Application entry point
```

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from create-react-app configuration
- `npm run lint` - Runs ESLint to check for code issues
- `npm run format` - Formats code with Prettier

## Integration with Backend

This frontend application communicates with the payON backend API. Make sure to set up and run the backend server before using all features of this application.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a pull request

## Deployment

The application can be deployed to various hosting platforms:

- Vercel
- Netlify
- AWS S3 with CloudFront
- GitHub Pages

Follow the specific deployment instructions for your preferred hosting platform.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- All contributors who have helped build and improve payON
- Open-source libraries and tools that made this project possible
