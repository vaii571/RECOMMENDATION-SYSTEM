# RECOMMENDATION-SYSTEM



_COMPANY_: CODTECH IT SOLUTIONS


_NAME_: VAISHNAVI VILAS BANSUDE


_INTERN ID_: CTIS4923


_DOMAIN_: MACHINE LEARNING


_DURATION_: 4 WEEKS


_MENTOR_: NEELA SANTOSH KUMAR

DESCRIPTION OF TASK:

Title: Mental Health Support Recommendation System Using Collaborative Filtering

Introduction:

Recommendation systems are widely used in modern applications to provide personalized suggestions based on user behavior and preferences. In the healthcare domain, such systems can help identify and recommend relevant support services to individuals based on their needs and interaction patterns. This project aims to build a Mental Health Support Recommendation System using collaborative filtering techniques to recommend suitable workplace mental health services to users.

The system uses survey-based interaction data to understand user preferences and applies Matrix Factorization to generate personalized recommendations. The primary objective is to predict which mental health support services would be most beneficial to a particular user.

Dataset Description:

The dataset used in this project is a mental health workplace survey dataset. It contains responses from individuals regarding various aspects of mental health support available in their organizations.
From the dataset, the following service-related columns were selected:

Benefits

Care Options

Wellness Program

Seek Help

Anonymity

Leave

These columns represent different mental health support services provided in workplaces. Since the dataset originally contained categorical responses (such as “Yes”, “No”, “Somewhat”, “Very easy”, etc.), these values were converted into numerical ratings on a scale from 1 to 5. This conversion was necessary to apply collaborative filtering techniques, which require numerical input.

Missing values were handled by assigning a neutral rating to maintain consistency in the dataset.

Data Preprocessing and User-Item Matrix Creation:

After selecting relevant columns and converting categorical responses into numerical values, a user-item interaction matrix was created.

Rows represent users

Columns represent mental health services

Values represent ratings given by users

This matrix forms the foundation of the recommendation system, where patterns between users and services can be analyzed.

Methodology:

To build the recommendation system, Matrix Factorization was implemented using Truncated Singular Value Decomposition (SVD).

SVD reduces the dimensionality of the user-item matrix by identifying latent factors that capture hidden relationships between users and services. These latent factors represent underlying patterns in user behavior.

The process includes:

Decomposing the user-item matrix into latent factors

Reconstructing the matrix using reduced dimensions

Predicting missing or potential ratings

Recommending top services based on predicted ratings

This approach enables personalized recommendations based on collaborative filtering.

Evaluation Metrics:

The performance of the model was evaluated using Root Mean Squared Error (RMSE). RMSE measures the difference between actual ratings and predicted ratings. A lower RMSE indicates better prediction accuracy.

Additionally, a baseline model was implemented using average service ratings for comparison. The comparison demonstrated that the Matrix Factorization model outperformed the baseline model, confirming its effectiveness.

Results and Visualization:

The system successfully generated personalized recommendations for selected users. The top recommended services were displayed using bar charts for better visualization.

Service popularity analysis was conducted by calculating average ratings across users. A correlation heatmap was also generated to visualize relationships between services and identify patterns in user preferences.

An explanation component was included to justify recommendations by displaying predicted ratings and average service ratings.

Conclusion:

This project successfully demonstrates the implementation of a recommendation system in the healthcare domain using collaborative filtering and Matrix Factorization. The system provides personalized mental health service recommendations based on user interaction patterns.

The project showcases practical applications of machine learning techniques including data preprocessing, matrix factorization, evaluation metrics, and visualization. It highlights how recommendation systems can be used to improve mental health support awareness and accessibility in workplace environments.

OUTPUT

<img width="532" height="182" alt="Image" src="https://github.com/user-attachments/assets/ef855240-ad1d-44d6-877a-c0c66593c462" />

<img width="567" height="547" alt="Image" src="https://github.com/user-attachments/assets/af72007a-7fb3-4c1b-be92-3538bd5c4a93" />

<img width="490" height="228" alt="Image" src="https://github.com/user-attachments/assets/bc83a211-4238-4457-a955-b07631103921" />

<img width="575" height="520" alt="Image" src="https://github.com/user-attachments/assets/75cb614f-07ac-45a2-9c27-e11c455288c4" />
