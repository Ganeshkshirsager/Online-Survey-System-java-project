**Online Survey System README**

---

### Project Description:
This project is an implementation of an Online Survey System using Java Swing and AWT (Abstract Window Toolkit). The system allows users to create, distribute, and analyze surveys online. Users can design different types of questions, share surveys with participants, collect responses, and view summarized results.

---

### Features:
1. **User Authentication:**
    - Users can create accounts or log in using existing credentials.
    - Authentication ensures the security and privacy of survey data.

2. **Survey Creation:**
    - Users can create surveys with various types of questions such as multiple-choice, single choice, open-ended, etc.
    - Each question type is supported with appropriate input fields and validation.

3. **Survey Distribution:**
    - Surveys can be shared with participants via generated links or emails.
    - Participants can access and submit responses through the provided links.

4. **Response Collection:**
    - The system collects and stores responses securely.
    - Responses are associated with the corresponding survey and participant information.

5. **Survey Analysis:**
    - Users can view summarized results of surveys.
    - Analysis includes graphical representations and statistical summaries.

---

### Technologies Used:
- **Java Swing:** Used for creating the graphical user interface (GUI) components.
- **AWT (Abstract Window Toolkit):** Used for handling windowing, graphics, and user interface events.
- **Java Database Connectivity (JDBC):** Used for database connectivity to store and retrieve survey data securely.
- **MySQL/SQLite/PostgreSQL:** The database management system used for storing survey data.

---

### Installation:

1. **Clone the Repository:**
    ```bash
    git clone <repository_url>
    ```

2. **Set Up Database:**
    - Install MySQL/SQLite/PostgreSQL.
    - Create a new database for the project.
    - Execute the SQL scripts provided in the `database` folder to create the necessary tables and schema.

3. **Set Up Environment:**
    - Ensure Java Development Kit (JDK) is installed.
    - Set up the necessary dependencies for Swing and AWT development.

4. **Compile and Run:**
    - Navigate to the project directory.
    - Compile the Java files.
    ```bash
    javac *.java
    ```
    - Run the main class.
    ```bash
    java Main
    ```

---

### Contact Information:
For any inquiries or issues, please contact sambhajikshirsagar37607@gmail.com.

---

Feel free to contribute to the project by submitting bug fixes, feature enhancements, or suggestions through pull requests. Thank you for using our Online Survey System!
