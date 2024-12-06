## Ex03 Time Table
## Date:
# 28/11/2024
## AIM
To write a html webpage page to display your slot timetable.

 ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using

tag in html.
## STEP 4
Add header row using

tag.
## STEP 5
Add your timetable using

tag.
## STEP 6
Execute the program using runserver command.

## PROGRAM
```html
<!doctype html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>TIME TABLE</title>
     <center>  
         <tilte>
            <img src="https://saveetha.ac.in/wp-content/uploads/2024/03/sec-logo-01as.png" width="1000px">
        </tilte>
     </center>
    </head>
    <br>
    <body background ="https://wallpapers.com/images/hd/star-colorful-surface-u2ppwaaeqn9ygk0i.webp">
        
        <center>  
          
        <table width="700px" border="3">
            <p> TIMETABLE - KELVIN (24900477)</p>
                <tr>
                <th bgcolor="cyan">date\time</th>
                <th bgcolor="cyan">    8-10   </th>
                <th bgcolor="cyan">  10-12  </th>
                <th bgcolor="cyan">   12-1  </th>
                <th bgcolor="cyan">    1-3    </th>
                <th bgcolor="cyan">    3-5    </th>
                </tr>
                <tr>
                <th bgcolor="blue">monday</th>
                <td bgcolor="yellow">FREE</td>
                <td bgcolor="yellow">web</td>
                <td bgcolor="yellow" rowspan="6">lunch</td>
                <td bgcolor="yellow">crypto</td>
                <td bgcolor="yellow">FREE</td>
                </tr>
                <tr>
                    <th bgcolor="blue">tuesday</th>
                    <td bgcolor="yellow">EDM</td>
                    <td bgcolor="yellow">calculas</td>
            
                    <td bgcolor="yellow">crypto</td>
                    <td bgcolor="yellow">FREE</td>
                    </tr>
                <tr>
                    <th bgcolor="blue">wednesday</th>
                    <td bgcolor="yellow">EDM</td>
                    <td bgcolor="yellow">CDS</td>
            
                    <td bgcolor="yellow">mentor meet</td>
                    <td bgcolor="yellow">FREE</td>
                </tr>   
                <tr>
                    <th bgcolor="blue">thursday</th>
                     <td bgcolor="yellow">physics</td>
                    <td bgcolor="yellow">python</td>
            
                    <td bgcolor="yellow">web</td>
                      <td bgcolor="yellow">FREE</td>
                    
                </tr> 
                <tr>
                    <th bgcolor="blue">friday</th>
                    <td bgcolor="yellow">FREE</td>
                    <td bgcolor="yellow">FREE</td>
            
                    <td bgcolor="yellow">python</td>
                    <td bgcolor="yellow">FREE</td>
                </tr>   
                <tr>
                    <th bgcolor="blue">saturday</th>
                    <td bgcolor="yellow"></td>
                    <td bgcolor="yellow">physics</td>
            
                    <td bgcolor="yellow">calculus</td>
                    <td bgcolor="yellow">web</td>
                </tr>
        </table>
        </center>
        <br>
            <center>
            <table width="500px" border="3" background="https://static.vecteezy.com/system/resources/thumbnails/018/800/338/small/colorful-grunge-art-painting-effect-of-light-hot-colored-of-sunset-clouds-cloud-on-the-sunset-sky-background-burning-background-abstract-watercolor-grunge-background-design-vector.jpg"> <tr>
                <th>s.no</th>
                <th>Subject code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI302</td>
                <td>Engineering Design and Modelling</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI302</td>
                <td>Python programming</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19EE404</td>
                <td>Fundamentals of crypto Currency</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EY708</td>
                <td>Career Development Skills</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19MA201</td>
                <td>Calculus and Marix Algebra</td>
            </tr>
            <tr>
                <td>7</td>
                <td>SH3214</td>
                <td>Physics for Quantum Computing</td>
            </tr>
        </table>
        </center>
        
    </body>
</!doctype html>
```
## OUTPUT
![Screenshot 2024-12-06 130142](https://github.com/user-attachments/assets/82d06131-ffec-4b57-b19d-b48e235303a5)


RESULT
