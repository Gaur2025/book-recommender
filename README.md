# Book Recommender System

Welcome to the Book Recommender System! This system utilizes a collaborative filtering recommendation algorithm to suggest books based on user preferences. The algorithm is tailored to books that have been rated by more than 50 readers, and users who have rated more than 200 books, ensuring high-quality recommendations.

## About Recommender Systems

Recommender systems, also known as recommendation systems, are a subclass of information filtering systems that predict and suggest items to users. They are widely used to personalize user experiences by offering suggestions that align with individual preferences. There are several types of recommender systems:

1. **Collaborative Filtering**: This method predicts a user's preferences based on the preferences of similar users. It operates under the assumption that users who have agreed in the past will agree in the future.

2. **Content-Based Filtering**: This approach suggests items similar to those the user has shown interest in before. It relies on item features and user profiles to make recommendations.

3. **Hybrid Recommender Systems**: These systems combine different recommendation techniques to provide more accurate and diverse suggestions.

## How to Use

### Clone the Repository

1. Clone this repository using Git:
```bash
git clone https://github.com/your-username/book-recommender-system.git
cd book-recommender-system
```

### Setup Virtual Environment

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

### Install Dependencies
3. Install the required packages using requirements.txt:
```bash
pip install -r requirements.txt
```


### Run the flask app locally
4. Navigate to the app directory and run the Flask app:
```bash
python app.py
```

5. Access the web interface by opening a web browser and navigating to http://127.0.0.1:5000.

Use the simple UI to input your preferences, and the recommender system will suggest books tailored to your taste.

Feel free to explore and modify the code to enhance the recommender system according to your needs.

Happy reading and discovering new books!

