# Ex08 Event Registration Web Application
## Date:20.03.2026

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
Page1
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="download" src="img/download-1.png" />
      <img class="img" src="img/download-1-1.png" />
      <img class="rectangle" src="img/rectangle-2.svg" />
      <div class="login">
        <img class="vector" src="img/vector-5.svg" />
        <img class="vector-2" src="img/vector-10.svg" />
        <img class="vector-3" src="img/vector-6.svg" />
        <img class="vector-4" src="img/vector-4.svg" />
        <img class="vector-5" src="img/vector-7.svg" />
      </div>
      <img class="rectangle-2" src="img/rectangle-3.svg" />
      <div class="register">
        <img class="vector-6" src="img/image.svg" />
        <img class="vector-7" src="img/vector-11.svg" />
        <img class="vector-8" src="img/vector-3.svg" />
        <img class="vector-9" src="img/vector-12.svg" />
        <img class="vector-10" src="img/vector-9.svg" />
        <img class="vector-11" src="img/vector.svg" />
        <img class="vector-12" src="img/vector-8.svg" />
        <img class="vector-13" src="img/vector-2.svg" />
      </div>
      <img class="rectangle-3" src="img/rectangle.svg" />
      <img class="badminton-tournament" src="img/badminton-tournament.png" />
    </div>
  </body>
</html>
 CSS 
 .iphone-pro-max {
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .download {
  position: absolute;
  top: 76px;
  left: 0;
  width: 440px;
  height: 103px;
  aspect-ratio: 5.01;
}

.iphone-pro-max .img {
  position: absolute;
  top: 223px;
  left: 131px;
  width: 185px;
  height: 178px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  top: 543px;
  position: absolute;
  left: 70px;
  width: 282px;
  height: 72px;
}

.iphone-pro-max .login {
  position: absolute;
  top: calc(50.00% + 83px);
  left: calc(50.00% - 65px);
  width: 97px;
  height: 39px;
}

.iphone-pro-max .vector {
  position: absolute;
  top: calc(50.00% - 11px);
  left: calc(50.00% + 31px);
  width: 17px;
  height: 22px;
}

.iphone-pro-max .vector-2 {
  position: absolute;
  top: calc(50.00% - 19px);
  left: calc(50.00% + 21px);
  width: 5px;
  height: 30px;
}

.iphone-pro-max .vector-3 {
  position: absolute;
  top: calc(50.00% - 11px);
  left: calc(50.00% - 4px);
  width: 19px;
  height: 31px;
}

.iphone-pro-max .vector-4 {
  position: absolute;
  top: calc(50.00% - 11px);
  left: calc(50.00% - 28px);
  width: 20px;
  height: 23px;
}

.iphone-pro-max .vector-5 {
  position: absolute;
  top: calc(50.00% - 18px);
  left: calc(50.00% - 49px);
  width: 17px;
  height: 29px;
}

.iphone-pro-max .rectangle-2 {
  top: 679px;
  position: absolute;
  left: 70px;
  width: 282px;
  height: 72px;
}

.iphone-pro-max .register {
  position: absolute;
  top: 700px;
  left: 135px;
  width: 151px;
  height: 39px;
  display: flex;
}

.iphone-pro-max .vector-6 {
  margin-top: 0.9px;
  width: 20.85px;
  height: 29.09px;
}

.iphone-pro-max .vector-7 {
  margin-top: 7.9px;
  width: 19.2px;
  height: 22.56px;
  margin-left: 3.0px;
}

.iphone-pro-max .vector-8 {
  margin-top: 7.9px;
  width: 19.26px;
  height: 30.74px;
  margin-left: 4.1px;
}

.iphone-pro-max .vector-9 {
  width: 4.77px;
  height: 30px;
  margin-left: 5.5px;
}

.iphone-pro-max .vector-10 {
  margin-top: 7.9px;
  width: 16.82px;
  height: 22.56px;
  margin-left: 4.4px;
}

.iphone-pro-max .vector-11 {
  margin-top: 3.0px;
  width: 11.7px;
  height: 27.33px;
  margin-left: 3.2px;
}

.iphone-pro-max .vector-12 {
  margin-top: 7.9px;
  width: 19.2px;
  height: 22.56px;
  margin-left: 3.4px;
}

.iphone-pro-max .vector-13 {
  margin-top: 7.8px;
  width: 10.91px;
  height: 22.16px;
  margin-left: 5.1px;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 433px;
  left: 58px;
  width: 315px;
  height: 63px;
}

.iphone-pro-max .badminton-tournament {
  position: absolute;
  top: 452px;
  left: 83px;
  width: 261px;
  height: 18px;
}


PAGE 2

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="download" src="img/download-1.png" />
      <div class="rectangle"></div>
      <p class="badminton-tournament">
        Badminton Tournament Rules:<br />Matches will be best of 3 sets (21 points each).<br />Players must report 30
        minutes before match.<br />Rally scoring system will be followed.<br />Serve must be below waist level.<br />Proper
        sports dress &amp; non-marking shoes required.<br />5-minute grace time, else walkover.<br />Misconduct or
        cheating leads to disqualification.<br />Referee/organizer decision is final.
      </p>
    </div>
  </body>
</html>

CSS

.iphone-pro-max {
  overflow: hidden;
  background-image: url(./img/iphone-16-17-pro-max-1.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .download {
  position: absolute;
  top: 151px;
  left: 0;
  width: 440px;
  height: 88px;
  aspect-ratio: 5.01;
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 775px;
  left: -1px;
  width: 449px;
  height: 154px;
  background-color: #d9d9d9;
}

.iphone-pro-max .badminton-tournament {
  position: absolute;
  top: 280px;
  left: 7px;
  width: 426px;
  font-family: "Inria Sans-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 28px;
  letter-spacing: 0;
  line-height: normal;
}


PAGE 3
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="images" src="img/images-2-1.png" />
      <img class="download" src="img/download-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">Name</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-2">Gender</div>
      <div class="text-wrapper-3">Age</div>
      <div class="text-wrapper-4">Mobile no.</div>
      <div class="text-wrapper-5">College Name</div>
      <img class="img" src="img/rectangle-6.svg" />
      <div class="text-wrapper-6">Event Registration Form</div>
    </div>
  </body>
</html>

CSS

.iphone-pro-max {
  background-image: url(./img/iphone-16-17-pro-max-1.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .images {
  position: absolute;
  top: 27px;
  left: 0;
  width: 440px;
  height: 535px;
  aspect-ratio: 1.43;
  object-fit: cover;
}

.iphone-pro-max .download {
  position: absolute;
  top: 27px;
  left: 0;
  width: 440px;
  height: 92px;
  aspect-ratio: 5.01;
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 295px;
  left: 29px;
  width: 365px;
  height: 72px;
  background-color: #d9d9d9;
  border-radius: 15px;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 309px;
  left: 59px;
  opacity: 0.7;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 416px;
  left: 29px;
  width: 365px;
  height: 72px;
  background-color: #d9d9d9;
  border-radius: 15px;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 762px;
  left: 29px;
  width: 365px;
  height: 72px;
  background-color: #d9d9d9;
  border-radius: 15px;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 644px;
  left: 29px;
  width: 365px;
  height: 72px;
  background-color: #d9d9d9;
  border-radius: 15px;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 526px;
  left: 29px;
  width: 365px;
  height: 72px;
  background-color: #d9d9d9;
  border-radius: 15px;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 434px;
  left: 59px;
  opacity: 0.7;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 543px;
  left: 54px;
  opacity: 0.7;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 658px;
  left: 53px;
  opacity: 0.7;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 781px;
  left: 39px;
  opacity: 0.7;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .img {
  position: absolute;
  top: 195px;
  left: 12px;
  width: 415px;
  height: 66px;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 206px;
  left: 21px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}


PAGE 4

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="download" src="img/download-1.png" />
      <div class="text-wrapper">Thank You</div>
      <p class="div">
        Thank you for registering for the Badminton Tournament. We appreciate your interest and participation
      </p>
      <p class="p">
        Further details regarding match schedule and rules will be shared soon. Please stay updated and be prepared for
        the tournament.
      </p>
      <div class="rectangle"></div>
      <div class="text-wrapper-2">SAAGAR -25013937</div>
    </div>
  </body>
</html>

CSS

.iphone-pro-max {
  overflow: hidden;
  background-image: url(./img/iphone-16-17-pro-max-1.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .download {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 89px;
  aspect-ratio: 5.01;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 207px;
  left: 86px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #ffffff;
  font-size: 52px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 380px;
  left: 23px;
  width: 451px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .p {
  position: absolute;
  top: 582px;
  right: -48px;
  width: 446px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 883px;
  left: 0;
  width: 440px;
  height: 73px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 905px;
  left: 100px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

```

## OUTPUT:
![alt text](<Screenshot (43).png>) ![alt text](<Screenshot (42).png>) ![alt text](<Screenshot (41).png>) ![alt text](<Screenshot (40).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
