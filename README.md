# Fitness Recommender System Using Natural Language Processing

## Overview
This repository contains a personalized fitness recommendation system developed using Natural Language Processing (NLP) techniques, specifically BERT (Bidirectional Encoder Representations from Transformers). The system is designed to suggest exercise routines tailored to individual preferences, such as fitness level, target body part, and exercise type.

## Project Description
In personalized fitness, one of the main challenges is finding exercise routines that match individual preferences. This project addresses this challenge by building a fitness recommender system that uses NLP techniques to offer personalized exercise suggestions. The system takes user inputs—such as fitness level, target body part, and exercise type—to recommend exercises from a set of options. By converting both the exercise details and user preferences into vectors, it ranks exercises based on how closely they match the user’s criteria. The system also includes a filtering feature to give higher priority to exercises that use the user’s preferred equipment.

## Research Question
How can personalized workout recommendations based on a gym-goer’s experience level and fitness goals enhance adherence to regular exercise and improve long-term fitness outcomes? Are the recommendations useful and diverse enough to be beneficial to anyone, from a frequent gym-goer to a newbie?

## Features
- **Personalized Recommendations**: Tailored exercise suggestions based on user inputs.
- **NLP Techniques**: Utilizes BERT for converting text to vectors and calculating similarity.
- **Equipment Filtering**: Prioritizes exercises that use the user’s preferred equipment.
- **Exploratory Data Analysis**: Visualizations to understand the distribution of exercise types, levels, and equipment used.

## Installation
To run this project, you need to have Python installed along with the following libraries:
- pandas
- scikit-learn
- transformers
- torch
- matplotlib

You can install these dependencies using pip:
```bash
pip install pandas scikit-learn transformers torch matplotlib
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/fitness-recommender-system.git
```
2. Navigate to the project directory:
```bash
cd fitness-recommender-system
```
3. Run the main script:
```bash
python main.py
```
4. Follow the prompts to enter your fitness level, target body part, type of training, and preferred equipment.

## Example
Here’s an example of how the system works:
```python
Enter your level (Beginner, Intermediate, Expert): Intermediate
Enter the body part you want to train (e.g., Abdominals, Legs, Arms): Abdominals
Enter the type of training (Strength, Cardio, Powerlifting, Stretching): Strength
Do you have a preference for equipment? (e.g., Dumbbell, Barbell, Body Only): Body Only
```
The system will then provide a list of recommended exercises based on your inputs.

## Conclusion
The fitness recommender system demonstrates how NLP techniques can improve exercise recommendations based on user preferences. By using cosine similarity, the system effectively suggests exercises that match the user’s fitness level, target body part, and type of training. This project lays the groundwork for applying advanced machine learning models like BERT in personalized fitness apps, offering potential for future improvements and innovations.

## Authors
- Landon Bragg
- Ben Kim
