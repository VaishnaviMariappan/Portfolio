# EXP 01 - PORTFOLIO

## AIM:

To create a portfolio using HTML and CSS

## ALGORITHM:

1. Set up the basic structure of your HTML document.

2. Create a CSS file named "styles.css" and link it to your HTML document. This file will contain the CSS rules for styling your portfolio.

3. Design the layout of your portfolio using HTML elements such as < header >, < nav >, < section >, < article >, and < footer >. Use appropriate classes or IDs to style these elements later with CSS.

4. Add a header section to display your name or the title of your portfolio.

5. Add images or media to enhance your portfolio. You can use the <img> tag to display images and embed videos or other media using appropriate HTML tags.

6. Apply responsive design techniques to ensure your portfolio looks good on different devices and screen sizes. Use CSS media queries to adjust the layout and styling as needed.

7. Apply CSS styling to your portfolio elements by targeting their respective classes or IDs in the "styles.css" file. Customize the colors, fonts, spacing, and other visual properties to match your desired design.

## CODE:

### HTML CODE:
## Portfolio.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <link href='https://fonts.googleapis.com/css?family=Aclonica' rel='stylesheet'>
    <link rel="Stylesheet" href="styleport.css">
    <title>Document</title>
</head>
<body>
            <div class="main">
                <div class="side_content">
                    <div class="name" style="padding-left: 100px;font-family: 'Aclonica';font-size: 40px;">VAISHNAVI</div>
                    <div class="content"><a style="font-weight:bold; color:black" href="portfolio.html">Home</a></div><br>
                    <div class="content"><a href="skill.html">Skills</a></div><br>
                    <div class="content"><a href="contact.html">Contact</a></div>

                    <div><a class="icons" href="https://www.linkedin.com/in/vaishnavi-mariappan-905078236/"><img src="linkedin.png" alt="photo" width="45px" height="45px"></a>
                    <a href="https://github.com/VaishnaviMariappan"><img src="github.png" alt="photo" width="45px" height="45px"></a>
                    <a href="https://app.slack.com/client/T04S22PMGG7/C04S2MHLU5V/rimeto_profile/U04SDMZB413"><img src="slack.png" alt="photo" width="40px" height="40px"></a></div>
                </div>
                <div class="mainlayout">
                    <div class="content_layout">
                    <div style="padding-left: 280px; padding-bottom: 20px;"><div class="image"></div></div>
                    <div style="font-size: 40px; text-align: center; padding: 15px;">Hello there!</div>
                    <div style="font-size: 30px; text-align: center; padding: 10px;font-weight:bold;">I'm Vaishnavi Mariappan</div>
                    <div style=" text-align: center; font-size: 23px;font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;">Fresh graduate in Engineering Profession.Did my major in Artificial Intelligence & Machine Learning.<br><br>
                    I'm passionate about Machine Learning algorithms, data analyzing, designing 3d models, implemented Ux And frontend and excited to learn more.</div>
                    </div>
                </div>
            </div>
        </body>
    </html>
```
## Skills.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <link href='https://fonts.googleapis.com/css?family=Aclonica' rel='stylesheet'>
    <link rel="Stylesheet" href="styleport.css">
    <title>Document</title>
</head>
<body>
            <div class="main">
                <div class="side_content">
                    <div class="name" style="padding-left: 100px;font-family: 'Aclonica';font-size: 40px;">VAISHNAVI</div>
                    <div class="content"><a href="portfolio.html">Home</a></div><br>
                    <div class="content"><a style="font-weight:bold; color:black" href="skill.html">Skills</a></div><br>
                    <div class="content"><a href="contact.html">Contact</a></div>

                    <div><a class="icons" href="https://www.linkedin.com/in/vaishnavi-mariappan-905078236/"><img src="linkedin.png" alt="photo" width="45px" height="45px"></a>
                    <a href="https://github.com/VaishnaviMariappan"><img src="github.png" alt="photo" width="45px" height="45px"></a>
                    <a href="https://app.slack.com/client/T04S22PMGG7/C04S2MHLU5V/rimeto_profile/U04SDMZB413"><img src="slack.png" alt="photo" width="40px" height="40px"></a></div>
                </div>
                <div class="mainlayout">
                    <div class="content_layout">
                    <div class="container">
                        <img src="ai.png" alt="photo" height="90px" width="90px"><img style="padding-left: 250px;" src="iot.png" alt="photo" height="90px" width="90px"><img style="padding-left: 250px;" src="code.png" alt="photo" height="90px" width="90px">
                        <h3>Internet of things&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Artificial Intelligence&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;C,Python and Java languages</h3>
                        <img style="padding-top: 170px;" src="autocad.png" alt="photo" height="90px" width="90px"><img style="padding-left: 250px;" src="ui.png" alt="photo" height="90px" width="90px"><img style="padding-left: 250px;" src="soft.png" alt="photo" height="90px" width="90px">
                        <h3>3D model designing&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;UI/UX Interface&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Problemsolving Skills, Time Managemanet</h3>
                    </div>
                </div>
            </div>
        </body>
    </html>
```
## Contact.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <link href='https://fonts.googleapis.com/css?family=Aclonica' rel='stylesheet'>
    <link rel="Stylesheet" href="styleport.css">
    <title>Document</title>
</head>
<body>
            <div class="main">
                <div class="side_content">
                    <div class="name" style="padding-left: 100px;font-family: 'Aclonica';font-size: 40px;">VAISHNAVI</div>
                    <div class="content"><a href="portfolio.html">Home</a></div><br>
                    <div class="content"><a href="skill.html">Skills</a></div><br>
                    <div class="content"><a style="font-weight:bold; color:black"href="contact.html">Contact</a></div>

                    <div><a class="icons" href="https://www.linkedin.com/in/vaishnavi-mariappan-905078236/"><img src="linkedin.png" alt="photo" width="45px" height="45px"></a>
                    <a href="https://github.com/VaishnaviMariappan"><img src="github.png" alt="photo" width="45px" height="45px"></a>
                    <a href="https://app.slack.com/client/T04S22PMGG7/C04S2MHLU5V/rimeto_profile/U04SDMZB413"><img src="slack.png" alt="photo" width="40px" height="40px"></a></div>
                </div>
                <div class="mainlayout">
                    <div class="content_layout">
                        <section id="contact">
                            <h2 class="heading">&emsp;CONTACT ME</h2>
                            <br>
                            <form action="" class="form">
                                <input type="text" name="name" class="input" placeholder="Enter Your name">
                                <input type="text" name="email" class="input" placeholder="Enter Your Email">
                                <textarea name="message" id="message" cols="70" rows="20" placeholder="Enter Your Message"></textarea>
                                <button class="submit">Submit</button>
                            </form>
                         </section>

                         <div style="text-align: center;padding-top: 100px;font-size: 25px;font-family: Georgia, 'Times New Roman', Times, serif;font-weight:bold;"><br>Emails will be answered within a day.<br>Thank you</div>
                    </div>
                </div>
            </div>
        </body>
    </html>
```
### CSS CODE:
```css
body
{
    margin: 0;
}
.main{
    display: inline-flex;
    justify-content: space-between;
}
.side_content{
    display: flex;
    width: 400px;
    flex-direction: column;
    align-content: space-between;
    padding: 10px;
    background-color: rgb(233, 233, 226);
}
.name{
    display: flex;
    font-size: 35px;
    color: black;
    padding: 55px;
    
}
.content{
    display: flex;
    font-size: 25px;
    opacity: 0.7;
    display: flex;
    padding: 45px;
    align-items: center;
    justify-content: space-around;
    text-align: center;
    padding-bottom: 70px;
}
.mainlayout{
    display: flex;
    flex-direction: column;
    width: max-content;
    justify-content: center;
    align-content: space-between;
    padding: 40px;
    background-image: url(./snow5.png);
    background-size: cover;
    opacity: 0.8;
    
}
.content_layout{
    display: flex;
    width: 1186.5px;
    flex-direction: column;
    align-content: space-between;
    padding: 10px;
    height: 690px;
}
.image{
    margin-top: 0;
    width: 450px;
    height: 450px;
    border-radius: 100px;
    background-image: url(./profile.png);
    
}
a:hover
{
    color: rgb(0, 0, 0);
    cursor: pointer;
}
a
{
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: 30px;
    color: rgba(0, 0, 0, 0.703);
    text-decoration: none
}
.icons
{
    padding-left: 130px;
}
#contact{
    display: flex;
    flex-direction: column;
    height: 400px;
}
#contact h1{
    margin: 10px;
}
.form{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.input{
    padding: 10px 15px;
    margin: 12px;
    width: 40%;
    border: none;
    outline: none;
    border-radius: 25px;
    background-color: rgba(0, 0, 0, 0.759);
    color:white;
    font-size: 1.2rem;
}
#message{
    margin: 15px;
    padding: 15px;
    border-radius: 20px;
    background-color: rgba(0, 0, 0, 0.759);
    color: white;
    height: 150px;
    width: 750px;
    font-size: 1.2rem;

}
.submit{
    padding: 7px 14px;
    margin: 15x;
    width: 15%;
    border-radius: 20px;
    background-color:  rgba(0, 0, 0, 0.759);
    color: white;
    border: none;
    outline: none;
    font-size: 1.2rem;
    margin-bottom: 1%;
}
.submit:hover{
    background-color: rgb(48, 84, 97);
    color: white;
    cursor: pointer;
}
h2
{
    font-size:30px;
}
.container
{
    margin-left: 200px;
    margin-top:5%;
    height: 700px;
    width: 1000px;
    border-radius: 10px;
}
```

## OUTPUT:
![home](https://github.com/VaishnaviMariappan/Portfolio/assets/94169913/f58f0fa6-7332-4230-b7bd-8dd3c4c43e57)
![skill](https://github.com/VaishnaviMariappan/Portfolio/assets/94169913/fa65b7ee-3d48-4715-ac8d-ea1862205e5d)
![contact](https://github.com/VaishnaviMariappan/Portfolio/assets/94169913/a9b59870-058e-4d34-889e-2a7ceb851701)


## RESULT:

Thus, a Portfolio is created using HTML and CSS.
