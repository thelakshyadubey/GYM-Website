# GYM Website - Dubeyji's GYM

A responsive gym website built with HTML, CSS, JavaScript, and Bootstrap. Includes features like class information, trainer details, contact form, and a meal calorie calculator connected to a backend API.

## Features

- Responsive design using Bootstrap 5
- Animated sections using AOS (Animate On Scroll) library
- Interactive navigation menu with hamburger toggle for mobile
- Meal calorie calculator with backend API integration
- Contact form with email functionality
- Google Maps integration for location
- Social media links

## Technologies Used

- Frontend:
  - HTML5
  - CSS3
  - JavaScript
  - Bootstrap 5
  - Font Awesome (for icons)
  - AOS Library (for animations)

- Backend:
  - Node.js
  - Express.js
  - MySQL
  - CORS middleware

## Installation

### Frontend
1. Clone the repository
2. Open `index.html` in your browser

### Backend (for meal calculator functionality)
1. Ensure Node.js and MySQL are installed
2. Create a database named `gym_database`
3. Create a `meals` table with columns: `meal_name`, `carbohydrates`, `protein`, `fat`, `calories`
4. Install dependencies:
```
npm install express mysql body-parser cors
```
5. Start the server:
```
node server.js
```

## Project Structure

- `index.html` - Main HTML file
- `styles.css` - Main stylesheet
- `script.js` - Frontend JavaScript
- `server.js` - Backend API server
- `images/` - Directory for images

## API Endpoints

- `POST /api/calculateMeal` - Returns nutritional information for a given meal
- `GET /` - Returns list of available meals

## Customization

1. Update the Google Maps API key in the iframe src
2. Modify the contact email and phone number in the footer
3. Add your own images to the `images/` folder
4. Update the MySQL connection details in `server.js`

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Lakshya Dubey

## Preview
![image](https://github.com/user-attachments/assets/4d4558fb-f744-42da-bbcd-28912f501991)
![image](https://github.com/user-attachments/assets/36484f69-a467-473f-ae1c-0cab8db07e26)
![image](https://github.com/user-attachments/assets/1cf61dd2-8823-4260-911e-6633520eaeec)
![image](https://github.com/user-attachments/assets/09eb4e28-4427-4477-8952-9359e98c999c)
![image](https://github.com/user-attachments/assets/020854bb-a877-44cc-b6f8-4e650b3a88fc)



