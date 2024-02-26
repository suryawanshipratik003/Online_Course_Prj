# Online_Course_Prj
 The Online Course Website is a platform developed using Django Framework that facilitates the management and delivery of online courses. It provides functionalities for both administrators and users, allowing administrators to manage courses, videos, fees, and user data, while users can sign up, log in, enroll in courses, and access course materials.

 # Key Features:
1.Admin Dashboard:

Secure login for administrators using Django's built-in authentication system.
Dashboard to manage courses, videos, fees, and user data.
Ability to add, edit, and delete courses with details such as name, description, thumbnail, and fee.
Uploading and managing course videos with titles, descriptions, and links.
Setting course fees and managing payment information.

2.User Authentication:

Sign up page for new users to create an account with email verification.
Log in page for registered users to access their accounts securely.

3.Homepage:

Display of all available courses with thumbnails, names, descriptions, and fees.
Navigation links to different sections of the website.

4.Course Enrollment:

Course details page where users can view course information and enroll.
Integration with Razorpay test API for secure payment processing.
Payment gateway to enable users to make payments for course enrollment.
Automatic enrollment upon successful payment.

5.My Courses Page:

Page to display the courses enrolled by the user.
Access to course materials, videos, and resources for enrolled courses.
Progress tracking and completion status for each enrolled course.

6.Data Management:

Backend database management using Django ORM for storing user data, course details, video information, and payment records.
Admin panel access to view, add, edit, and delete data entries.
