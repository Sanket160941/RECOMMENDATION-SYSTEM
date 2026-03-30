# RECOMMENDATION-SYSTEM

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SANKET MITHBAVKAR

*INTERN ID*: CTIS6838

*DOMAIN*: MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION ABOUT THIS TASK*:
In this task, we developed a recommendation system using the movie ratings dataset, which contains user interactions in the form of ratings given to different movies. The dataset includes key attributes such as user IDs, movie IDs, and ratings, making it well-suited for building a recommendation system based on user preferences. This structured format allowed us to understand how users interact with items and enabled us to extract meaningful patterns for generating personalized recommendations.

The first step in the process was loading and exploring the dataset to understand its structure and quality. We examined the number of users, number of movies, and the distribution of ratings. Since real-world datasets often contain missing values, we handled sparsity by transforming the data into a user-item matrix, where rows represent users and columns represent movies. Each cell in this matrix contains the rating given by a user to a movie, and missing values were replaced with zeros to ensure compatibility with mathematical operations. This transformation is a crucial step in recommendation systems, as it provides the foundation for both similarity-based and matrix factorization techniques.

To build the recommendation system, we first implemented collaborative filtering using a user-based approach. In this method, we calculated similarity between users using cosine similarity. This technique measures how similar two users are based on their rating patterns. Once similar users were identified, we recommended movies that similar users had liked but the target user had not yet watched. This approach mimics real-world recommendation logic, where users receive suggestions based on preferences of like-minded individuals. Additionally, we extended this concept by implementing item-based collaborative filtering, where similarity between movies was calculated instead of users. This helped in recommending movies that are similar to those already liked by a user, improving the diversity and relevance of recommendations.

To further enhance the system, we implemented matrix factorization using Singular Value Decomposition (SVD). This technique decomposes the user-item matrix into lower-dimensional matrices, capturing hidden relationships between users and movies. Unlike basic collaborative filtering, SVD is capable of identifying latent features such as user interests and movie characteristics, even when data is sparse. By reconstructing the matrix using these latent factors, we were able to predict missing ratings and generate more accurate recommendations. This advanced approach significantly improves performance, especially in large-scale systems. The entire implementation was carried out in a Jupyter Notebook environment using Visual Studio Code (VS Code). This platform provided a clean and organized workspace where we could write, execute, and document our code step by step. Each stage of the workflow, including data preprocessing, model building, evaluation, and visualization, was divided into separate cells for clarity and readability. This structured approach not only made the development process efficient but also ensured that the final deliverable was easy to understand and well-documented.

In terms of scalability, several important actions were taken. We optimized data handling by using matrix operations instead of loops wherever possible, which significantly improved computational efficiency. The use of cosine similarity and SVD allows the system to scale to larger datasets with minimal modifications. Additionally, we implemented model persistence by saving similarity matrices, enabling reuse without recomputation. We also designed a recommendation pipeline that integrates multiple methods, allowing the system to be extended or modified easily. These steps ensure that the system can handle larger datasets and more users in real-world applications. This recommendation system has wide applicability in various domains. It can be used in movie streaming platforms to suggest films to users, in e-commerce websites to recommend products, and in music streaming services to suggest songs based on listening history. The techniques used in this task are fundamental to many modern recommendation engines used by platforms like Netflix and Amazon. Through this task, we gained practical experience in building, analyzing, and improving recommendation systems using both basic and advanced machine learning techniques.

*OUTPUTS*:
<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/19fb8960-ca3e-45f5-a31a-b2864af6df6c" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/cdeaa995-ae41-409a-8d63-e97005657e9f" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/89e79c9f-4768-4779-9ae0-d45e3ecfc02c" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/435395f5-891a-4e0d-82a6-0eb430ddeb74" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/b8b25a4f-3d30-4ae1-b003-53a1cc56f6b5" />

<img width="2553" height="1060" alt="Image" src="https://github.com/user-attachments/assets/262e4b3a-00aa-4303-87da-d9316ae1f956" />

<img width="17" height="12" alt="Image" src="https://github.com/user-attachments/assets/50df4b1d-68b9-4d20-b6c5-50135551926b" />

<img width="2545" height="1184" alt="Image" src="https://github.com/user-attachments/assets/0210079f-793f-4a0d-83e8-391cb465bb44" />

<img width="1447" height="1301" alt="Image" src="https://github.com/user-attachments/assets/6e531343-3502-45b2-8494-0816979b807b" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/85d520fa-5ea7-4f5c-a5af-e830e5b7f28b" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/06be75fc-f5a8-4471-b72f-affbf4c4a9d6" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/9765df01-e667-44ad-970b-9a22c702e5d4" />

<img width="2559" height="1137" alt="Image" src="https://github.com/user-attachments/assets/1e6663d3-4245-46e6-9f64-9976e8964c39" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/0c67f58c-ea89-45b7-a82d-620e22238b0b" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/0fa17b5c-7005-4192-88e2-a294d047c515" />
