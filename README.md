# Billions-Quiz
🌐 Billions Network Identity and Verification Quiz

This is a single-file, interactive web quiz designed to test and reinforce knowledge about the Billions Network, focusing on its core principles of digital identity, uniqueness, and verification protocols.

The application is built to be fast, responsive, and features a sleek, dark aesthetic inspired by high-stakes finance and technology themes.

✨ Features

Dynamic Difficulty: Choose from Easy (12s per Q), Medium (8s per Q), or Hard (4s per Q) modes, which adjust both the question count and the time pressure.

Real-Time Leaderboard: Scores are saved and displayed on a global leaderboard using Firebase Firestore, filtered by difficulty level.

Performance Tracking: Tracks and displays critical metrics, including score percentage, maximum correct streak, and average time per question.

Shareable Results: Upon completion, a visual Results Card is generated that users can download as a PNG or share directly to X (Twitter) to prove their expertise.

Responsive Design: Optimized for seamless interaction on both mobile devices and desktop browsers.

🛠️ Technology Stack

This project is intentionally designed as a single, self-contained file for easy deployment and portability.

Frontend: HTML5, Vanilla JavaScript (ES6+), and CSS.

Styling: Tailwind CSS via CDN for utility-first, responsive styling.

State Management/Storage: Firebase Firestore is used for real-time persistence of the global leaderboard data.

Image Export: html2canvas is used to convert the final results card into a high-quality PNG image for download.
