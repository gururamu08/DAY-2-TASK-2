# DAY-2-TASK-2
<h2>AIM</h2>
   To Create Website for Registration Form.
<h2>CODE</h2>
```

<!DOCTYPE html>
<html>
    <head>
        <title>GURUMOORTHI R Task 2</title>
        <style>
            body{
                background-image: url(images.jpeg);
                background-repeat: no-repeat;
                background-attachment: fixed;
                background-size: 100% 100%;
            }
        
        </style>
        
    </head>

    <body>
       
        <center>
            <h1>Registration form</h1>
            <form>
                <div>
                    <label for="fname">First Name</label>
                    <input type="text" id="fname" name="fname" placeholder="Enter fname" required>
    
                </div>
                <br>
    
                <div>
                    <label for="lname">Last Name</label>
                    <input type="text" id="lname" name="lname" placeholder="Enter lname" required>

                </div>
                <br>

                <div>
                    <label for="gender">Gender</label>
                    <select id="gender" name="gender" required>
                        <option value="">select gender</option>
                        <option value="male">Male</option>
                        <option value="female">Female</option>
                    
                    </select>
                    
                </div>
                <br>

                <div>
                    <label for="Title">Title</label>
                    <label for="Mr.">Mr.</label>
                    <input type="radio" id="Mr." name="name" required>
                    <label for="Mrs.">Mrs.</label>
                    <input type="radio" id="Mrs." name="name" required>
                    <label for="Dr.">Dr.</label>
                    <input type="radio" id="Dr." name="name" required>
            

                </div>
                <br>

                <div>
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" placeholder="enter email" required>

                </div>
                <br>

                <div>
                    <label for="password">Password</label>
                    <input type="password" id="password" name="password" placeholder="enter password" requireds>

                </div>
                <br>
    
                <div element=".mydiv">
                    <button type="submit">Submit</button>
                    <button type="reset">Reset</button>

                </div>
                
                
    
            </form>
        </center>
        
    </body>
    ```
<h2>RESULT</h2>
   Thus the Website for Registration Form Created Successfully.
