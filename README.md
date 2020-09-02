<!DOCTYPE html>
<html>
<head>
<title></title>
</head>
<link rel="stylesheet" type="text/css" href="Surveystyle.css">

<div class="survey">
<h1 id="title">Star<span>Survey</span></h1>
<h3 id="discription">Thank you for signing up at Star Survey. Tell us more about yourself.</h3>
<form id="survey-form">
<div class="form-inner">
<div class="space">
<label for="name" id="name-label">Name</label><br>
<input type="text" id="fname" name="fname" placeholder="First Name" required><br>
<label for="lname">Last name:</label><br>
<input type="text" id="lname" name="lname" placeholder="Last Name" required=""><br><br>
</div>
<label for="email"><h1>Email</h1></label>
<input type="text" name="email" id="email" required></div>
<div>
<label><h2>Password</h2>
<input type="password" name="password" required></label>
</div><br>
<div><h2>Female</h2><input type="radio" name="gender" value="Female">
    <h2>Male</h2><input type="radio" name="gender" value="Male">
    <h2>Other</h2><input type="radio" name="gender" value="Other"></div>
    <div>

<div class="space">
 <label for="number-label" id="name-label">Age</label><br>
 <input type="number" placeholder="age" id="number" min="18" max="90" required>
</div>
<div class="space">
 <label id="dropdown-label">Zodiac Sign</label><br>
 <select id="dropdown">
    <option vaue="Leo">Leo</option>
    <option vaue="Aquarius">Aquarius</option>
        <option vaue="Sagittarius">Sagittarius</option>
        <option vaue="Gemini">Geminin</option>
        <option vaue="Pisces">Pisces</option>
        <option vaue="Virgos">Virgos</option>
        <option vaue="Cancer">Cancer</option>
        <option vaue="Taurus">Taurus</option>
        <option vaue="Scorpio">Scorpio</option>
        <option vaue="Aries">Aries</option>
        <option vaue="Libra">Libra</option>
        <option vaue="Capricorn">Capricorn</option>
 </select><br>
</div>
<form-group>
<div class="space-se">
<h3>Favorite Music:</h3><br>
</div class="space-se">
<label for="Rock">Rock</label>
<input type="checkbox" name="Rock" id="Rock">

 <label for="Hip Hop">Hip Hop</label>
    <input type="checkbox" name="Hip Hop" id="Hip Hop">
    
     <label for="Jazz">Jazz</label>
        <input type="checkbox" name="Jazz" id="Jazz"><br>

</div>
</form-group>
</div>
<div class="space">
<label id="Bio"></label><br>
</div>
<div class="space-sect">
    <textarea class="text-area"></textarea><br>
</div>

<input type="submit" value="Submit">
</form>


</div>
