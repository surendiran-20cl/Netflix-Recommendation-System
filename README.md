# 🎬 Netflix Recommendation System using SVD  

## 📌 Project Overview  
This project implements a **Netflix Recommendation System** using **Singular Value Decomposition (SVD)** from the `surprise` library. The system analyzes user ratings to provide personalized movie recommendations, identify popular genres, and determine the best and worst-rated genres.  

## 🔥 Features  
✅ **Most Popular & Liked Genres** – Identifies the most watched and highest-rated genres.  
✅ **Personalized Recommendations** – Recommends the best movie for a user in every genre.  
✅ **Genre Analysis** – Finds genres with the best and worst user ratings.  

## 📂 Dataset  
The dataset contains user-movie ratings, including:  
- `User_Id` – Unique identifier for users  
- `Movie_Id` – Unique identifier for movies  
- `Genre` – Movie genre classification  
- `Rating` – User rating on a scale  

## 🛠️ Tech Stack  
- **Python**  
- **Pandas & NumPy** for data manipulation  
- **Surprise Library** for SVD-based recommendations  
- **Matplotlib & Seaborn** for data visualization  

## 🚀 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/netflix-recommendation-system.git
   cd netflix-recommendation-system
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook or script to train the model and generate recommendations.  

## 📊 Results  
The system successfully identifies:  
- The most-watched and highest-rated genres.  
- Personalized top movie recommendations per genre.  
- Best and worst-rated genres based on user feedback.  

Feel free to contribute and improve the model! 🚀  
