# Netflix Movie Recommendation Engine Using SVD

## Project Overview  
This project builds a personalized movie recommendation system using collaborative filtering based on **Singular Value Decomposition (SVD)**. The system predicts user preferences by analyzing past movie ratings and recommends movies users are likely to enjoy.

## Dataset  
- Netflix Prize dataset with over 24 million ratings from thousands of users on thousands of movies  
- Additional movie metadata including movie titles and release years

## Features  
- Data preprocessing to extract and clean movie IDs and user ratings  
- Filtering out low-activity users and rarely rated movies for better model accuracy  
- Implementation of SVD algorithm using the Surprise library  
- Cross-validation to evaluate model performance using Root Mean Square Error (RMSE)  
- Generation of top-5 personalized movie recommendations for individual users

## Libraries Used  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Surprise (Recommendation systems library)

## Project Workflow  
- **Load Dataset:** Mount your Google Drive and load the Netflix dataset  
- **Preprocess Data:** Clean and filter data to remove inactive users and less-rated movies  
- **Train Model:** Use SVD algorithm from Surprise library to train the model  
- **Evaluate Model:** Use cross-validation and RMSE to check model performance  
- **Make Recommendations:** Predict ratings for a specific user and generate top-5 movie recommendations  

## Results  
- Achieved an average RMSE of ~1.02 on cross-validation  
- Generated meaningful personalized movie recommendations  
- Filtering helped improve model accuracy by focusing on active users and popular movies  

## Business Impact  
- Helps streaming platforms like Netflix improve user experience  
- Enables personalized content discovery  
- Increases user engagement and watch time by recommending relevant movies  
