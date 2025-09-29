# FitPrint

## Overview
FitPrint is a smart fitness assistant designed to personalize and enhance your workout experience. The platform combines web technologies and machine learning to help users track their fitness journey, receive AI-driven recommendations, and interact with features like equipment identification, custom workout plans, and real-time form correction. The project includes:

- **User Profile Management:** Track personal data, progress, and preferences.
- **Equipment Identification:** Upload images to identify gym machines and get tailored workout suggestions.
- **Custom Workout Plans:** Automatically generate daily workout routines based on identified equipment and user goals.
- **AI Trainer:** Interactive sessions for exercises like pushups, with real-time feedback and audio cues.
- **Form Correction:** Uses computer vision to analyze exercise form and provide corrective feedback.


## My Contributions: Machine Learning & AI
I developed the machine learning components that power FitPrint's intelligent features:

- **Pose Estimation & Form Correction:** Implemented real-time pose detection using [MediaPipe](https://google.github.io/mediapipe/) and OpenCV. The system calculates joint angles and tracks movement to assess exercise form, providing instant feedback to users during workouts.
- **YOLO-based Equipment Detection:** Integrated YOLO (You Only Look Once) models for fast and accurate identification of gym equipment from user-uploaded images, enabling automated workout plan generation.
- **Audio Feedback System:** Integrated automatic audio cues using pre-generated mp3 files to motivate and guide users through repetitions.
- **Custom Plan Generation:** Built logic to identify gym equipment from user input and generate personalized workout plans using ML-driven recommendations.

These ML features enable FitPrint to deliver a truly interactive and adaptive fitness experience, making workouts safer, more effective, and engaging for users.
