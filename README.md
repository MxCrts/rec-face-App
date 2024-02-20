# rec-face-App

`rec-face` is a cutting-edge facial recognition web application that enables users to detect faces in any image with a simple URL input. Utilizing the powerful AI capabilities of the Clarifai model, `rec-face` offers a seamless and intuitive interface for registering or signing in, submitting images, and instantly getting facial detection results with precise bounding boxes drawn around detected faces.

## Features

- **User Authentication**: Secure sign-in and registration process to access the facial recognition feature.
- **Intuitive Interface**: A clean main page featuring the logo and a straightforward URL input field with a "Detect" button.
- **Facial Detection**: Utilize the Clarifai AI model to accurately detect faces in images provided via URL.
- **Visual Feedback**: Display the submitted image below the input field with a dynamically drawn box around detected faces.

## Tech Stack

`rec-face` is built with a robust stack that includes:

- Frontend: HTML, CSS, JavaScript, React
- Backend: Node.js, Express
- Database: PostgreSQL
- Deployment: Heroku

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- PostgreSQL

### Installation

1. Clone the repository:
   git clone https://github.com/<your-username>/rec-face.git
   
2. Navigate to the project directory:
   cd rec-face

3. Install dependencies:
   npm install

4. Use your PAT from Clarifai:

5. Start the Server:
   npm start

Usage
After logging in or registering, you'll be directed to the main page. Enter the URL of an image in the input field and click the "Detect" button. The image will be displayed below, and if a face is detected, a box will be drawn around it.

Contributing
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

Please ensure to update tests as appropriate.

License
Distributed under the MIT License

Acknowledgements
ZTM Academy for the sharing of the application.
Clarifai for the facial recognition API.
Heroku for hosting the application.
 


