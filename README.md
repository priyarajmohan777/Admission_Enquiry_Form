# Admission_Enquiry_Form
## Date: 07-07-2025

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
<html lang="en">
   

    <head>
         <title>Admission Enquiry Form</title>
        
    
    </head>
    <body>

        <h1 align="center">Admission Enquiry Form</h1>

        <form>
            
            <label>Name</label><br>
            <input type="text" name="name" placeholder="Enter your name" required> 
            <br> <br>

            <label>Email</label><br>
            <input type="email" name="email" placeholder="Enter email"> 
            <br> <br>


            <label>Mobile Number</label><br>
            <input type="number" name="mobile" placeholder="Enter number"> 
            <br> <br>

            <label>Gender</label><br>
            <input type="radio" name="gender"> Male
            <br> 
            <input type="radio" name="gender">Female
            <br> <br>

            <label>Date of Birth</label><br>
            <input type="text" name="dob" placeholder="Enter your name"> 
            <br> <br>

            <label>Department Interested</label><br>
            <select>
                <option value="CSE">CSE</option>
                <option value="ECE">ECE</option>
                <option value="EEE">EEE</option>
                <option value="AIDS">AIDS</option>
                <option value="AIML">AIML</option>
                <option value="Choose a department" selected>Choose a department</option>
            </select> 
            <br> <br>

            <label>Academic qualifications</label><br>
            <textarea name="qualifications" row="5" col="5"> </textarea>
            <br> 
            <br>

             <label>Address</label><br>
            <textarea row="5" col="5"> </textarea> 
            <br> <br>

             <label>Mode of Contact</label><br>
            <input type="checkbox" name="contact"> Email
            <input type="checkbox" name="contact"> Phone

            <br> <br>

             
            <input type="submit" value="Submit"> 
            <br> <br>

        </form>
    </body>
</html>
         
```
## Output:
![image](https://github.com/user-attachments/assets/f9097b51-64d3-4107-9e32-7d7d34681767)

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
