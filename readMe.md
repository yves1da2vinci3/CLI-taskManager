Certainly! Here's how you can format the information in a README.md file:

# Task Manager CLI Tool

This is a task manager CLI tool built using Node.js and Commander.js.

## Setting Up the Tool

To set up this tool directly from this repository, follow these steps:

1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Create a `.env` file in the root directory and add your MongoDB connection string:
   ```env
   MONGO_URI=<your-mongodb-connection-string>
   ```

4. Install the tool globally:
   ```sh
   npm install -g .
   ```

## Supported Commands

The CLI tool provides CRUD (Create, Read, Update, Delete) operations for tasks. Here's a list of supported commands:

- **Add Task(s):**
  To create one or multiple new tasks.
   ```sh
   todo add
   ```

- **Read Tasks:**
  To read all existing tasks.
   ```sh
   todo read
   ```

- **Update Task:**
  To update a specific task.
   ```sh
   todo update
   ```

- **Delete Task:**
  To delete a specific task.
   ```sh
   todo delete
   ```

