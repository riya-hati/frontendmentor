# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Desaturated Dark Cyan: hsl(180, 29%, 50%)

### Neutral

- Light Grayish Cyan (Background): hsl(180, 52%, 96%)
- Light Grayish Cyan (Filter Tablets): hsl(180, 31%, 95%)
- Dark Grayish Cyan: hsl(180, 8%, 52%)
- Very Dark Grayish Cyan: hsl(180, 14%, 20%)

## Typography

### Body Copy

- Font size: 15px

### Headings

- Family: [League Spartan](https://fonts.google.com/specimen/League+Spartan)
- Weights: 500, 700
<!-- Item Start -->
  Photosnap
  New!
  Featured
  Senior Frontend Developer
  1d ago
  Full Time
  USA only
  <!-- Role -->
  Frontend
  <!-- Level -->
  Senior
  <!-- Languages -->
  HTML
  CSS
  JavaScript
  <!-- Item End -->

  <!-- Item Start -->
  Manage
  New!
  Featured
  Fullstack Developer
  1d ago
  Part Time
  Remote
  <!-- Role -->
  Fullstack
  <!-- Level -->
  Midweight
  <!-- Languages -->
  Python
  <!-- Tools -->
  React
  <!-- Item End -->

  <!-- Item Start -->
  Account
  New!
  Junior Frontend Developer
  2d ago
  Part Time
  USA only
  <!-- Role -->
  Frontend
  <!-- Level -->
  Junior
  <!-- Languages -->
  JavaScript
  <!-- Tools -->
  React
  Sass
  <!-- Item End -->

  <!-- Item Start -->
  MyHome
  Junior Frontend Developer
  5d ago
  Contract
  USA only
  <!-- Role -->
  Frontend
  <!-- Level -->
  Junior
  <!-- Languages -->
  CSS
  JavaScript
  <!-- Item End -->

  <!-- Item Start -->
  Loop Studios
  Software Engineer
  1w ago
  Full Time
  Worldwide
  <!-- Role -->
  Fullstack
  <!-- Level -->
  Midweight
  <!-- Languages -->
  JavaScript
  Ruby
  <!-- Tools -->
  Sass
  <!-- Item End -->

  <!-- Item Start -->
  FaceIt
  Junior Backend Developer
  2w ago
  Full Time
  UK only
  <!-- Role -->
  Backend
  <!-- Level -->
  Junior
  <!-- Languages -->
  Ruby
  <!-- Tools -->
  RoR
  <!-- Item End -->

  <!-- Item Start -->
  Shortly
  Junior Developer
  2w ago
  Full Time
  Worldwide
  <!-- Role -->
  Frontend
  <!-- Level -->
  Junior
  <!-- Languages -->
  HTML
  JavaScript
  <!-- Tools -->
  Sass
  <!-- Item End -->

  <!-- Item Start -->
  Insure
  Junior Frontend Developer
  2w ago
  Full Time
  USA only
  <!-- Role -->
  Frontend
  <!-- Level -->
   Junior
  <!-- Languages -->
  JavaScript
  <!-- Tools -->
  Vue
  Sass
  <!-- Item End -->

  <!-- Item Start -->
  Eyecam Co.
  Full Stack Engineer
  3w ago
  Full Time
  Worldwide
  <!-- Role -->
  Fullstack
  <!-- Level -->
  Midweight
  <!-- Languages -->
  JavaScript
  Python
  <!-- Tools -->
  Django
  <!-- Item End -->





   <div class="bottom_container"> 
    <div> 
      <div>
      <div>
      <img src="./images/photosnap.svg" alt="logo" srcset="">
    </div>
    <div>
      <h1>Senior Frontend Developer</h1>
    </div>
  </div>
  <div class="front_end">
    <p>frontend</p>
    <p>frontend</p>
    <p>frontend</p>
    <p>frontend</p>
    <p>frontend</p>
  </div>
</div>
</div>  






*
{
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
}
body
{
 font-family: 'League Spartan', sans-serif;
 background-color:var(--cyan);
}
:root{
    --bg-Dark-Cyan: hsl(180, 29%, 50%);
    --cyan: hsl(180, 52%, 96%);
    --light-cyan : hsl(180, 31%, 95%);
    --Dark-Cyan: hsl(180, 8%, 52%);
    --Very-Dark-Cyan: hsl(180, 14%, 20%);
}
.top_container{
height: 200px;
width: 100%;
background-image: url(./images/bg-header-desktop.svg);
background-repeat: no-repeat;
background-color:var(--bg-Dark-Cyan);
background-position: center;
background-size: cover;
}
.main{
    display: flex;
    justify-content: center;
    background-color: blueviolet;
    margin: 40px 40px 40px 40px;
    padding: 4px 4px 4px 4px;
    border: 20px 20px 20px 20px;
    border-color: var(--cyan);
	box-shadow: rgba(17, 12, 46, 0.15) 0px 48px 100px 0px;
    /*height: 200px;
    width: 1000px;*/
    cursor: pointer;
    
}
.container{
    width: 80%  ;
    display: flex;
    justify-content: space-between;
    border-radius: 3px;
    padding: 2px;
    
    

}
.item1{
    display: flex;
    margin-bottom: 10px;
    padding: 20px;
   
}
.item_i{
    display: flex;
    justify-content: space-between;
    gap: 20px;
    padding: 10px;
}
.item_ii{
    display: flex;
    justify-content: space-between;
}
.item2{
    display: flex;
    justify-content: center;
    align-items: center ;
    gap: 20px;
    
}

.front{
    background-color: var(--Dark-Cyan);
    border-radius: 50px;
    padding: 2px;
    
}
.senior{
    background-color: var(--Dark-Cyan);
    border-radius: 50px;
    padding: 2px;
    
}
.html{
    background-color: var(--Dark-Cyan);
    border-radius: 50px;
    padding: 2px;
    
}
.css{
    background-color: var(--Dark-Cyan);
    border-radius: 50px;
    padding: 2px;
    
}
.java{
    background-color: var(--Dark-Cyan);
    border-radius: 50px;
    padding: 2px;
    
}
.new{
    background-color: var(--Dark-Cyan);
    border-radius: 50px;
    padding: 2px;
    
}
.featured{
    background-color: var(--Dark-Cyan);
    border-radius: 50px;
    padding: 2px;
    
}
.item_b{
    padding: 20px;
}
.item_a{
    align-items: center;
}




<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- displays site properly  based on user's device -->

  <link rel="icon" type="imag e/png" sizes="32x32" href="./images/favicon-32x32.png">

  <title>Frontend Mentor | Job Listings</title>
  <link rel="stylesheet" href="style.css">

  <link rel="stylesheet" href="<link rel=" preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@500&display=swap" rel="stylesheet">">
</head>

<body>
  <div class="top_container"></div>

  <div class="main">
    <div class="container">
      <div class="item1">
        <div class="item_a">
          <img src="./images/photosnap.svg" alt="logo">
        </div>
        <div class="item_b">
          <div class="item_i">
            <p style="color:aqua">Photosnap</p>
            <p class="new">NEW</p>

            <P class="featured">FEATURED</P>
          </div>
          <h4>Senior Frontend Developer</h4>
          <div class="item_i">
            <p>1d ago</p>
            <span>&#8226;</span>
            <p>FullTime</p>
            <span>&#8226;</span>
            <p>USA only</p>
  
          </div>
        </div>
  
      </div>
      <div class="item2">
        <p class="front">Frontend</p>
        <p class="senior">Senior</p>
        <p class="html">HTML</p>
        <p class="css">CSS</p>
        <p class="java">Javascript</p>
  
      </div>
    </div>
  </div>

</body>

</html>
