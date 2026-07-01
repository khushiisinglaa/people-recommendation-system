# 👥 People Recommendation System

A Python-based recommendation system that suggests:

- 🤝 **People You May Know** using mutual friends.
- 📄 **Pages You Might Like** using collaborative filtering.

This project demonstrates how social media platforms recommend connections and content using basic Python data structures without any machine learning libraries.

## 🚀 Features

- Load user data from JSON
- Clean and preprocess data
- Remove duplicate and inactive records
- Recommend people based on mutual friends
- Recommend pages based on shared interests

## 🛠️ Tech Stack

- Python
- JSON
- Dictionaries
- Sets

## 📂 Project Structure

```
📁 people-recommendation-system/
│
├── codebook_data1.json
├── duplicated+data.json
├── cleaned_codebook_data.json
├── load_data.py
├── clean_data.py
├── people_recommendation.py
├── pages_you_might_like.py
└── README.md

## 📖 What I Learned

- JSON handling
- Data cleaning
- Recommendation algorithms
- Collaborative filtering
- Python data structures

⭐ Feel free to explore the project and share your feedback!


## Sample Output

### People You May Know

```text
People You May Know for User 1:
[7, 8, 9, 10, 11, 12]
```

### Pages You Might Like

```text
Pages You Might Like for User 1:
[102, 104]
```