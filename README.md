# Ex.04 Book Front Cover Page Design
## Date:17/12/2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: black; /* solid black background */
      font-family: Arial, sans-serif;
    }

    /* Book rectangle frame */
    .book-frame {
      width: 400px;
      height: 650px;
      border: 8px solid #fff;
      box-shadow: 0 10px 25px rgba(255,255,255,0.3);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      background: url("background.jpg") center/cover no-repeat; 
      /* Your uploaded image inside the book frame */
      color: white;
      text-align: center;
      padding: 1rem;
    }

    h1 {
      font-size: 1.8rem;
      margin: 1rem 0 0 0;
    }

    h2 {
      font-size: 1.2rem;
      margin: 0.5rem 0 1rem 0;
    }

    /* Square frame for author image */
    .author-img {
      width: 180px;
      height: 180px;
      border: 4px solid #fff;
      object-fit: cover;
      margin-bottom: 1rem;
    }

    /* Features section */
    .features {
      text-align: left;
      font-size: 0.9rem;
      margin-top: 1rem;
      padding: 0.5rem;
      background: rgba(0,0,0,0.5);
      border-radius: 6px;
      width: 90%;
    }

    .features h3 {
      text-align: center;
      margin: 0.5rem 0;
      font-size: 1rem;
      text-decoration: underline;
    }

    .features ul {
      margin: 0;
      padding-left: 1.2rem;
    }

    /* Signature */
    .signature {
      margin-top: auto;
      font-style: italic;
      font-size: 0.9rem;
      color: #ff1500;
    }
  </style>
</head>
<body>
  <div class="book-frame">
    <h1>Father of anime dragon ball</h1>
    <h2>Author: Akira Toriyama</h2>
    <img src="akira.jpeg" alt="Akira Toriyama" class="author-img">

    <div class="features">
      <h3>Dragon Ball Features</h3>
      <ul>
        <li>Epic battles with Saiyan warriors</li>
        <li>Legendary transformations like Super Saiyan</li>
        <li>Iconic characters: Goku, Vegeta, Piccolo</li>
        <li>Fusion techniques and powerful energy blasts</li>
        <li>Journey for the mystical Dragon Balls</li>
      </ul>
    </div>

    <div class="signature">
      Created by [Bharath S]
    </div>
  </div>
</body>
</html>
```


## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-12-17 211805" src="https://github.com/user-attachments/assets/eff26af5-3f8a-4ea5-b04e-56b0baabed16" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
