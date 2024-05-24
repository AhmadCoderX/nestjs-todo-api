# nestjs-todo-api

This is a ToDo application built with NestJS. It provides a RESTful API for managing your tasks.

## Prerequisites

Make sure you have the following installed before proceeding:
- [Node.js](https://nodejs.org/) (version 14.x or higher)
- [npm](https://www.npmjs.com/) (version 6.x or higher)
- [NestJS CLI](https://docs.nestjs.com/cli/overview)

## Installation

1. **Install NestJS CLI:**
   ```bash
   npm install -g @nestjs/cli
   ```

2. **Clone the repository:**
   ```bash
   git clone https://github.com/AhmadCoderX/nestjs-todo-api.git
   ```

3. **Navigate into the project directory:**
   ```bash
   cd nestjs-todo-api
   ```

4. **Install dependencies:**
   ```bash
   npm install
   ```
5. **Database Setup**

   - Create a local or online Postgres DB and provide credentials in the `app.module.ts`.
   ![image](https://github.com/AhmadCoderX/nestjs-todo-api/assets/136037316/6cdd6d0a-1f89-41db-97e2-3a8f3419b842)


5. **Run the application:**

   Start the development server:
   ```bash
   npm run start
   ```

## Usage

Once the server is running, you can access the API at `http://localhost:3000`.

## API Endpoints

The following endpoints are available:

- **GET /todos** - Retrieve all todos
- **GET /todos/:id** - Retrieve a specific todo by ID
- **POST /todos** - Create a new todo
- **PATCH /todos/:id** - Update a specific todo by ID
- **DELETE /todos/:id** - Delete a specific todo by ID


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or feedback, feel free to reach out at [My Email](mailto:heyahmadhassan@gmail.com).

---

Thank you for using nestjs-todo-api!
