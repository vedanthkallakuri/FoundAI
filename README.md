FoundAI
FoundAI is an innovative solution to help students on college campuses find their lost belongings, leveraging advanced AI techniques and machine learning to make things easy. Through a simple and intuitive web platform, FoundAI uses PyTorch-based image classification and object detection to help people find their lost items faster and more accurately.

What It Does
FoundAI utilizes PyTorch image classification and object detection to provide a seamless experience for users who have lost an item. Here's how it works:

Image Search: Upload a photo of your lost item, and FoundAI will return similar items that have been found across your campus.
Text Search: Don’t have a picture? Simply describe your lost item in the search bar. Using object detection, our AI will match your description with found items from other users.
Whether you have an image or just a description, FoundAI helps you connect with lost and found items quickly and easily.

How We Built It
Tech Stack:
Frontend: React, JavaScript
Backend: Python, Flask
Database: MongoDB
Cloud Storage: AWS S3
Machine Learning: PyTorch (ResNet18 model)

Architecture:
The frontend is built using React and interacts with the backend via REST API calls.
The backend is built using Flask to handle requests, while MongoDB stores lost and found information and supports fast search queries.
AWS S3 is used to upload and store item images securely.
For search functionality, we use MongoDB search indexes to match textual queries, and PyTorch (ResNet18 model) is used for matching images based on their content.

Image Classification:
The PyTorch ResNet18 model evaluates images of lost items and matches them with found items, ranking similarity based on pre-trained neural networks.

Integration:
Users can upload images to AWS S3, which are then linked in the MongoDB database. This allows the system to return visually similar items quickly and accurately.


Accomplishments We're Proud Of
Accurate Image Matching: We successfully fine-tuned our image classification model, which allows users to upload a picture of their lost item and receive accurate matches.
Optimized Search Algorithm: Filtering the ImageNet dataset to focus on relevant keywords improved the search accuracy and overall performance.
Scalable Platform: We built a platform that is easy to use, scalable, and robust, capable of handling large datasets and user interactions efficiently.

What We Learned
Throughout this project, we learned how to:

Process and classify image data using PyTorch and fine-tune machine learning models for real-world applications.
Store and retrieve large datasets using MongoDB and design effective search indexes for better query performance.
Work with AWS S3 to host and serve images, and integrate cloud storage solutions into web applications.
Build full-stack applications using React, Flask, and MongoDB, gaining valuable experience in frontend, backend, and database management.

What's Next for FoundAI?
The next steps for FoundAI include:

Augmented Reality (AR): We're exploring the integration of AR to help users visualize where their lost items might be in real-time based on other users’ reports.
Improving Image Classification: We aim to enhance the accuracy and speed of our image classification model.
Expanding Platform: FoundAI plans to support multiple campuses and institutions, expanding the reach and usefulness of the platform.
Contributing
If you'd like to contribute to FoundAI, please feel free to fork the repository, open an issue, or submit a pull request. Contributions of any kind are welcome!


MORE INFO HERE: https://devpost.com/software/foundai
