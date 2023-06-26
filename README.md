# ER Diagram Generator

ER Diagram Generator is a web application that allows users to create Entity-Relationship (ER) diagrams for their existing SQL databases. The application provides an intuitive interface for designing ER diagrams and offers features to visualize, edit, and export the diagrams based on the schema of the user's SQL database.

## Features

- Connect to an existing SQL database and fetch the schema.
- Create, edit, and delete ER diagrams based on the database schema.
- Drag-and-drop functionality to add entities and relationships to the diagram.
- Customize entity attributes and relationship cardinality.
- Generate and view the ER diagram based on the database schema.
- Export the ER diagram as an image or a downloadable file.

## Technologies Used

- Vue.js: A JavaScript framework for building user interfaces.
- Node.js: A JavaScript runtime for server-side development.
- Express: A web application framework for Node.js.
- Go: A programming language used for the backend server.
- MySQL: A relational database management system.
- HTML/CSS: Markup and styling for the web application.

## Project Structure

The project has the following directory structure:

- `backend/`: Contains the Go backend server code.
  - `cmd/`: Contains the main package of the backend application.
  - `internal/`: Contains internal packages and modules for the backend application.
  - `migrations/`: Contains database migration files.
  - `seeds/`: Contains seed data files.
  - `pkg/`: Contains shared packages or modules.

- `frontend/`: Contains the Vue.js frontend code.
  - `src/`: Contains the Vue components, router, and other frontend resources.

- `database/`: Contains SQL scripts for database setup and configuration.

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/your-username/er-diagram-generator.git
```

2. Set up the database:
   - Create a MySQL database for your existing SQL database.
   - Import the SQL scripts from the `database/` directory to set up the necessary tables.
   - Update the database connection settings in the backend configuration files.

3. Set up the backend server:
   - Navigate to the `backend/` directory.
   - Install the required dependencies using your preferred package manager (e.g., Go modules).
   - Start the backend server using the appropriate command (e.g., `go run cmd/main.go`).

4. Set up the frontend:
   - Navigate to the `frontend/` directory.
   - Install the required dependencies using npm or yarn:
   ```bash
   npm install
   ```
   - Start the frontend development server:
   ```bash
   npm run serve
   ```

5. Access the application:
   - Open your web browser and visit `http://localhost:8080` to access the ER Diagram Generator application.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
