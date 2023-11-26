# HarmoniFi

HarmoniFi is a music recommendation app that uses machine learning to suggest music to users based on their listening habits.

## Getting Started

To get started, you will need to create a Spotify developer account and obtain a client ID and client secret. You will also need to create a PostgreSQL database and configure the `config.py` file with your database connection credentials.

Once you have done that, you can build the Docker image for the app by running the following command:

docker build -t harmoniFi .


You can then run the app by running the following command:

docker run -p 5000:5000 harmoniFi

The app will be running on http://localhost:5000.

Usage
To use the app, you will need to create a user account. Once you have created an account, you can log in and start using the app.

The app will recommend music to you based on your listening habits. You can also browse for music by genre, artist, or mood.

Contributing
We welcome contributions to HarmoniFi. Please read our contributing guidelines for more information.
