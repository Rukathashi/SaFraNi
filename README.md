# SaFraNi
<!DOCTYPE html>  
<html>  
<head>  
<meta name="viewport" content="width=device-width, initial-scale=1">  
<style>  
body{  
  font-family: Calibri, Helvetica, sans-serif;  
  background-color: pink;  
}  
.container {  
    padding: 50px;  
  background-color: lightblue;  
}  
  
input[type=text], input[type=password], textarea {  
  width: 100%;  
  padding: 15px;  
  margin: 5px 0 22px 0;  
  display: inline-block;  
  border: none;  
  background: #f1f1f1;  
}  
input[type=text]:focus, input[type=password]:focus {  
  background-color: orange;  
  outline: none;  
}  
 div {  
            padding: 10px 0;  
         }  
hr {  
  border: 1px solid #f1f1f1;  
  margin-bottom: 25px;  
}  
.registerbtn {  
  background-color: #4CAF50;  
  color: white;  
  padding: 16px 20px;  
  margin: 8px 0;  
  border: none;  
  cursor: pointer;  
  width: 100%;  
  opacity: 0.9;  
}  
.registerbtn:hover {  
  opacity: 1;  
}  
</style>  
</head>  
<body>  
<form>  
  <div class="container">  
  <center>  <h1> SaFraNi Registrierung</h1> </center>  
  <hr>  
  <label> Name </label>   
<input type="text" name="firstname" placeholder= "Name" size="15" required />   
<label> Mittelnahme: </label>   
<input type="text" name="middlename" placeholder="Mittelnahme" size="15" required />   
<label> Nachnahme: </label>    
<input type="text" name="lastname" placeholder="Nachnahme" size="15"required />   
<div>   
<label>   
Geschlecht :  
</label><br>  
<input type="radio" value="Man" name="gender" checked > Man   
<input type="radio" value="Frau" name="gender"> Frau   
<input type="radio" value="Anderes" name="gender"> Anderes  
  
</div>  
<label>   
Handynummer :  
</label>  
<input type="text" name="country code" placeholder="Country Code"  value="+49" size="2"/>   
<input type="text" name="handynummer" placeholder="handynummer" size="10"/ required>   
Addresse :  
<textarea cols="80" rows="5" placeholder="Adresse" value="address" required>  
</textarea>  
 <label for="email"><b>Email</b></label>  
 <input type="text" placeholder="Email Eingeben" name="email" required>  
  
    <label for="psw"><b>Password</b></label>  
    <input type="password" placeholder="Password Eingeben" name="psw" required>  
  
    <label for="psw-repeat"><b>Password Bestetigen</b></label>  
    <input type="password" placeholder="Password Bestetigen" name="psw-repeat" required>  
    <button type="submit" class="registerbtn">Register</button>    
</form>  
</body>  
</html>  
