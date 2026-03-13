# Task Management App

## Overview

The Task Management App is a web application that allows users to create, manage, and track their tasks efficiently. Built using **React** for the frontend and **Python** with **Django** for the backend.

## Database Design

### ER Diagram


### Data Dictionary
| Field Name        | Data Type     | Description                             |
|-------------------|---------------|-----------------------------------------|
| `id`              | Integer       | Unique identifier for each task        |
| `title`           | String        | Title of the task                       |
| `description`     | String        | Description of the task                 |
| `status`          | String        | Current status of the task (e.g., Pending, Completed) |
| `created_at`      | Timestamp     | Timestamp for when the task was created |
| `updated_at`      | Timestamp     | Timestamp for when the task was last updated |

### Documentation of Indexes Used
- **`id`**: Primary key index for the tasks table to ensure unique identification of tasks for efficient retrieval.

### Code First or DB First Approach
This project uses a **Code First** approach

## Structure of the Application

### Single Page Application (SPA)
The application follows a **Single Page Application (SPA)** architecture, allowing for dynamic content updates without page reloads.

## Frontend Structure

### Frontend Framework
The frontend is built using **React**. React was chosen for its component-based architecture, which promotes reusability and easier maintenance. It provides a dynamic user experience and allows for modular UI development.

## Build and Install

### Environment Details
- **Backend**: Python (Django)
- **Frontend**: React
- **Database**: Postgre SQL
- **Dependencies**:
  - CORS
  - React
  - Axios
  

### Instructions to Compile/Build the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/task-management-name.git
   cd task-manager


2. **Create Virtual Enviornment**
```bash
  python -m venv venv
  source venv/bin/activate   # On Windows use `venv\Scripts\activate`
```
3. Install Backend Dependencies:
```bash
  pip install -r requirements.txt
```

4. Navigate to the frontend
   ```bash
   cd task-manager-frontend
   npm install

5. **Start Backend**
```bash
  python app.py
```
