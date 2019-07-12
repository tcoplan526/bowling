<!DOCTYPE html>
<html>
<style>
input[type=text], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

div {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
</style>
<body>

+++
date = "2019"
title = "2019 Tournament Registraion"
+++

<form action="/thankyou" method="post" name="2019 Tournament Registration" data-netlify-recaptcha="true" data-netlify="true" netlify-honeypot="bot_field" netlify>
    <p style="visibility: hidden">
        <label> Don't fill this out"</label> <input name=bot_field>
        </p>
    Team Event
    <br>
    <br>
    <label for="tname">Team Name</label>
    <br>
    <input type="text" id="tname" name="teamname" placeholder="Your Team Name">
    <br>
    <br>
    Squad Time     
    <select name="Team_Squad">
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="bowler1">First Bowler</label>
    <br>
    <input type="text" id="bowler1" name="firstbowler" placeholder="First Bowler">
    <br>
    <br>
    <label for="bowler2">Second Bowler</label>
    <br>
    <input type="text" id="bowler2" name="secondbowler" placeholder="Second Bowler">
    <br>
    <br>
    <label for="bowler3">Third Bowler</label>
    <br>
    <input type="text" id="bowler3" name="thirdbowler" placeholder="Third Bowler">
    <br>
    <br>
    <label for="bowler4">Fourth Bowler</label>
    <br>
    <input type="text" id="bowler4" name="fourthbowler" placeholder="Fourth Bowler">
    <br>
    <br>
    Doubles Pairing 1
    <br>
    <br>
    Squad Time
    <select name="Doubles_1_Squad">
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="doubles1">Doubles 1 First Bowler</label>
    <br>
    <input type="text" id="doubles1" name="doublesfirstbowler" placeholder="First Bowler">
    <br>
    <br>
    <label for="doubles2">Doubles 1 Second Bowler</label>
    <br>
    <input type="text" id="doubles2" name="doublessecondbowler" placeholder="Second Bowler">
    <br>
    <br>
    Doubles Pairing 2
    <br>
    <br>
    Squad Time
    <select name="Doubles_2_Squad">
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="doubles3">Doubles 2 First Bowler</label>
    <br>
    <input type="text" id="doubles3" name="doublesthirdbowler" placeholder="First Bowler">
    <br>
    <br>
    <label for="doubles4">Doubles 2 Second Bowler</label>
    <br>
    <input type="text" id="doubles4" name="doublesfourthbowler" placeholder="Second Bowler">
    <br>
    <br>
    Singles
    <br>
    <br>
    First Bowler Squad Time
    <select name="Singles_1_Squad">
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="singles1">Singles First Bowler</label>
    <br>
    <input type="text" id="singles1" name="singlesfirstbowler" placeholder="First Bowler">
    <br>
    <br>
   Second Bowler Squad Time
    <select name="Singles_2_Squad">
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="singles2">Singles Second Bowler</label>
    <br>
    <input type="text" id="singles2" name="singlessecondbowler" placeholder="Second Bowler">
    <br>
    <br>
   Third Bowler Squad Time
    <select name="Singles_3_Squad">
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="singles3">Singles Third Bowler</label>
    <br>
    <input type="text" id="singles3" name="singlesthirdbowler" placeholder="Third Bowler">
    <br>
    <br>
    Fourth Bowler Squad Time
    <select name="Singles_4_Squad">
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="singles4">Singles Fourth Bowler</label>
    <br>
    <input type="text" id="singles4" name="singlesfourthbowler" placeholder="Fourth Bowler">
    <br>
    <br>
    <label for="contact">Contact Info</label>
    <br>
    <textarea id="contact" name="contact" placeholder="Please leave your email address or phone number and preferred contact method (text, call, etc.) so we can confirm your registration." style="height: 300px" style="width:500px"></textarea>
    <br>
    <br>
    <div data-netlify-recaptcha="true"></div>
    <br>
    <br>
    <input type="submit" value="Submit" style="">
</form>