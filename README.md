School App
Welcome to the School App! This application provides functionality for managing lessons, with various roles and permissions. Below is a summary of the features and setup.

Features
Lessons Management
Controller: LessonsController is implemented with all required actions.
CRUD Operations: Teachers can create, view, and delete lessons.
Permissions:
Teachers have full access to manage lessons.
Students can view lessons but are restricted from deleting them.
Permissions with CanCanCan
Integrated CanCanCan gem for role-based access control.
Teachers: Can create and delete lessons.
Students: Cannot delete lessons but can view lesson details.
Styling
Bootstrap: Applied Bootstrap for responsive and visually appealing views.
