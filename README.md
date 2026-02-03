Biomedical Data Management using SQLite in Python

This project implements a simple relational database for a biomedical research study using SQLite in Python. The database manages patient information, clinical visits, and biological samples.

Three tables are used: Patients, Clinical_Visits, and Samples. Primary keys uniquely identify records, while foreign keys maintain relationships between patients and their visits and samples. Cascading delete ensures related records are removed automatically.

The script demonstrates CRUD operations including inserting data, reading data using SELECT and JOIN queries, updating sample storage location, and deleting a patient.

How to run:
1. Make sure Python is installed.
2. Place main.py in a folder.
3. Open terminal in that folder.
4. Run: python main.py
