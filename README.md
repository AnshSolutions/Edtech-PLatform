# EdTech Platform

## Description
A full-stack EdTech platform designed to enhance online learning experiences. Built using the MERN stack (MongoDB, Express.js, React.js, Node.js) for a dynamic frontend and scalable backend. The platform integrates user authentication, course management, and interactive features to provide a seamless learning and teaching experience.

## Features
- User Authentication
- Course Management
- Interactive Learning Tools
- Responsive Design

## Tech Stack
- **Frontend:** ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
- **Backend:** ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
- **Database:** ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AnshSolutions/Edtech-PLatform.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Edtech-PLatform
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables in a `.env` file:
   ```
   MAIL_HOST=smtp.gmail.com
   MAIL_USER=your-email@gmail.com
   MAIL_PASS=your-email-password
   JWT_SECRET=your-jwt-secret
   MONGODB_URL=your-mongodb-url
   PORT=4000
   ```
5. Start the development server:
   ```bash
   npm start
   ```

## Usage
- Access the platform at `http://localhost:4000` after starting the server.
- Register or log in to explore the features.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, please contact [your-email@gmail.com](mailto:your-email@gmail.com).

## Screenshots
Include screenshots or GIFs of the platform here.

## Demo
Check out the live demo [here](https://edtech-p-latform.vercel.app).

## API Documentation
- **GET /api/courses**: Retrieve a list of all courses.
- **POST /api/auth/login**: Authenticate a user and return a token.
- **POST /api/auth/register**: Register a new user.

## Future Enhancements
- Add real-time chat functionality.
- Implement a recommendation system for courses.

## Acknowledgments
- Thanks to the open-source community for providing valuable resources and libraries.
- Special thanks to contributors and testers for their feedback. 