### How to initialize:
->> cd to BACKEND: </br>
    -> venv\Scripts\activate : </br>
    -> python manage.py runserver : </br>
    name: AdminUser : </br>
    email: sefayetalam14@gmail.com : </br>
    pass: 12345 : </br>

->> in another terminal: : </br>
    -> cd to frontend : </br>
    -> npm start : </br>


### Project Description:

# Project_Manager

**Project_Manager** is a web application built with React for the front end and Python with Django for the back end. This application allows users to manage their projects efficiently by providing features to create, update, delete, and search for projects. Each project can have a start date, an end date, a status, and comments. </br>

## Features

- **Create Projects**: Add new projects with a title, start date, end date, status, and comments. 
- **Update Projects**: Modify existing projects to keep them up to date.
- **Delete Projects**: Remove projects that are no longer needed.
- **Search Projects**: Easily find projects using the search functionality on the home page.

## Technologies Used

- **Frontend**: React
- **Backend**: Python, Django
- **Database**: (Specify your database, e.g., PostgreSQL, SQLite)
- **Other Tools**: (List any other tools or libraries you used)

## Installation

### Prerequisites

- Node.js
- Python 3.x
- Django
-  Read instructions.md ans install all

### Backend Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Project_Manager.git
    cd Project_Manager
    ```

2. Set up a virtual environment and activate it:
    ```bash
    python -m venv env
    source env/bin/activate   # On Windows use `env\Scripts\activate`
    ```

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations and run the Django development server:
    ```bash
    python manage.py migrate
    python manage.py runserver
    ```

### Frontend Setup

1. Navigate to the frontend directory:
    ```bash
    cd frontend
    ```

2. Install the required npm packages:
    ```bash
    npm install
    ```

3. Start the React development server:
    ```bash
    npm start
    ```

The application should now be running locally. You can access it by navigating to `http://localhost:3000` in your web browser.

## Usage

- To create a project, navigate to the "Create Project" page and fill in the required fields.
- To update or delete a project, click on the respective project from the project list on the home page.
- Use the search bar on the home page to find specific projects.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.


## Contact

For any inquiries or feedback, feel free to contact:
email: sefayetalam14@gmail.com

---

Happy Project Managing!
