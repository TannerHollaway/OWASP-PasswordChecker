# OWASP-PasswordChecker

<h2>Description</h2>
Creating a Password Strength Checker based on OWASP standards.

- OWASP stands for the Open Web Application Security Project. It provides guidelines to improve software security, including recommendations for strong passwords.
<br />


<h2>Utilities Used</h2>

- <b>Python</b> 
- <b>re</b>


<h2>Program walk-through:</h2>

<p align="center">
We start by importing the re module, which stands for regular expressions. This module helps us check for specific patterns in the password. We also start by defining a set of common passwords: <br/> 
<img src="https://i.imgur.com/GcUXO0Q.png" height="80%" width="80%" alt="OWASPChecker"/>
<br />
<br />

<p align="center">
The check_password_strength Function is function takes a password as input and returns an errors based on the criteria it fails to meet: <br/> 
<img src="https://i.imgur.com/db0Ae5r.png" height="80%" width="80%" alt="OWASPChecker"/>
<br />
<br />

<p align="center">
Next, we use regular expressions to verify the different types of characters. For each type missing (uppercase, lowercase, digit, special character), an error is thrown: <br/> 
<img src="https://i.imgur.com/t1qXtAp.png" height="80%" width="80%" alt="OWASPChecker"/>
<br />
<br />

<p align="center">
Finally, we test our function with an example password. Based on the errors returned, we know if the password is strong or weak: <br/> 
<img src="https://i.imgur.com/9WQVoWZ.png" height="80%" width="80%" alt="OWASPChecker"/>
<br />
<br />

<p align="center">
1 error example: <br/> 
<img src="https://i.imgur.com/KR6RKzw.png" height="80%" width="80%" alt="OWASPChecker"/>
<br />
<br />

<p align="center">
3 error example: <br/> 
<img src="https://i.imgur.com/XOtIfMz.png" height="80%" width="80%" alt="OWASPChecker"/>
<br />
<br />

<p align="center">
Strong password example: <br/> 
<img src="https://i.imgur.com/QfRmxFr.png" height="80%" width="80%" alt="OWASPChecker"/>
<br />
<br />
