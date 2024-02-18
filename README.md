# MeloMatch

MeloMatch is a music recommendation web application that leverages machine learning algorithms to provide personalized music suggestions based on user preferences and behavior patterns. Whether you're discovering new artists or exploring genres, MeloMatch has you covered.

## Features

- **Personalized Recommendations**: Receive tailored music suggestions based on your listening history and preferences.
- **User Authentication and Profile Management**: Securely manage your account and preferences with built-in authentication.
- **Integration with External Music APIs**: Access a vast catalog of songs, albums, and artists from services like Spotify, Apple Music, and Last.fm.
- **Interactive User Interface**: Explore recommended songs, albums, and genres through an intuitive and dynamic user interface.
- **Feedback and Interaction**: Provide feedback on recommendations to refine future suggestions and enhance the user experience.

## Tech Stack

- **Backend**: Django, Django REST Framework, TensorFlow
- **Frontend**: React, D3.js, Material-UI
- **External APIs**: Spotify, Apple Music, Last.fm
- **Authentication**: OAuth

## Getting Started

To get started with MeloMatch, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/Swish78/melomatch.git
   ```

2. Install dependencies:
   ```
   cd melomatch
   npm install   # Install frontend dependencies
   pip install -r requirements.txt   # Install backend dependencies
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add necessary environment variables such as API keys and database configuration.

4. Run the development server:
   ```
   npm start   # Start the frontend server
   python manage.py runserver   # Start the backend server
   ```

5. Access MeloMatch in your web browser:
   ```
   http://localhost:5173  # Frontend
   http://localhost:8000   # Backend
   ```

## Contributing

Contributions to MeloMatch are welcome! If you have ideas for new features, enhancements, or bug fixes, feel free to open an issue or submit a pull request. Please follow the [contributing guidelines](CONTRIBUTING.md) for more information.

## License

This project is licensed under the [MIT License](LICENSE).
