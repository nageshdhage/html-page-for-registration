# html-page-for-registration
if form is submitted it say tahnks
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>registration form for class</title>
</head>
<body bgcolor="skyblue" >
    <form action="ab.html" target="_selfS">
        <fieldset>
            <legend><strong>registration form</strong></legend>
<label>user name</label><br>
<input type="text" name="user name"><br>
<label>email</label><br>
<input type="email" id="email"><br>
<label>password</label><br>
  <input type="password" id="password"><br>
<label>conform password</label><br>
  <input type="password" id="password"><br>
inter your address:<br>
        <textarea rows="20"cols="30"></textarea><hr>
   <label for="gender">gender</label><br>
     <input type="radio" id="gender" value="male">male<br>
    <input type="radio" id="gender" value="female">female<br>
    <input type="radio" id="gender" value="other">other<br><hr>
what you like:<br>
  <input type="checkbox" id="cricket" value="cricket">
  <label for="cricket">cricket</label><br>
  <input type="checkbox" id="dosa" value="dosa">
  <label for="dosa">dosa</label><br>
  <input type="checkbox" id="laptop" value="laptop">
  <label for="laptop">laptop</label><br><hr>
  <input type="file" id="file" value="file"><br>
  <input type="submit" value="submit"><hr><br>
       </fieldset>
    </form>
    
</body>
</html>
