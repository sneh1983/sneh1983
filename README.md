<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>CSS position</title>
        <style>
        body {
            font-family: fantasy;
            color: rgb(199, 177, 14);
        }
        
        #landscape {
            width: 250px;
            position: absolute;
            top: 20px;
            left: 10px;
            z-index: 1;
        }
        
        #winston {
            position: absolute;
            top: 50px;
            left: 50px;
            z-index: 2;
        }
        #hopper {
            position: absolute;
            top: 30px;
            left: 80px;
            z-index: 3;
        }
        
        h1 {
            position: fixed;
            z-index: 4;
            left: 30px;
        }
        
        #song {
            position: relative;
            top: 220px;
        }
        </style>
    </head>
    <body>

    <h1>Dance Party</h1>

    <img src="https://www.kasandbox.org/programming-images/landscapes/fields-of-grain.png" id="landscape">
    <img src="https://www.kasandbox.org/programming-images/avatars/Hopper-jumping.gif" id="hopper">
    <img src="https://www.kasandbox.org/programming-images/creatures/Winston.png" id="winston">
    
    <div id="song">
    <h3>Jamming to "Fields of Gold" by Sting</h3>
    <p>You'll remember me when the west wind moves<br>
Upon the fields of barley<br>
You'll forget the sun in his jealous sky<br>
As we walk in fields of gold
    </p>
    
    <p>So she took her love<br>
For to gaze awhile<br>
Upon the fields of barley<br>
In his arms she fell as her hair came down<br>
Among the fields of gold</p>

    <p>Will you stay with me, will you be my love<br>
Among the fields of barley<br>
We'll forget the sun in his jealous sky<br>
As we lie in fields of gold</p>
    </div>
    
    </body>
</html>
