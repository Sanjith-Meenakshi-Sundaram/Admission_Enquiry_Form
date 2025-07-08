# Admission_Enquiry_Form
## Date:7/7/2025

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:

```
<!DOCTYPE html>
<html>
<head>
  <title>Saveetha Engineering College - Admission Enquiry</title>
</head>
<body>
  <h1>Admission Enquiry Form</h1>
  <form>
    <label for="fullname">Full Name:</label><br>
    <input type="text" id="fullname" required><br><br>
    <label for="email">Email Address:</label><br>
    <input type="email" id="email" required><br><br>
    <label for="mobile">Mobile Number:</label><br>
    <input type="tel" id="mobile" required><br><br>
    <label>Gender:</label><br>
    <input type="radio" id="male">
    <label for="male">Male</label><br>
    <input type="radio" id="female">
    <label for="female">Female</label><br><br>
    <label for="dob">Date of Birth:</label><br>
    <input type="date" id="dob"><br><br>
    <label for="department">Department Interested:</label><br>
    <select id="department">
      <option >CSE</option>
      <option>ECE</option>
      <option>MECH</option>
      <option>CIVIL</option>
      <option>EEE</option>
    </select><br><br>
    <label for="qualification">Academic Qualification:</label><br>
    <textarea id="qualification" rows="3" cols="30"></textarea><br><br>
    <label for="address">Address:</label><br>
    <textarea id="address" rows="3" cols="30"></textarea><br><br>
    <label>Preferred Mode of Contact:</label><br>
    <input type="checkbox" id="contactEmail">
    <label for="contactEmail">Email</label><br>
    <input type="checkbox" id="contactPhone">
    <label for="contactPhone">Phone</label><br><br>
    <input type="submit">
  </form>

</body>
</html>

```

## Output:
![image](https://github.com/user-attachments/assets/d6c07913-fb37-4a72-a769-8182abe85a85)


## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
