# 🏋️ PocketCoach

PocketCoach is an advanced fitness web application that combines **machine learning**, **computer vision**, and **modern web technologies** to help users improve their training quality, track progress, and manage nutrition.

The system is built using:

- **Backend:** Python (FastAPI)
- **Frontend:** React
- **Machine Learning:** pose estimation, body proportions analysis, movement pattern recognition
- **Cloud storage:** secure media handling for images and videos

The main goal of PocketCoach is to provide **personalized training analysis**, reliable feedback on exercise technique, and comprehensive fitness tracking in one platform.

---

## 🚀 Main Features

- AI-based exercise form analysis  
- Automatic body proportions estimation from photos  
- Smart diet and calorie tracking  
- Exercise database with videos and detailed descriptions  
- Social feed with posts, comments, likes, images and videos  
- Secure authentication with optional passphrase  
- Cloud-based media storage  
- Advanced statistics and self-assessment tools  

---

## 🧩 Application Pages & Functionality

---

### 🔐 1. Register & Login

The authentication system provides a high level of security:

- Standard registration and login
- **Strong password policy** (length, complexity, validation)
- Optional **passphrase system**:
  - User can define a passphrase consisting of **four custom words**
  - Passphrase is optional
  - If enabled, it is required during every login
- Protection against weak credentials and brute-force attempts

🎬 Demo video:  

https://github.com/user-attachments/assets/9713f605-1297-4adc-90b2-bb50b040589b


---

### 🏠 2. Home (Social Feed)

The home page acts as a social hub for users:

- Displays all posts in a **randomized layout**
- Infinite scrolling
- Filtering and browsing posts
- Creating new posts
- Liking posts and comments
- Commenting on posts
- Uploading **images and videos**

All uploaded media is **securely stored in the cloud** and validated before processing.

🎬 Demo video:  
`HomePage.mp4`

---

### 🏋️ 3. Exercises

The exercise page provides access to a large exercise database:

- Over **200 exercises** with video demonstrations
- Detailed information for each exercise:
  - Target muscles
  - Exercise type
  - Execution instructions
  - Tips and common mistakes
  - Description
- Filtering and searching exercises
- Liking favorite exercises
- Creating **custom exercises** with:
  - Own videos
  - Images
  - Descriptions

🎬 Demo video:  
`Exercises.mp4`

---

### 📐 4. Body Proportions

This section is part of the user profile and includes:

- Basic data:
  - Height
  - Weight
  - BMI
- Advanced measurements calculated automatically by an ML model:
  - Torso length
  - Arm length
  - Leg length
  - Shoulder width
  - Hip width
  - Ratios and proportions

The model estimates these values from user-uploaded photos.

These parameters are later used to **personalize exercise form analysis** and improve accuracy.

🎬 Demo video:  
`BodyProportions.mp4`

---

### 📝 5. Self Assessment

This page allows users to:

- Store personal records for selected exercises
- Fill in self-assessment questionnaires:
  - Mobility
  - Endurance
  - Strength balance
  - Stability

The collected data can be useful for:

- Long-term progress tracking
- Future trainer integration
- Personalized recommendations

🎬 Demo video:  
`SelfAssessment.mp4`

---

### 🎥 6. Exercise Analysis

One of the core features of PocketCoach.

Workflow:

- User uploads a video of an exercise
- Selects the performed exercise type
- ML model:
  - Detects movement patterns
  - Splits video into repetitions
  - Classifies each repetition as **correct or incorrect**
  - Detects mistakes and explains what should be improved

Features:

- Repetition counter
- Accuracy percentage
- Detailed feedback
- Timeline view with:
  - Correct repetitions
  - Incorrect repetitions
  - Clickable timestamps

All analysis is performed automatically using computer vision and ML models.

🎬 Demo video:  
`ExerciseAnalysis.mp4`

---

### 🥗 7. Diet Tracker

The diet tracker helps users manage nutrition efficiently:

- Automatic daily calorie requirement calculation based on goals
- Macro tracking (proteins, fats, carbohydrates)
- Daily nutrition history
- Meal management:
  - Add meals manually
  - Scan barcodes
  - Use favorite meals
  - Select recipes
- Each day is tracked separately

Integration with the recipe system allows quick meal creation.

🎬 Demo video:  
`DietTracker.mp4`

---

### 📖 8. Recipes

Recipe management system:

- Search through recipes
- View:
  - Ingredients
  - Preparation steps
  - Calories
  - Macros
- Create custom recipes
- Like and save recipes
- Advanced filtering:
  - Diet type
  - Calories
  - Macros
  - Ingredients
  - Preferences

🎬 Demo video:  
`Recipes.mp4`

---

## 🛠️ Technology Stack

- Python (FastAPI)
- React
- PostgreSQL
- Docker
- YOLO / Pose Estimation models
- Custom ML models for body analysis and movement recognition
- Cloud object storage for media
- JWT authentication

---

## 📌 Project Status

The project is actively developed and extended with:

- Trainer dashboards
- Training plans
- Advanced analytics
- Mobile version

---

## 📫 Contact

Email: bartosz.malujda@gmail.com  
LinkedIn: https://www.linkedin.com/in/bartosz-malujda-2a3079306/
