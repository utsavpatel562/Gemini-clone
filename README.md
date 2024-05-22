# Gemini: A Google AI Clone

Welcome to **Gemini**, a project inspired by Google's AI capabilities. This application is built using modern web technologies such as React.js, SCSS, and VITE, and leverages Firebase for authentication. It utilizes the Gemini API to simulate AI functionalities similar to Google AI. The project is deployed on Vercel for seamless accessibility and performance.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running Locally](#running-locally)
- [Deployment](#deployment)
- [Firebase Authentication](#firebase-authentication)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **AI Simulation**: Mimics Google AI capabilities using the Gemini API.
- **Authentication**: Secure user authentication via Firebase.
- **Modern UI**: Responsive and interactive user interface designed with React.js and SCSS.
- **Fast Performance**: Built with VITE for optimized performance and fast loading times.
- **Deployment**: Easily deployable on Vercel.

## Technologies Used

- **Frontend**: React.js, SCSS, CSS
- **Build Tool**: VITE
- **API**: Gemini API
- **Authentication**: Firebase
- **Hosting**: Vercel

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your machine.
- A Firebase project set up for authentication.
- Vercel account for deployment (optional).

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/utsavpatel562/Gemini-clone.git
    cd Gemini-clone
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

### Running Locally

1. Create a `.env` file in the root directory and add your environment variables:

    ```env
    VITE_API_URL=your_gemini_api_url
    VITE_FIREBASE_API_KEY=your_firebase_api_key
    VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
    VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
    VITE_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
    VITE_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
    VITE_FIREBASE_APP_ID=your_firebase_app_id
    ```

2. Start the development server:

    ```bash
    npm run dev
    ```

3. Open your browser and navigate to `http://localhost:3000`.

## Deployment

To deploy the project to Vercel, follow these steps:

1. Commit and push your changes to your GitHub repository.
2. Log in to your Vercel account and import your repository.
3. Set up your environment variables in the Vercel dashboard.
4. Deploy your project.

For detailed instructions, visit the [Vercel documentation](https://vercel.com/docs).

## Firebase Authentication

This project uses Firebase for authentication. Make sure to set up your Firebase project and enable the required authentication methods (e.g., Email/Password, Google Sign-In).

### Firebase Setup

1. Go to the Firebase console and create a new project.
2. Enable authentication methods in the Firebase Authentication section.
3. Obtain your Firebase configuration and add it to your `.env.local` file as shown in the [Running Locally](#running-locally) section.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to contact me:

- **GitHub**: [utsavpatel562](https://github.com/utsavpatel562)
- **Email**: utsavpatel562@gmail.com

---

Thank you for checking out Gemini: Google AI Clone! I hope you find this project helpful and inspiring. Happy coding!
