# TasteBud-RecommendationEngine

TasteBud's Recommendation Engine is a hybrid recommendation system that combines collaborative filtering and content-based filtering to provide users with personalized on-site dish recommendations. Processing user, dish data and general trend patterns, the recommendation engine is able to provide users with a list of dishes that they are likely to enjoy based on their past preferences and the preferences of similar users.

Our purpose is to provide users with a personalized experience that will help them discover new dishes that they are likely to enjoy. This will help users to explore new dishes and restaurants that they may not have considered before, and will help them to make more informed decisions when choosing what to eat, with less effort and time spent on browsing through menus.

## Collaborative Filtering:

- **What it does:** Recommends dishes based on user similarity. If User A liked a certain dish and User B has similar preferences, the system suggests that dish to User B.
- **Advantages:** Personalizes recommendations based on the behaviors of similar users.
- **Example:** If 100 users who like "sushi" also like "tempura," the system will recommend tempura to a new user who likes sushi.

![alt text](https://i0.wp.com/analyticsarora.com/wp-content/uploads/2022/03/collaborative-filtering-shown-visually.png?resize=800%2C600&ssl=1)
*Image Source: [Analytics Arora](https://analyticsarora.com/8-unique-machine-learning-interview-questions-on-collaborative-filtering/)*

## Content-Based Filtering:

- **What it does:** Recommends dishes based on their characteristics (e.g., ingredients, categories) and matches them with user preferences.
- **Advantages:** Personalizes recommendations based on the user's past preferences.
- **Example:** If a user likes "sushi" and "tempura" is a type of sushi, the system will recommend tempura to the user.

![alt text](https://cdn.sanity.io/images/oaglaatp/production/a2fc251dcb1ad9ce9b8a82b182c6186d5caba036-1200x800.png?w=1200&h=800&auto=format)
*Image Source: [StrataScratch](https://www.stratascratch.com/blog/step-by-step-guide-to-building-content-based-filtering/)*

## Hybrid Recommendation System (TasteBud):

- Combines **collaborative filtering and content-based filtering** to leverage both user behavior and dish content.
- **For new users:** The engine uses general preferences (popular dishes across the platform) or dish characteristics (content-based filtering) to make recommendations.
- **For returning users:** The engine uses a combination of past interactions (collaborative filtering) and their taste profiles (content-based filtering) to refine suggestions.

## Technology Stack:

- **Python:** Programming language used for the recommendation engine.
- **Scikit-learn:** Machine learning library used for building recommendation models.
- **TensorFlow:** Open-source machine learning library used for building deep learning models.
- **gRPC:** Remote Procedure Call (RPC) framework used for communication between services.
- **Docker:** Containerization platform used for packaging the application and its dependencies.
- **PostgreSQL:** Open-source relational database used for storing user and dish data.
- **GitHub:** Version control system used for managing the project codebase.
- **GitHub Actions:** CI/CD tool used for automating the testing and deployment process.
- **Redis:** In-memory data structure store used for caching recommendation results.

## How It Works:

1. **Data Collection:** Collect user and dish data from the TasteBud platform.
2. **Data Preprocessing:** Clean and preprocess the data for building recommendation models.
3. **Model Training:** Train collaborative filtering and content-based filtering models using the preprocessed data.
4. **Model Evaluation:** Evaluate the models using metrics like RMSE, MAE, and precision-recall.
5. **Model Deployment:** Deploy the models as microservices using Docker containers.
6. **Recommendation Generation:** Generate recommendations for users based on their preferences and past interactions.
7. **Recommendation Display:** Display the recommendations on the TasteBud platform for users to view and interact with.

## Future Enhancements:

- **Real-Time Recommendations:** Implement real-time recommendation generation for users based on their current preferences.
- **Personalized Notifications:** Send personalized notifications to users based on their taste profiles and dish recommendations.
- **Feedback Loop:** Implement a feedback loop to collect user feedback on recommendations and improve the recommendation engine.
- **A/B Testing:** Conduct A/B testing to evaluate the performance of different recommendation algorithms and models.
- **Deep Learning Models:** Explore the use of deep learning models like neural collaborative filtering for better recommendation accuracy.

## Conclusion:

TasteBud's Recommendation Engine aims to provide users with personalized dish recommendations based on their preferences and past interactions. By combining collaborative filtering and content-based filtering, the engine leverages user behavior and dish characteristics to generate accurate and relevant recommendations. With future enhancements like real-time recommendations and personalized notifications, TasteBud aims to create a seamless and engaging user experience for its users.


