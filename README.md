🌍 TripNest: Full-Stack Travel Accommodation Platform
Live Demo: https://tripnest-zczi.onrender.com

🚀 Overview
TripNest is a full-stack web application inspired by Airbnb, designed to provide a seamless experience for users to discover, list, and manage travel accommodations. The project focuses on robust server-side rendering, RESTful API principles, and secure data handling.

🛠️ Technical Architecture
The application follows the MVC (Model-View-Controller) design pattern to ensure a clean separation of concerns, making the codebase scalable and maintainable.

Frontend: Dynamic templating using EJS, styled with Bootstrap 5 for a fully responsive mobile-first UI.

Backend: Node.js & Express.js handling complex routing and middleware logic.

Database: MongoDB (NoSQL) with Mongoose for schema-based data modeling.

Authentication: Strategy-based authentication using Passport.js, supporting persistent sessions.

Cloud Services:

Cloudinary: For optimized image transformation and storage.

Mapbox API: For interactive geospatial data visualization.

MongoDB Atlas: For cloud database hosting.

✨ Key Features & Engineering Highlights
Complete CRUD Functionality: Users can Create, Read, Update, and Delete property listings with server-side validation.

Geocoding & Interactive Maps: Integrated Mapbox SDK to convert location strings into geographical coordinates (lat/long) for visual markers.

Image Upload Pipeline: Implemented multi-part form handling (using Multer) to upload property images directly to Cloudinary.

Security & Validation: Used Joi for schema validation to prevent malformed data. Implemented Passport-Local for salted and hashed password storage.

Authorization: Protected routes using custom middleware (e.g., ensuring only owners can edit or delete their listings).

Review Ecosystem: A nested data relationship allowing users to leave ratings and textual feedback on specific properties.

⚙️ Installation & Setup
Clone the Repo:

Bash
git clone https://github.com/Shreyaspawar203/Tripnest.git
cd Tripnest
Install Dependencies:

Bash
npm install
Environment Configuration:
Create a .env file in the root directory and add:

Code snippet
ATLASDB_URL=your_mongodb_atlas_url
CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
MAP_TOKEN=your_mapbox_public_token
SECRET=your_session_secret_phrase
Launch:

Bash
node app.js
(Visit http://localhost:8080/listings in your browser.)

👨‍💻 Author
Shreyas Pawar
Computer Engineering Student | Mumbai University
https://www.linkedin.com/in/shreyas-pawar-85028a305/
https://github.com/Shreyaspawar203
