# Admission_Enquiry_Form
## Date:07-07-2025

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
<html>
    <head>
        <title>Saveetha Engineering College - Admission Enquiry</title>
    </head>
    <body>
        <h1>Admission Enquiry Form</h1>
       <form>
        <label >Full Name:</label>
        <input type="text"><br><br>
        <label >Email Address:</label>
        <input type="text" ><br><br>
        <label >Mobile number:</label>
        <input type="mobile"><br><br>
        <label>Gender:</label><br>
        <input type="radio"  name="gander" value="male">
        <label>Male</label>
        <input type="radio" name="gander" value="female">
        <label>Female</label>
        <input type="radio"  name="gander" value="male">
        <label>Others</label>
        <br><br>
        <label>Date.Of.Birth:</label><br>
        <input type="date" name="Date.Of.Birth"><br><br>
        <label>Department:</label><br>
        <input type="radio"  name="department" value="ECE">
        <label>ECE</label>
        <input type="radio" name="department" value="MECH">
        <label>MECH</label>
        <input type="radio"  name="department" value="CSE">
        <label>CSE</label><br><br>
            <label>Qualification:</label><br>
            <textarea name="qualification"></textarea><br><br>
            <label>Address:</label><br>
            <textarea name="address"></textarea><br><br>
            <label>Contact Mode:</label>
            <input type="checkbox" name="contactMode" value="Email">Email
            <input type="checkbox" name="contactMode" value="Phone">Phone<br><br>

           <input type="submit" value="Submit">
       </form>
    </body>
</html>
```
## Output:
![image](https://github.com/user-attachments/assets/5cea4ee7-a6f4-4df4-abbe-f19681f54025)


## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
