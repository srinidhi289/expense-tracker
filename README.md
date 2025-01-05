

## Project Description

The **Expense Tracker Management** project is a full-stack web application built using the MERN stack (MongoDB, Express.js, React, Node.js). It helps users manage their finances by tracking income and expenses. The application provides visual analytics using pie charts, offering insights into financial data over different time periods (weekly, monthly, yearly).

## Features

- **Expense and Income Management**: Easily add, edit, and delete income and expense entries.
- **Categorization**: Classify transactions into customizable categories.
- **Visual Analytics**: 
  - Combined and separate pie chart representations for income and expenses.
  - View analytics based on weekly, monthly, and yearly data.
- **User Authentication**: Secure login and registration functionality.
- **Responsive Design**: Optimized for use on desktops, tablets, and mobile devices.

## Tech Stack

### Frontend:
- React
- Ant Design (UI Framework)
- Axios (API Communication)

### Backend:
- Node.js
- Express.js
- MongoDB (Database)
- Mongoose (ODM for MongoDB)

### Additional Libraries:
- Chart.js (For generating pie charts)

## Installation

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/srinidhi289/expense-tracker-management.git
   cd expense-tracker-management
   \`\`\`

2. Install dependencies for the backend:
   \`\`\`bash
   cd backend
   npm install
   \`\`\`

3. Install dependencies for the frontend:
   \`\`\`bash
   cd ../frontend
   npm install
   \`\`\`

4. Set up environment variables:
   - Create a \`.env\` file in the \`backend\` directory.
   - Add the following variables:
     \`\`\`env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     \`\`\`

5. Start the backend server:
   \`\`\`bash
   cd backend
   npm start
   \`\`\`

6. Start the frontend server:
   \`\`\`bash
   cd ../frontend
   npm start
   \`\`\`

7. Open your browser and navigate to \`http://localhost:3000\` to view the application.

## Project Structure

### Backend:
- \`/models\`: Contains Mongoose schemas for users and transactions.
- \`/routes\`: API routes for user authentication and transaction management.
- \`/controllers\`: Logic for handling API requests.
- \`/middlewares\`: Middleware for authentication and error handling.

### Frontend:
- \`/src/components\`: Reusable React components.
- \`/src/pages\`: Main pages of the application (e.g., Home, Login, Signup).
- \`/src/context\`: Context API for state management.
- \`/src/services\`: Axios service for API calls.

## Future Enhancements

- Add support for recurring transactions.
- Implement budget-setting and alerts.
- Add dark mode for improved user experience.
- Integrate export options for financial reports (PDF/Excel).

## Contributing

We welcome contributions from the community! To contribute:
1. Fork the repository.
2. Create a new branch:
   \`\`\`bash
   git checkout -b feature-name
   \`\`\`
3. Commit your changes:
   \`\`\`bash
   git commit -m \"Add new feature\"
   \`\`\`
4. Push to your branch:
   \`\`\`bash
   git push origin feature-name
   \`\`\`
5. Create a pull request on GitHub.


## Contact

For any questions or feedback, please contact:
- Your Name: [yourname@example.com](mailto:yourname@example.com)
- GitHub: [github.com/yourusername](https://github.com/yourusername)
" > README.md
