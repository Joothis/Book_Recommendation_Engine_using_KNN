# 📖 Book Recommendation System

A machine learning-based **book recommendation system** that suggests books based on user preferences, ratings, and similarity metrics.

## 🗂 Dataset
We use publicly available book datasets:  

| Dataset | Description | Source |
|---------|------------|--------|
| **Book-Crossing** | Contains book ratings, user data, and metadata | [Kaggle](https://www.kaggle.com/datasets/rxsraghavagrawal/book-crossing-dataset) |
| **Goodreads Books** | Over 12,000+ books with metadata and ratings | [Kaggle](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks) |
| **Amazon Books** | User reviews, ratings, and book details | [Kaggle](https://www.kaggle.com/datasets/datasets/amazon-books-reviews) |

## 🔧 Installation
1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/yourusername/Book-Recommendation-System.git
cd Book-Recommendation-System
```

2️⃣ **Install Dependencies**  
```bash
pip install -r requirements.txt
```

3️⃣ **Run the Notebook**  
```bash
jupyter notebook
```
Open **`book_recommendation.ipynb`** and run the cells.

## 📜 Usage
- Run the notebook.  
- Enter a book title in the function `get_recommends("Book Name")`.  
- Get **top 5 recommended books** based on user preferences.

Example:
```python
print(get_recommends("Harry Potter and the Sorcerer's Stone"))
```
✅ Output:
```
1. The Hobbit
2. The Chronicles of Narnia
3. Percy Jackson & The Olympians
4. Eragon
5. The Golden Compass
```

## 📜 License
This project is licensed under the **MIT License**.

## 📩 Contact
📧 Email: joothiswaranpalanisamy2005@gmail.com 
📌 GitHub: [yourusername](https://github.com/joothis)