# Virtual Art Museum Project - Digital Art Walk

## 📋 Overview
This project implements a **Virtual Art Museum** using **HTML5 Canvas** and **PHP** to simulate an interactive environment. User can use 'awsd' key to control the movement of the character "Kirby". Users can explore artworks, search for specific items, and manage collections.

### Features
- Interactive character movement within the museum.
- Search functionality with proximity triggers near NPCs.
- Dynamic artwork collections with user interactions.
- PHP backend for data processing and database operations.

---

## 📂 Project Structure
Below is the directory structure of the project:

```plaintext
.vscode/           # VSCode configuration files
asset/             # Asset files of collection function 
character/         # Character animation assets
exb_images/        # Images used in the exhibition page
homepage_images/   # Images used on the homepage
script/            # JavaScript utilities of collection function
style/             # CSS files for styling
utils/             # php file for collection function

collection.html    # Collection page to display user’s saved artworks
exb.css            # CSS for the exhibition page
exb.js             # JS logic for exhibition interactions
exb.php            # Backend logic for handling exhibition-related requests (character movement)
final_proj.sql     # SQL file for initializing the database
homepage.html      # Homepage of the application
homepage.css       # CSS for the homepage
homepage_kirby.js  # JavaScript for homepage interactions
login.html         # Login page
react.php          # PHP for handling user actions (e.g., collecting items)
register.html      # Registration page
search.js          # JS for search interactions
search.php         # PHP for handling search requests
walk.js            # JS for player movement logic
```

---

## 🚀 Running the Project
### Prerequisites
1. Install a web server (e.g., Apache, Nginx).
2. Install PHP and MySQL.
3. Create a database called `final_proj`.
3. Import the tables using `final_proj.sql`.

### Steps to Run
1. Clone the repository or copy the files into your web server’s root directory.
2. Ensure the database is set up and the connection details in `exb.php` and `search.php` are configured correctly.
  (the default setting is`$host = 'localhost'; $username = 'root'; $password = ''; $dbname = 'final_proj';`)
3. Access the application via the browser:`http://localhost/login.html`

---

## 🛠️ Future Enhancements
- Add support for real-time multiplayer functionality.
- Integrate more animations for a smoother user experience.
- Include detailed artwork descriptions with interactive zoom.
- Allow user to upload their own art works to share with people.

---

## 🖼️ Screenshots
login
![image](https://github.com/marionchenchen/Digital-Art-walk/blob/main/login.jpg)
homepage
![image](https://github.com/marionchenchen/Digital-Art-walk/blob/main/homepage.jpg)
exibition room
![image](https://github.com/marionchenchen/Digital-Art-walk/blob/main/exb.jpg)
collection
![image](https://github.com/marionchenchen/Digital-Art-walk/blob/main/collection.jpg)

---

## 👨‍💻 Contributors
陽明交通大學
- 陳奕
- 蔡芳慈
- 吳佳諭


---

## 👨‍💻Database resource
Stadel museum digital collection
`https://sammlung.staedelmuseum.de/en`

---

## 📄 License
This project is licensed under the MIT License.
