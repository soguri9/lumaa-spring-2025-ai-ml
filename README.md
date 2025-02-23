**Content-Based Recommendation System**

**Overview**

This project builds a simple content-based recommendation system. It takes a user’s description (like "I love thrilling action movies set in space with a comedic twist") and finds similar items (e.g., movies) from a dataset using TF-IDF and Cosine Similarity.
Example
User Input: "I love thrilling action movies set in space, with a comedic twist."
Output: A list of the top 3-5 most similar movies based on the description.

**Setup in Google Colab**

Open the google colab in the browser https://colab.research.google.com/
Open the notebook in Google Colab.
Upload the dataset (e.g., luma1.csv) using the Colab file upload dialog
In the left panel, go to the Files tab, and click Upload.
After uploading, you can access it via "/content/luma1.csv". or “luma1.csv”

**How It Works**

Load Data: The dataset is loaded, and rows with missing descriptions are removed.
Vectorization: Descriptions are converted into TF-IDF vectors.
Similarity: When you input a query, the system computes cosine similarity between the query and each description, then recommends the top matches.
Running the Code:
We can give the user input in the query and run it, then it gives the output as in the below furnished.
query = "I love thrilling action movies set in space, with a comedic twist."
recommend_items(query, df, tfidf_matrix, vectorizer, top_n=5)
Sample Output:

![image](https://github.com/user-attachments/assets/d86c7cb0-13f1-4635-9c9b-8870d5ee3541)

**Below is the video link on demonstrating how to run the code.**
"C:\Users\soguri1\Downloads\DEMO.mp4"


