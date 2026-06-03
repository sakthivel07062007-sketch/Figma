# Ex09 Event Registration Web Application
## Date:03/06/2026

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```html
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- British Style Font -->
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;700&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="style.css">

    <title>Gaming Portal</title>
</head>

<body>

    <div class="container">

        <!-- College Header -->
        <div class="college">
            <h1>SAVEETHA</h1>
            <h2>ENGINEERING COLLEGE</h2>

            <div class="tag">
                AFFILIATED TO ANNA UNIVERSITY
            </div>
        </div>

        <!-- Controller -->
        <div class="controller">
            🎮
        </div>

        <!-- Triangle Design -->
        <div class="triangle"></div>

        <!-- Buttons -->
        <div class="buttons">

            <button class="login-btn">
                LOGIN
            </button>

            <button class="register-btn">
                REGISTER
            </button>

        </div>

    </div>

</body>
</html>
front_page.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- British Style Font -->
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;700&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="style.css">

    <title>Gaming Portal</title>
</head>

<body>
<div class="container">

    <!-- Title -->
    <div class="college">
        <h1>Controller Chaos</h1>
        <p class="subtitle">
            Join the fun of open world gaming culture
        </p>
    </div>

    <!-- Triangle -->
    <div class="triangle"></div>

    <!-- Game List -->
    <div class="game-list">

        <a href="#" class="game">
            → Red Dead Redemption 2
        </a>

        <a href="#" class="game">
            → Grand Theft Auto V
        </a>

        <a href="#" class="game">
            → God of War
        </a>

        <a href="#" class="game active">
            → Assassin's Creed Shadows
        </a>

        <a href="#" class="game">
            → Uncharted Lost Legacy
        </a>

        <a href="#" class="game">
            → Hogwarts Legacy
        </a>

        <a href="#" class="game">
            → Spider Man 2
        </a>

        <a href="#" class="game">
            → Ghost of Yotei
        </a>

    </div>


</div>
</body>
</html>
registration.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;700&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="style.css">

    <title>Event Registration</title>
</head>
<body>

<div class="container">

    <div class="form-card">

        <h1>EVENT REGISTRATION</h1>

        <form>

            <input type="text" placeholder="Full Name">

            <select>
                <option>Gender</option>
                <option>Male</option>
                <option>Female</option>
                <option>Other</option>
            </select>

            <input type="number" placeholder="Age">

            <input type="text" placeholder="Register Number">

            <input type="text" placeholder="Department">

            <input type="tel" placeholder="Mobile Number">

            <input type="email" placeholder="Email ID">

            <select>
                <option>Select Event</option>
                <option>Red Dead Redemption 2</option>
                <option>Grand Theft Auto V</option>
                <option>God of War</option>
                <option>Assassin's Creed Shadows</option>
                <option>Ghost of Yotei</option>
            </select>

            <button type="submit">
                Register
            </button>

        </form>

    </div>

</div>

</body>
</html>
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- British Style Font -->
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;700&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="style.css">

    <title>Gaming Portal</title>
</head>

<body>
    <div class="container">

    <div class="thankyou-card">

        <!-- Sports Icons -->
        <div class="sports-icons">
            🎈 🎆 🎇 🧨 ✨
            <br><br>
            💝 💖 💗 💓 💞
        </div>

        <!-- Thank You Message -->
        <div class="thankyou-content">

            <h1>THANK YOU</h1>

            <p>
                We are all eagerly waiting<br>
                for your participation in the<br>
                Gaming events.
            </p>

        </div>

        <!-- Contact Section -->
        <div class="contact-section">

            <h2>CONTACT US:</h2>

            <p>
                Email ID:
                mrunknown@gmail.com
            </p>

            <h2>PHONE:</h2>

            <p>
                9836742776<br>
                9735601889
            </p>

            <h2>SITE:</h2>

            <p>
                https://saveetha.ac.in/
            </p>

        </div>

        <!-- Back Button -->
        <div class="btn-area">
            <a href="index.html" class="gold-btn">
                BACK TO HOME
            </a>
        </div>

    </div>

</div>
</body>
</html>
```
```css
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;

    font-family:'Cinzel', serif;

    background:
    radial-gradient(circle at top left,
    rgba(255,215,0,0.25),
    transparent 30%),

    radial-gradient(circle at bottom right,
    rgba(255,215,0,0.25),
    transparent 30%),

    #000;

    
}

.container{
    width:360px;
    height:780px;
    position:relative;
    text-align:center;
}

/* Gold Dust */
.container::before{
    content:"";
    position:absolute;
    width:100%;
    height:100%;

    background-image:
    radial-gradient(gold 1px, transparent 1px);

    background-size:8px 8px;

    opacity:0.12;
}

/* Header */

.college{
    position:relative;
    z-index:2;
    margin-top:30px;
}

.college h1{
    color:white;
    font-size:35px;
}

.college h2{
    color:white;
    font-size:20px;
    letter-spacing:2px;
}

.tag{
    display:inline-block;

    margin-top:10px;
    padding:8px 18px;

    background:gold;
    color:black;

    font-weight:bold;
    font-size:12px;
}

/* Controller */

.controller{
    font-size:170px;
    margin-top:60px;

    filter:
    drop-shadow(0 0 20px gold)
    drop-shadow(0 0 40px gold);

    position:relative;
    z-index:2;
}

/* Triangle */

.triangle{
    width:0;
    height:0;

    border-left:140px solid transparent;
    border-right:140px solid transparent;
    border-top:220px solid rgba(255,215,0,0.08);

    position:absolute;

    left:50%;
    transform:translateX(-50%);

    top:280px;
}

/* Buttons */

.buttons{
    position:absolute;
    width:100%;
    bottom:170px;

    display:flex;
    flex-direction:column;
    align-items:center;
    gap:20px;

    z-index:2;
}

.login-btn{
    width:220px;
    padding:15px;

    border:none;
    border-radius:50px;

    background:#caa400;
    color:white;

    font-size:18px;
    font-family:'Cinzel', serif;
    font-weight:bold;

    cursor:pointer;

    transition:0.3s;
}

.register-btn{
    width:270px;
    padding:15px;

    border:2px solid #caa400;

    background:#caa400;
    color:white;

    font-size:18px;
    font-family:'Cinzel', serif;
    font-weight:bold;

    cursor:pointer;

    transition:0.3s;
}

.login-btn:hover,
.register-btn:hover{
    transform:scale(1.05);

    box-shadow:
    0 0 15px gold,
    0 0 30px gold;
}
.college{
    margin-top:60px;
    position:relative;
    z-index:2;
}

.college h1{
    color:#caa400;
    font-size:28px;
    font-weight:700;
}

.subtitle{
    color:white;
    margin-top:20px;
    font-size:16px;
}

.game-list{
    position:relative;
    z-index:2;

    width:80%;
    margin:140px auto 0;

    display:flex;
    flex-direction:column;
    gap:25px;
}

.game{
    text-decoration:none;
    color:white;

    font-size:20px;
    font-weight:600;

    transition:0.3s;
}

.game:hover{
    color:gold;
    transform:translateX(10px);
}

.active{
    border:1px solid rgba(255,215,0,0.6);
    padding:10px;
}


.triangle{
    width:0;
    height:0;

    border-left:170px solid transparent;
    border-right:170px solid transparent;
    border-top:260px solid rgba(255,215,0,0.05);

    position:absolute;

    top:250px;
    left:50%;

    transform:translateX(-50%);
}
/* YOUR BACKGROUND IMAGE */

body{
    min-height:100vh;

    background:
    linear-gradient(
        rgba(0,0,0,0.75),
        rgba(0,0,0,0.75)
    ),
    url("back.avif");

    background-size:cover;
    background-position:center;
    background-attachment:fixed;

    font-family:'Cinzel', serif;

    display:flex;
    justify-content:center;
    align-items:center;

    padding:30px 0;
}

/* FORM CARD */

.form-card{
    width:90%;
    max-width:420px;

    background:rgba(0,0,0,0.65);

    border:2px solid #caa400;

    border-radius:25px;

    backdrop-filter:blur(6px);

    padding:30px;

    box-shadow:
    0 0 15px rgba(255,215,0,0.4),
    0 0 40px rgba(255,215,0,0.2);
}

.form-card h1{
    text-align:center;

    color:#caa400;

    margin-bottom:30px;

    font-size:28px;
}

/* INPUTS */

.form-card input,
.form-card select{
    width:100%;

    padding:14px;

    margin-bottom:15px;

    border:1px solid #caa400;

    border-radius:8px;

    background:rgba(255,255,255,0.08);

    color:white;

    font-size:15px;
}

.form-card input::placeholder{
    color:#ddd;
}

.form-card select option{
    color:black;
}

/* BUTTON */

.form-card button{
    width:100%;

    padding:15px;

    border:none;

    border-radius:50px;

    background:#caa400;

    color:white;

    font-size:18px;

    font-weight:bold;

    cursor:pointer;

    transition:0.3s;
}

.form-card button:hover{
    transform:scale(1.03);

    box-shadow:
    0 0 15px gold,
    0 0 30px gold;
}
.thankyou-card{
    width:90%;
    max-width:420px;

    margin:auto;
    padding:30px;

    text-align:center;

    background:rgba(0,0,0,0.65);

    border:2px solid #caa400;
    border-radius:25px;

    backdrop-filter:blur(8px);

    box-shadow:
    0 0 15px rgba(255,215,0,0.4),
    0 0 40px rgba(255,215,0,0.2);
}

.sports-icons{
    color:#caa400;
    font-size:32px;
    line-height:1.8;
    margin-bottom:20px;
}

.thankyou-content h1{
    color:#caa400;
    font-size:42px;
    margin-bottom:15px;
}

.thankyou-content p{
    color:white;
    font-size:20px;
    line-height:1.8;
    margin-bottom:30px;
}

.contact-section{
    text-align:left;
}

.contact-section h2{
    color:#caa400;
    margin-top:20px;
    margin-bottom:8px;
}

.contact-section p{
    color:white;
    line-height:1.8;
}

.btn-area{
    margin-top:30px;
}

.gold-btn{
    display:inline-block;

    padding:14px 30px;

    background:#caa400;
    color:white;

    text-decoration:none;
    border-radius:50px;

    font-weight:bold;

    transition:0.3s;
}

.gold-btn:hover{
    transform:scale(1.05);

    box-shadow:
    0 0 15px gold,
    0 0 30px gold;
}
```
## OUTPUT:
![alt text](<Screenshot 2026-06-03 182044.png>)

![alt text](<Screenshot 2026-06-03 182223.png>)

![alt text](<Screenshot 2026-06-03 182249.png>)

![alt text](<Screenshot 2026-06-03 182322.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
