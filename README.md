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
[ques_paper_gen_output.docx](https://github.com/user-attachments/files/32342036/ques_paper_gen_output.docx)
