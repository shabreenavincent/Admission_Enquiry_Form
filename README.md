# Admission_Enquiry_Form
## Date:

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
        <label for="fullname">Full Name:</label>
        <input type="text" id="fullname" name="Full Name"><br><br>
        <label for="Email Address">Email Address:</label>
        <input type="text" id="Email Address" name="Email Address"><br><br>
        <label for="mobile">Mobile number:</label>
        <input type="mobile" id="Mobile Number" name="Mobile Number"><br><br>
        <label>Gender:</label><br>
        <input type="radio"  name="gander" value="male">male
        <input type="radio" name="gander" value="female">male
        <input type="radio"  name="gander" value="male">Other<br><br>
        <label>Date.Of.Birth</label>
        <input type="date" name="Date.Of.Birth">
        <label>Department:</label><br>
        <input type="radio"  name="department" value="ECE">male
        <input type="radio" name="department" value="MECH">male
        <input type="radio"  name="department" value="CSE">Other<br><br>
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
![image](https://github.com/user-attachments/assets/68824e33-a2c5-4f48-91a3-3114af28841f)

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
