# Discord Clone - StudyBuddy

### Discord Clone using Django

> Features

* User Authentication (Login, Logout, Registration)

* Create, Update, and Delete Chat Rooms

* Post and Delete Messages in Rooms

* User Profile Management

* Recent Activity and a List of All the Topics

* REST API for Fetching all Rooms and Individual Rooms

> API Endpoints

```
 ______________________________________________________________
|       |                |                                     |
|Method |    Endpoint    |             Description             |
|_______|________________|_____________________________________|
|       |                |                                     |
|  GET  |     /api/      |      List available API routes      |
|  GET  |  /api/rooms/   |       Retrieve all chat rooms       |
|  GET  | /api/rooms/:id | Retrieve details of a specific room |
|_______|________________|_____________________________________|
```

> Technologies Used:

* Backend: Django, Django REST Framework
* Frontend: HTML, CSS, JavaScript
* Database: SQLite

> To Clone the Repository

```
git clone https://github.com/seanandersxn/Discord-Clone.git
python -m venv .venv
.venv\scripts\activate
pip install -r requirements.txt
```

> To Run the App:

```
cd studybuddy
python manage.py runserver
```

> The Development Server will be Started at:

```
http://127.0.0.1:8000/
```
