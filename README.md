# HTML-form
Revealing proper form using html form and table tag
<!-- CODE -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML FORM</title>
    <style>
        * {
            margin:0;
            padding:0;
        }
        #form {
            margin:100px;
            padding:100px;
            padding-left: 150px;
            margin-left:500px;
            background-color: #243766;
            width: 300px;
            height: 250px;
        }
        span {
            font-family: Verdana;
            font-size:25px;
            color: white;
            text-align: center;
            
        }
        #name {
            width:150px;
            height: 35px;
            border-radius: 3px;
            margin-top:15px;
        }
        #email {
            width:150px;
            height:35px;
            border-radius: 3px;
        }
        #message {
            width:150px;
            height:75px;
            border-radius: 3px;
        }
        #nameandsurname {
            color:white;
            font-family:Verdana;
        }
        #emailadress {
            color:white;
            font-family:Verdana;
        }
        #messagetext {
            color:white;
            font-family:Verdana;
        }
        #submit {
            margin-top:50px;
            margin-left:50px;
            width:90px;
            height:35px;
        }
        #submit:hover{
            background-color: green;
        }
        #reset {
            margin-top:50px;
            margin-left:50px;
            width:90px;
            height:35px;
        }
        #reset:hover {
            background-color: red;
        }
    </style>
</head>
<body>
    <div id="form"> 
    <table>
        <form action="#">
            <span> Contact Me </span> 
            <tr> </tr>
            <tr>
                <td id="nameandsurname"> Name and Surname : </td> 
                <td> <input type="text" placeholder="Name and Surname..." required id="name"> </td>
            </tr>
            <tr>
                <td id="emailadress"> Email adress : </td> 
                <td> <input type="email" placeholder="Your email adress..." required id="email"></td>
            </tr>
            <tr>
                <td id="messagetext"> Message : </td> 
                <td> <input type="textarea" requrired placeholder="Your message..." id="message" rows="500" cols="50">
                    <tr>
                        <td> <input type="submit" id="submit" value="Submit"> </td>
                        <td> <input type="reset" id="reset" value="Reset"> </td>
                    </tr>
                </td>
            </tr>
            
            
        </form>
    </table>
    </div>
</body>
</html>
