<!DOCTYPE html>
<html>
    <head>
        <title> simple table</title>
        <h5> people information </h5>
         <table border="1">


            <tr>
            <th> Name </th>
            <th> Age</th>
            <th> city</th>

            </tr>

             <tr>
                 <td>John Doe </td>
                <td>Jane Smith </td>
                <td>Sam Brown</td>                
            </tr>
             
            <tr>
                <td> 30 </td>
                <td> 25</td>
                <td> 35 </td>

            </tr>
       <tr>
    <td> New york</td>
    <td> london</td>
    <td> sydney</td>
</tr>


        </table>
 
___________________________________________________________________






 <h5> simple table</h5>



    <table border="2">

        <tr>
            <th> Name</th>
            <th> Age</th>
            <th> Country</th>
        </tr>



    <tr>
        <td>John </td>
        <td>Maria </td>
        <td>Ali </td>
        
    </tr>




    <tr>
       <td>25</td>
       <td> 30</td>
       <td>22</td>
       </tr>




       <tr>
       <td> USA</td>
       <td> Canada</td>
       <td> Jordan</td>
       </tr>




  </table>

___________________________________________________________________




<label for="name">Name:</label>
 <input type="text" id="name" name="name" required><br><br>

 <label for="email">email: </label>
 <input type="text"id="email" name="email"><br><br>

 <label for="country">Country:</label>
 <select id="country" name="Country" required >
    <option value=""> select your country </option>
    <option value="Jordan"> Jordan </option>

    </select>

<br>
    <label>Gender:</label>
    <input type="radio" id="female" name="gender" value="female"required>
    <label for="female"> Female</label>
    <input type="radio" id="male" name="gender" value="male"required>
    <label for="male"> Male</label><br><br>
    <label for="message">Message</label>
    <textarea id="message" name="message"rows="6"cols="50" placeholder="Type your message here"></textarea>

        <input type="checkbox" id="subscribe" name="subscribe">
        <label for="subscribe">Subscribe</label>
        <br>
        
           <input type="Submit" value="Submit">

           ______________________________________________________________


<video width="350" height="200" controls>
    <src="https://www.youtube.com/watch?v=22VOzqS_9ms"></src>
</video>

______________________________________________________________

<h3>Learn About Two Subjects</h3>
<div style="border:2px solid black; padding: 11px;">
    <h4>Technology</h4>
    
    <p>Technology is constantly evolving, bringing about new innovations that
        shape the world. It affects various aspects of daily life, from communication to 
        transportation. In the past few decades, the rise of the internet 
        and mobile devices has revolutionized how people interact and work.</p>

        <img src="comp.jpg" alt="comp"width="100" height="100">

        <h3>What we learn about Technology:</h3>

        <ol>
            <il>1. Impact of technology on communication</il>
            <il>2.Technological advancements in medicine </il>
            <il>3.Future of artificial intelligence</il>
            
        </ol>
         
        <h3>Key aspects of technology:</h3>
        <ul>
            <il>Innovation </il>
            <il>Connectivity </il>
            <il>Data privacy </il>

        </ul>

            </div>
                <pre></pre>
               <div Style="border: 2px solid black; padding: 10px;">
               <h2>Environment</h2>
              <p>The environment is the natural world that surrounds us.</p>
               </div>
               ___________________________________________________________________

               <h3>Employees - Project Information</h3>  
               <table border="1" style="border-collapse: collapse; width: 100%; text-align: left;">
                <tr>
                     
                    <th>Manager Name</th>
                    <th>Employee Name</th>
                    <th>Project Name</th>

                </tr>
                <tr>
                         <td rowspan="4">Alice Johnson</td>
                         <td>John Smith</td>
                         <td rowspan="4">Website Redesign</td>
                </tr>
                <tr>
                      <td>sarah parker</td>

                </tr>
                <tr>
                    <td>Kim Lee</td>
                </tr>
                <tr>
                    <td>Anna Brown</td>
                </tr>
                <tr>
                    <td rowspan="3">Bob Anderson</td>
                    <td>Mike Davis</td>
                    <td rowspan="3">Marketing Campaign</td>
                </tr>
                <tr>
                    <td>James Wilson</td>
                </tr>
                <tr>
                    <td>David Clark</td>
                </tr>
                <tr>
                    <td rowspan="2">Carol White</td>
                    <td>Emma Martinez</td>
                    <td rowspan="2">Mobile App Development</td>
                </tr>
                <tr>
                    <td>Chris Green</td>
                </tr>
            </table>


        <br>
        ______________________________________________________________

           
           <h1 style="text-align: center;">Drinks Table</h1>
           <table>
            <meta charset="UTF-8">
                   <meta name="viewport" content="width=device-width, initial-scale=1.0">
                   <style>
                    table {
                        border-collapse: collapse;
                        margin: 20px auto;
                        text-align: center;
                        font-family: Arial, sans-serif;
                    }
                    th, td {
                        border: 1px solid black;
                        padding: 20px;
                    }
                </style>
   
               <tr>
                   <td colspan="2">Drinks</td>
               </tr>
               <tr>
                   <td>Coffee</td>
                   <td>Tea</td>
               </tr>
           </table>      
        ______________________________________________________________

        <h3>Drinks table</h3>
        <meta charset="UTF-8">
        <table border="1" >
             <tr>
                <td rowspan="4"> Drinks</td>
             </tr>
             <tr>

                <td rowspan="2" >Coffee</td>
             </tr>
              <tr align="center">
                <td rowspan="3"> tea</td> 
                <td>Green Tea</td>
             </tr>
             <tr>
            </tr>
            <tr align="center">
                <td>Herbal Tea</td>
            </tr>
           </Table>
               
             </tr>


        </table>
    ______________________________________________________________

          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
           <title>Table with colspan and rowspan</title>

            <body>
         <h1>Employees-Project Information</h1>
          <table border="1px">
         <tr>
        <th>Manager Name</th>
       <th>Empoyee Name</th>
       <th>Project Name</th>
       </tr>
         <tr>
      <td rowspan="3">Alice Johnson</td>
      <td>John Smith</td>
       <td rowspan="3">Website Redsign</td>
    
           </tr>
           <tr>
     <td>Sarah Parker</td>
         </tr>
                   <tr>
           <td>Kim Lee</td>
                 </tr>
             <tr>
              <td rowspan="3">Bob Anderson</td>
              <td>Anna Brown</td>
              <td rowspan="3">Marketing Campaign</td>
         </tr>
         <tr>
    <td>Mike Davis</td>
    </tr>
      <tr>
    <td>James Wilson</td>
     /tr>
        <tr>
    <td rowspan="3">Carol White</td>
    <td>David Clark</td>
    <td rowspan="3">Mobile App Development</td>
          </tr>
     <tr>
    <td>Emma Martinez</td>
    </tr>
       <tr>
    <td>Chris Green</td>
      </tr>
          <pre></pre>
         </table> 
<br>
         ______________________________________________________________
    
         <table border="1" cellspacing="0" cellpadding="10">
            <tr>
            <th colspan="2">Login Form</th>
        </tr>
        <tr>
            <td><label for="Email">Email address</label></td>
            <td><input type="text" name="Email" id="Email"></td>
        </tr>
        <tr>
            <td><label for="Password">Password</label></td>
            <td><input type="password" name="Password" id="Password"></td>
        </tr>
        <tr>
            <td colspan="2" align="center"><input type="submit" value="login" ></td>
        </tr>
        </table>
        ______________________________________________________________

             <h1>Student Registration Form</h1>
                 <p>Welcome to the student registration page. Please fill out the form below to register for your desired courses.</p>
                   <h2>Personal Information</h2>
                    <label for="fname">Full Name: </label>
                    <input type="text" name="fname" id="fname"><br>
              <pre></pre>
              <label for="email">Email: </label>
                     <input type="text" name="email" id="email"><br>
                  <pre></pre>
                <label for="date">Date of Birth: </label>
                                        <input type="date" name="date" id="date">
                <pre></pre>
                <label for="gender">Gender: </label>
            <input type="radio" name="gender" id="gender"> Female
              <input type="radio" name="gender" id="gender"> Male <br><br>
            <h2>Course Selection</h2>
                  <label for="course">Please select the courses you want to enroll in:</label><br>
            <input type="radio" name="course" id="course"> Course 1: Mathematics <br>
               <input type="radio" name="course" id="course"> Course 2: Computer Science <br>
                        <input type="radio" name="course" id="course"> Course 3: Physics <br> <br>
               <button type="submit">Submit</button>
                  <button type="reset">Reset</button> <br><br>
    <h2>Available Courses</h2> <br>
    <table border="1">
        <tr>
            <th>Course ID</th>
            <th>Course Name</th>
            <th>Instructor</th>
            <th>Duration</th>
        </tr>
        <tr>
            <td>101</td>
            <td>Mathematics</td>
            <td>Dr. Smith</td>
            <td>6 months</td>
        </tr>
        <tr>
            <td>102</td>
            <td>Computer Science</td>
            <td>Dr. Lee</td>
            <td>6 months</td>
        </tr>
        <tr>
            <td>103</td>
            <td>Physics</td>
            <td>Dr. Johnson</td>
            <td>6 months</td>
        </tr>
    </table>
</head>
</html>
