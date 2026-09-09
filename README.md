# Manan360.pk
Welcome Students 🌟

This website is created to provide notes, PDFs, study materials, and useful educational resources for all students.

Thank you for visiting and happy learning! 📘
<p><a href="Class%209th%20Urdu%20Test%20Paper%20Ch%231.pdf">📘 Download Urdu Test Paper class 9th Chapter 1</a></p>
<h1>Class 10th Physics Test Papers</h1>

<a href="physics-test-paper.pdf.pdf" download 
style="background:#2563eb;color:white;padding:12px 20px;
text-decoration:none;border-radius:8px;display:inline-block;">
  Class 10th Physics Chapter 1 Test Paper Download
</a>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Manan360 Login</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      min-height: 100vh;
      background: linear-gradient(135deg, #111827, #2563eb);
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .login-box {
      width: 90%;
      max-width: 380px;
      background: white;
      padding: 35px 25px;
      border-radius: 20px;
      box-shadow: 0 15px 40px rgba(0,0,0,0.3);
      text-align: center;
    }

    .logo {
      font-size: 32px;
      font-weight: bold;
      color: #2563eb;
      margin-bottom: 10px;
    }

    h2 {
      margin-bottom: 25px;
      color: #222;
    }

    input {
      width: 100%;
      padding: 14px;
      margin-bottom: 15px;
      border: 1px solid #ddd;
      border-radius: 10px;
      font-size: 16px;
      outline: none;
    }

    input:focus {
      border-color: #2563eb;
    }

    button {
      width: 100%;
      padding: 14px;
      border: none;
      border-radius: 10px;
      background: #2563eb;
      color: white;
      font-size: 17px;
      font-weight: bold;
      cursor: pointer;
    }

    button:hover {
      background: #1d4ed8;
    }

    #error {
      color: red;
      margin-top: 15px;
      font-size: 14px;
    }

    #website {
      display: none;
    }
  </style>
</head>

<body>

  <!-- LOGIN PAGE -->
  <div class="login-box" id="loginPage">

    <div class="logo">Manan360</div>

    <h2>Login</h2>

    <input
      type="text"
      id="username"
      placeholder="Username"
      autocomplete="username"
    >

    <input
      type="password"
      id="password"
      placeholder="Password"
      autocomplete="current-password"
    >

    <button onclick="login()">Login</button>

    <p id="error"></p>
  </div>


  <!-- YOUR WEBSITE WILL SHOW AFTER LOGIN -->
  <div id="website">

    <!-- اپنی موجودہ ویب سائٹ کا اصل content یہاں رکھیں -->

    <h1>Welcome to Manan360</h1>
    <p>Login successful.</p>

  </div>


  <script>

    // LOGIN DETAILS
    const correctUsername = "Manan360";
    const correctPassword = "1098765492";


    function login() {

      const username =
        document.getElementById("username").value.trim();

      const password =
        document.getElementById("password").value;


      if (
        username === correctUsername &&
        password === correctPassword
      ) {

        sessionStorage.setItem("manan360Login", "true");

        document.getElementById("loginPage").style.display = "none";

        document.getElementById("website").style.display = "block";

      } else {

        document.getElementById("error").innerText =
          "Username یا Password غلط ہے!";

      }
    }


    // Check if already logged in
    window.onload = function () {

      if (
        sessionStorage.getItem("manan360Login") === "true"
      ) {

        document.getElementById("loginPage").style.display = "none";

        document.getElementById("website").style.display = "block";

      }

    };

  </script>

</body>
</html>
