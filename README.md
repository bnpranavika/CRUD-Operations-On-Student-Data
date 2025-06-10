✅ Summary: RESTful Student API with Node.js and Express
This project is a basic RESTful API built using Node.js and Express to manage student records.

⚙️ Features
CRUD operations on student data:

Create (POST)

Read (GET)

Update (PUT)

Delete (DELETE)

Data is stored in-memory (not persisted after server restart).

Ideal for understanding API fundamentals and route handling.

🧱 Tech Stack
Node.js (JavaScript runtime)

Express (backend web framework)

🔍 API Endpoints
GET /api/students – Get all students

POST /api/students – Add a new student

PUT /api/students/:id – Update a student by ID

DELETE /api/students/:id – Delete a student by ID

🧪 Sample Data
json
Copy code
[
  {
    "id": 1,
    "name": "Swayam",
    "age": 21,
    "course": "Mathematics"
  }
]
🚀 How to Run
Initialize project with npm init -y

Install Express: npm install express

Run: node server.js

Access at: http://localhost:3000/api/students
![image](https://github.com/user-attachments/assets/9768f7c1-7892-4b79-b5a3-849fecca524f)
![image](https://github.com/user-attachments/assets/48ba8d7b-8e0b-4b26-9777-24c9ddfb5198)
![image](https://github.com/user-attachments/assets/87829861-dd80-4110-85f2-8f9f4bce6a5c)
![image](https://github.com/user-attachments/assets/0f31966b-d1a9-4815-8027-08a00d079978)
![image](https://github.com/user-attachments/assets/e2100bd8-3c14-4033-9700-d07bf998d70a)
