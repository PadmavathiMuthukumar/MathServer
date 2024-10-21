# Ex.05 Design a Website for Server Side Processing
## Date: 21-10-2024

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
P = I<sup>2</sup>R
<br> P --> Power (in watts)
<br> I --> Intensity
<br> R --> Resistance

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
    <head>
        <title>power</title>
        <style>
            .box{
                width: 500px;
                height: 500px;
                border: 5px solid black;
                border-radius: 50px;
                background-image: url('https://img.freepik.com/premium-photo/light-bulb-pastel-color-tone-background_1028938-124350.jpg');

                align-content: center;
                justify-items: center;
               
                
            }
            body{
                display: flex;
                align-items: center;
                justify-content: center;
                font-size: larger;
                background-color: black;
                background-size: cover;

            }
            input[type="text"]{
                height: 30px;
                width: 200px;
                border-radius: 5px;
                border: 2px solid black;
                background-color: rgb(227, 222, 222);
            }
            input[type="button"]{
                height: 30px;
                width: 200px;
                border-radius: 5px;
                border: 2px solid black;
                font-size: large;
            }
            h1{
                position: absolute;
                top: 1%;
                align-items: center;
                color: white;
            }
            #result{
                font-size: large;
                font-weight: bold;
                width: 300px;
                height: 50px;
                border: 2px solid black;
                background-color: darkgrey;
                color: rgb(6, 15, 19);
                text-align: center;
                align-content: center;
                border-radius: 5px;
            }
        </style>
    </head>
    <script>
        function power(){
            var a=Number(document.getElementById("current").value);
            var b= Number(document.getElementById("Resistance").value);
            var value=a*a*b;
            document.getElementById("result").textContent="Power: "+ value +"watts"
        }
    </script>
    <body>
        <h1>Padmavathi M (212223040141)</h1>

        <div class="box">
            <h2 align="center"> Power of a lamp filament in an Incandescent bulb</h2>
            <label>Current</label><br>
            <input type="text" id="current"><br><br>
            <label>Resistance</label><br>
            <input type="text" id="Resistance"><br><br>
            <input type="button" value="calculate power" onclick="power()">
            <p id="result"></p>

        </div>
    </body>
</html>
```
## HOMEPAGE:
![Screenshot 2024-10-21 220143](https://github.com/user-attachments/assets/d4c44f89-dda4-4864-aef2-1e3a43ad0793)

## RESULT:
The program for performing server side processing is completed successfully.
