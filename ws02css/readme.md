body {
  background-color: #e0f7fa; /* Light cyan background */
  font-family: Arial, sans-serif;
  padding: 20px;
}

h1 {
  font-size: 2.5em; /* Adjusted font size for headings */
  color: #004d40; /* Dark teal color */
}

p {
  color: #00796b; /* Medium teal color for paragraphs */
}

/* --- Task 3: Add Padding and Margin --- */
.content-box {
  padding: 25px; /* Increased padding */
  margin: 30px 0; /* Margin on top and bottom, none on sides */
  background-color: #ffffff; /* White background for the box */
  border: 2px solid #004d40; /* Dark teal border */
  border-radius: 8px; /* Rounded corners */
  box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
}

/* --- Task 4: Format the Table and Form --- */
table {
  width: 75%;
  border-collapse: collapse;
  margin-top: 20px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

th, td {
  border: 1px solid #b2dfdb; /* Lighter border color */
  padding: 12px;
  text-align: left;
}

th {
  background-color: #80cbc4; /* Light teal header background */
  color: #004d40; /* Dark teal text in header */
  font-weight: bold;
}

tr:nth-child(even) {
  background-color: #e0f2f1; /* Very light teal for alternating rows */
}

/* Form Styles */
form {
  max-width: 400px;
  padding: 20px;
  margin-top: 30px;
  border: 1px solid #b2dfdb;
  border-radius: 5px;
  background-color: #ffffff;
  display: flex;
  flex-direction: column;
  gap: 15px; /* Space between form elements */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
}

label {
  font-weight: bold;
  color: #004d40;
}

input[type="text"], input[type="email"] {
  padding: 10px;
  border: 1px solid #b2dfdb;
  border-radius: 4px;
  transition: border-color 0.3s;
}

input[type="text"]:focus, input[type="email"]:focus {
  border-color: #004d40; /* Highlight on focus */
  outline: none;
}

input[type="submit"] {
  background-color: #004d40; /* Dark teal submit button */
  color: white;
  padding: 10px 15px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  font-weight: bold;
  transition: background-color 0.3s;
}

input[type="submit"]:hover {
  background-color: #00796b; /* Medium teal on hover */
}