# Ex.06 Book Front Cover Page Design
## Date:04.10.2025

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
book.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: rgba(232, 46, 13, 0.913);
      border: 2px solid #333;
      padding: 40px 30px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-size: 28px;
      font-weight: bold;
      color: #06050ee3;
      text-align: center;
      line-height: 1.3;
    }

    .subtitle {
      font-size: 16px;
      margin-top: 10px;
      text-align: center;
      font-style: italic;
    }

    .image {
      flex: 1;
      text-align: center;
      background: url('https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.simonandschuster.co.in%2Fbooks%2FArt-of-Demon-Slayer-Kimetsu-no-Yaiba-the-Anime%2Fufotable%2FThe-Art-of-Demon-Slayer-Kimetsu-no-Yaiba-the%2F9781974739011&psig=AOvVaw1NRi1_j4lbhfn-DcG7ue_c&ust=1759650651061000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCPiwxdSHipADFQAAAAAdAAAAABAL') center/contain no-repeat;
      margin: 30px 0;
    }

    .author {
      font-size: 18px;
      text-align: center;
      color: 
      #090909;
      margin-top: 20px;
    }

    .line {
      height: 2px;
      background: #0a0a0a;
      width: 50px;
      margin: 10px auto;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">Kimetsu no Yaiba</div>
      <div class="line"></div>
      <div class="subtitle">"Set your heart ablaze"
</div>
    </div>
    <div class="image">
        <img src="demon slayer.jpg" height="100%" width="300">
    </div>
    <div class="author">By Vishal SB</div>
  </div>
</body>
</html>
</body>
</html>
```


## OUTPUT:
![alt text](image.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
