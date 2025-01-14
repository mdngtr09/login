This project implements a secure login system utilizing Spring Security and MySQL. It features user authentication, password encryption, and role-based access control, ensuring safe access to application resources.

Project Features:
User Authentication: Implements login functionality with a custom login page and redirects users upon successful authentication.
Password Security: Uses BCryptPasswordEncoder for hashing passwords before storing them in the MySQL database.
Authorization: Configures role-based access, allowing certain endpoints to be accessible without authentication, while protecting others.
Configuration:
Database Integration: The system is connected to a MySQL database where user details, including usernames and hashed passwords, are stored and managed.
Spring Security: Configured to handle both login and access control, it provides a secure environment for user management.
Endpoints:
/req/signup: Public endpoint for user registration.
/req/login: Custom login page for user authentication.
/index: Default landing page after a successful login.
Static resources (/css/**, /js/**) are accessible without login.
Security Enhancements:
Password Hashing: Ensures secure storage of user passwords with BCrypt.
Access Control: Protects sensitive areas of the application, requiring users to authenticate before access.
![Captura de tela 2025-01-12 195845](https://github.com/user-attachments/assets/b385c218-d63e-4170-80f8-83337d534f30)
![Captura de tela 2025-01-13 023302](https://github.com/user-attachments/assets/7b0572a9-e47a-421b-baa2-19fcde230a65)
![Captura de tela 2025-01-13 023315](https://github.com/user-attachments/assets/baaa6bb8-63ef-45f2-8140-7cefaff63169)
![Captura de tela 2025-01-13 023406](https://github.com/user-attachments/assets/045354c4-b4a8-4bd8-8cba-0f750dec2989)
