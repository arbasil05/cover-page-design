# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Fork your the repository to your repository 
### Step 2:
Now using the command "django-admin startproject myproj" start a django project named myproj
### Step 3:
Now mek sure to adjust the settings.py folder properly by adding "import os" in line 14 and STATCFILES_DIRS line at last
### Step 4:
Now create a folder called static within this create another folder called html and within this create a html file named index.html
### Step 5:
Now create your book cover design using html and css
### Step 6:
Using the command runserver, run your server and then access the static and html folder to access the index.html file

## Code:

### HTML code :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
      
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,100;1,200&family=Open+Sans:ital,wght@0,400;0,700;0,800;1,500&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Press+Start+2P&family=Quicksand:wght@300;400;500;600;700&family=Roboto:ital,wght@0,100;0,400;0,500;0,700;0,900;1,400;1,500;1,700&display=swap" rel="stylesheet">
    <style>
        *{
            font-family: 'poppins';
        }
        body {
            margin: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        .container{
            border: solid 1px;
            height: 650px;
            width: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
            background-image: url("images/7714.jpg");
            
        }
        .title{
            font-size: 70px;
            margin-top: -180px;
            margin-left: 10px;
            line-height: 90px;
            display:inline-block;
            position: absolute;
            color: black;
            
        }
        .author{
            font-size: 20px;
            margin-top: 400px;
            display: inline-block;
            color: black;
            height: 80px;
            position: absolute;
            bottom:-10px;
            left: 340px;
            transform: translateX(-50%);
        
        }
        .author-photo{
            height: 200px;
            width: 150px;
            position: absolute;
            bottom: 0px;
            right: 175.4px;
            transform: translateX(-50%);
        }
        .subtitle {
            color: black;
            height: 80px;
            width: 300px;
            position: absolute;
            top: 10px; 
            left: 50%; 
            transform: translateX(-50%);
            font-size: 12px;
            display: inline-block;
        }

      
    </style>
</head>
<body>
    <div class="container">
        <p class="subtitle">Uncover the power of Django through a journey into web development's core.</p>
        <p class="title">A Dive into Django</p>
        <div>
            <p class="author">A.R.Basil</p>
            <img src="images/author.png" class="author-photo">
        </div>
   
    </div>
    
</body>
</html>

```

## Output:
![image](https://github.com/arbasil05/cover-page-design/assets/144218037/7b768284-be5c-4d6a-8124-d15da12af8b3)


## Result:
Book cover has been made using HTML and CSS 
