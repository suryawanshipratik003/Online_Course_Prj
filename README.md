
# Online Course Website with Django Framework

# Description:
This project is an Online Course Website developed using the Django Framework, providing a platform for managing and delivering online courses. The website includes functionalities for both administrators and users, allowing administrators to manage courses, videos, fees, and user data, while users can sign up, log in, enroll in courses, and access course materials.

# Key Features:

**Admin Dashboard**: Secure login for administrators to manage courses, videos, fees, and user data.
**User Authentication**: Sign up and log in functionality for users to access their accounts securely.
**Homepage**: Display of all available courses with thumbnails, descriptions, and fees.
**Course Enrollment**: Integration with Razorpay test API for secure payment processing and course enrollment.
**My Courses Page**: Display of enrolled courses with access to course materials and progress tracking.
**Data Management**: Backend database management using Django ORM for storing user data, course details, and payment records.

# Technologies Used:

Django Framework
HTML/CSS/JavaScript
Bootstrap Framework
Razorpay API
SQLite or PostgreSQL (Database Management)
# Installation:

Clone the repository: **git clone https://github.com/yourusername/online-course-website.git**
Navigate to the project directory: **cd online-course-website**
Install dependencies: **pip install -r requirements.txt**
Run migrations: **python manage.py migrate**
Create a superuser: **python manage.py createsuperuser**
Start the development server: **python manage.py runserver**
Access the website at: **http://localhost:8000**
# Usage:

Access the admin dashboard by logging in with the superuser credentials at **http://localhost:8000/admin**.
Add courses, upload videos, and manage user data from the admin panel.
Users can sign up, log in, browse available courses, enroll in courses, and access course materials.
Payments are processed securely using the Razorpay test API during course enrollment.
Contributing:

Fork the repository.
Create a new branch: git checkout -b feature/new-feature
Make your changes and commit them: git commit -m 'Add new feature'
Push to the branch: git push origin feature/new-feature
Submit a pull request.
License:
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements:

Special thanks to Django, Bootstrap, and Razorpay for their excellent tools and documentation.
Contact:
For any inquiries or issues, please contact email@example.com.





