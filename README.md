# 👗🌹💍 **Wedding Essentials: Vector Space Model**

Welcome to the world of wedding essentials turned into numbers! This project helps decode the magic behind wedding items using text analysis. 🎩💐

## **What's Inside?**
- **Text Cleanup Magic:** We tidy up text about wedding gowns, roses, diamonds, and flowers. No mess, just sparkling clean data! ✨✨
- **Numeric Transformations:** We transform words into numbers using special tools like CountVectorizer and TF-IDFVectorizer. Turning wedding dreams into digits! 🔢💭
- **Meaningful Relations:** Ever wondered how words understand each other? Dive into Word Embeddings to discover the connections between wedding items. 🤝💬
- **Measure Similarity:** We calculate how closely related wedding choices are with Cosine Similarity. Finding perfect matches! 📏🎯



## **Assignment Description**
This code is part of an assignment for my CMPE 256 class at SJSU by Chandrasekar Vappulapati that creates a Vector Space Model for predicting a user's preferred wedding gown based on their user data and document features related to wedding store items such as wedding gowns, roses, diamond rings, and other related items. The code processes the user data and document features to create a vector representation of each document, which is then used to calculate the cosine similarity between the user data and each document. The document with the highest cosine similarity score is considered the predicted preferred wedding gown for the user.

**Learning objective:** develop a Vector Space Model (VSM) for the Wedding gown
d stands for a document.
Vocabulary Vector (Gown, Rose, Diamond, Flowers)
- d1: User selected Wedding gown.
- d2: User ordered on-line rose flowers.
- d3: User searched diamond ring.
- d4: User selected white wedding gown, online flowers, 3 carat diamond ring.
