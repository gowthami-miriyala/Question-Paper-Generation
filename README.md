# Question-Paper-Generation
📝 Automated Question Paper Generator

An application that automatically generates randomized, well-structured question papers from a stored question bank based on subject, difficulty level, marks distribution, and paper pattern — reducing the manual effort faculty spend creating exam papers every semester.

📌 Problem Statement

Creating question papers manually is time-consuming, prone to repetition, and hard to standardize across sections (easy/medium/hard, unit-wise weightage, total marks). This project automates the process: teachers/admins upload or maintain a question bank, define paper rules, and the system generates a ready-to-use paper (and optionally an answer key) in seconds.

✨ Features
🎯 Generate question papers by subject, unit, difficulty level, and marks
🔀 Randomized question selection to avoid repeated papers every time
📊 Supports marks-wise distribution (e.g., 5×2 marks, 5×5 marks, 3×10 marks)
🗂️ Question bank stored in a database (add/edit/delete questions)
📄 Export generated paper as PDF / Word document
🔑 Optional answer key generation
👤 Admin login to manage questions and subjects
🔍 Duplicate-question prevention within the same paper
🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript / React
Backend: Python (Flask / Django)
Database: MySQL / SQLite
PDF Generation: ReportLab / WeasyPrint / python-docx
Version Control: Git & GitHub
⚙️ How It Works
Admin adds questions to the database with metadata: subject, unit, difficulty, marks.
User selects paper pattern: total marks, number of questions per difficulty, units to cover.
The selection engine randomly picks questions matching the pattern while avoiding duplicates.
The system compiles the selected questions into a formatted paper.
Paper is exported as a downloadable PDF (with an optional answer key).
🔮 Future Enhancements
AI/NLP-based question generation from textbook content
Bloom's Taxonomy-based difficulty tagging
Multi-language support
Cloud deployment (Render/Heroku) with user accounts per institution
OMR-compatible answer sheet generation
📄 License

MIT License


output:


<img width="1360" height="759" alt="Image" src="https://github.com/user-attachments/assets/c5e4cbd7-ef01-45a8-b453-36ba859389b8" />

<img width="1359" height="723" alt="Image" src="https://github.com/user-attachments/assets/b6376822-f0ce-4b20-bc24-64a113e91920" />

<img width="1359" height="723" alt="Image" src="https://github.com/user-attachments/assets/5d6dea71-97dc-4f3c-be26-601a6aa01d09" />

<img width="1360" height="721" alt="Image" src="https://github.com/user-attachments/assets/4cad245e-2984-4fcc-a5da-03b52936c1b3" />

<img width="1360" height="708" alt="Image" src="https://github.com/user-attachments/assets/912b3e21-17f1-4a8d-b303-9858d1fe1fbb" />

<img width="1360" height="767" alt="Image" src="https://github.com/user-attachments/assets/3398bb86-08cf-4c62-b4a5-f466c38271d1" />

<img width="1360" height="763" alt="Image" src="https://github.com/user-attachments/assets/496a282a-dcdd-4f3e-bff7-8510b1cd1ff2" />

<img width="1359" height="765" alt="Image" src="https://github.com/user-attachments/assets/b1861d69-5ec4-40db-9fbe-bb2b43ed5eae" />

<img width="1360" height="768" alt="Image" src="https://github.com/user-attachments/assets/29cf8512-f0e4-4f4c-bd36-6b6f7ba71a4b" />

<img width="1360" height="634" alt="Image" src="https://github.com/user-attachments/assets/e5ff4f90-3058-400a-8936-516cd5d1b882" />

<img width="1360" height="765" alt="Image" src="https://github.com/user-attachments/assets/b4450abb-499c-45a5-beea-38cc7cf43672" />

<img width="1360" height="763" alt="Image" src="https://github.com/user-attachments/assets/95ed814b-f293-49ba-b7b0-bb3c6c8d8db5" />
