# Restaurant Web Project

## Overview
The **Restaurant Web Project** is a full-stack web application designed to manage restaurant operations efficiently. Users can browse the menu, place orders, book tables, and provide feedback. The project also includes an admin panel for restaurant management.

## Features
- 🛒 **Order Now** – Users can place food orders online.
- 📅 **Book a Table** – Customers can make table reservations.
- 📝 **Feedback System** – Users can submit reviews and ratings.
- 🖥️ **Admin Panel** – Manage menu items, orders, and reservations.
- 🗺️ **Google Maps Integration** – Displays restaurant location.
- 📱 **Responsive Design** – Works seamlessly across devices.

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript (Bootstrap for styling)
- **Backend**: Django (Python), Django ORM
- **Database**: SQLite/MySQL
- **Deployment**: Local development server (Django runserver)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/restaurant-web-project.git
   cd restaurant-web-project
   ```
2. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Apply migrations:
   ```sh
   python manage.py migrate
   ```
5. Run the development server:
   ```sh
   python manage.py runserver
   ```
6. Open [127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

## Usage
- **Admin Login**: Navigate to `/admin` to access the dashboard.
- **Order Food**: Users can browse the menu and place orders.
- **Book a Table**: Reserve tables by filling in the booking form.
- **Feedback Submission**: Users can leave reviews and ratings.

## Contributing
Feel free to fork the repository and submit pull requests for improvements.

## License
This project is open-source under the MIT License.

