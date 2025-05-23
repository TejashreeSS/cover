# Ex.06 Book Front Cover Page Design
## Date: 25.04.25

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
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #fff5f8;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Playfair Display', serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: #ffe9f3;
      border: 2px solid #d291bc;
      padding: 35px 25px;
      box-shadow: 0 12px 30px rgba(0, 0, 0, 0.15);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      color: #5c3d53;
      border-radius: 20px;
    }

    .title {
      font-size: 30px;
      font-weight: 700;
      text-align: center;
      letter-spacing: 1px;
    }

    .subtitle {
      font-size: 16px;
      margin-top: 8px;
      text-align: center;
      font-style: italic;
      color: #7e5771;
    }

    .image {
      flex: 1;
      margin: 30px 0;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .image img {
      max-width: 100%;
      max-height: 100%;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }

    .author {
      font-size: 18px;
      text-align: center;
      color: #865c74;
      margin-top: 10px;
    }

    .line {
      height: 2px;
      background: #a15d8f;
      width: 60px;
      margin: 12px auto;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">Whispers in Bloom</div>
      <div class="line"></div>
      <div class="subtitle">A poetic journey through petals and peace</div>
    </div>
    <div class="image">
      <img src="https://files.idyllic.app/files/static/2882834">
    </div>
    <div class="author">Tejashree SS(212224100058)</div>
  </div>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2025-04-25 110928.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
