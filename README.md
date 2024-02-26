# Movie Recommender System using TMDB Dataset

This repository hosts the code for a Machine Learning-based Movie Recommender System developed using the TMDB dataset. The project aims to provide personalized movie recommendations to users based on their viewing history, preferences, and the intrinsic characteristics of the movies.

## Project Overview

The recommender system utilizes collaborative filtering, content-based filtering, and hybrid methods to generate movie recommendations. It leverages the TMDB dataset, which includes movie metadata, user ratings, and social media data, to understand user preferences and predict movies that users are likely to enjoy.

## Features

- **Collaborative Filtering**: Identifies similar users and recommends movies liked by these users.
- **Content-Based Filtering**: Recommends movies similar to those a user has liked in the past, based on movie metadata like genres, director, and actors.
- **Hybrid Recommendation**: Combines collaborative and content-based filtering to improve recommendation quality.
- **User Interface**: Simple and interactive web interface for users to rate movies and receive recommendations.
- **Scalability**: Designed to efficiently handle large datasets and a growing number of users.

## Technologies and Frameworks

- **Python**: Primary programming language for data processing and machine learning.
- **Pandas & NumPy**: For data manipulation and numerical operations.
- **Scikit-learn**: For implementing machine learning algorithms.
- **Surprise**: A Python scikit for building and analyzing recommender systems.
- **Flask**: For creating the web application.
- **TMDB API**: For fetching real-time movie data and metadata.

## Getting Started

### Prerequisites

- Python 3.6+
- Pip package manager

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/ankitrajsh/movie-recommendation-system
   
2. Navigate to the project directory:
   ```bash
   cd movie-recommendation-system
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

- Launch the web application:
  ```bash
  python app.py
  ```

## Usage

- Access the web interface at `http://localhost:5000`.
- Rate some movies to set your preferences.
- The system will recommend movies based on your ratings and preferences.

## Contributing

Contributions to improve the project are welcome. Please follow these steps to contribute:

1. Fork the project repository.
2. Create a new branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

- **Project Maintainer**: Ankit Sharma
- **Email**: Ankitraj.84060@gmail.com
- **LinkedIn**: [Ankit Sharma](https://www.linkedin.com/in/ankitrajsh)

## Acknowledgments

- TMDB for providing the dataset.
- The Python and ML community for excellent resources and libraries.
