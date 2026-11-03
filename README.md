

<!DOCTYPE html>

<html lang="en">

<head>

&#x20;   <meta charset="UTF-8">

&#x20;   <meta name="viewport" content="width=device-width, initial-scale=1.0">

&#x20;   <title>Student Management System</title>

&#x20;   <link rel="stylesheet" href="style.css">

</head>

<body>



&#x20;   <header>

&#x20;       <h1>Student Management System</h1>

&#x20;       <p>Manage Student Records Easily</p>

&#x20;   </header>



&#x20;   <div class="container">



&#x20;       <div class="summary">

&#x20;           <h2>Total Students: <span id="totalStudents">0</span></h2>

&#x20;       </div>



&#x20;       <section class="form-section">

&#x20;           <h2>Add Student Details</h2>



&#x20;           <form id="studentForm">

&#x20;               <input type="text" id="name" placeholder="Student Name" required>

&#x20;               <input type="text" id="roll" placeholder="Roll Number" required>

&#x20;               <input type="email" id="email" placeholder="Email Address" required>

&#x20;               <input type="text" id="course" placeholder="Course" required>

&#x20;               <input type="number" id="year" placeholder="Year" min="1" max="6" required>



&#x20;               <button type="submit" id="submitBtn">Add Student</button>

&#x20;           </form>

&#x20;       </section>



&#x20;       <section class="records">

&#x20;           <h2>Student Records</h2>



&#x20;           <input type="text" id="search"

&#x20;           placeholder="Search by name or roll number">



&#x20;           <div class="table-container">

&#x20;               <table>

&#x20;                   <thead>

&#x20;                       <tr>

&#x20;                           <th>Name</th>

&#x20;                           <th>Roll Number</th>

&#x20;                           <th>Email</th>

&#x20;                           <th>Course</th>

&#x20;                           <th>Year</th>

&#x20;                           <th>Actions</th>

&#x20;                       </tr>

&#x20;                   </thead>

&#x20;                   <tbody id="studentList"></tbody>

&#x20;               </table>

&#x20;           </div>

&#x20;       </section>



&#x20;   </div>



&#x20;   <script src="script.js"></script>

</body>

</html>



