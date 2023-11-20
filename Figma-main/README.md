# Ex09 Event Registration Web Application
## Date : 07-11-2023

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
```
/* Home Page */

position: relative;
width: 360px;
height: 640px;

background: linear-gradient(180deg, rgba(187, 191, 191, 0.8) 0%, rgba(187, 191, 191, 0.720833) 75.62%, rgba(187, 191, 191, 0) 99.98%, rgba(187, 191, 191, 0.720833) 99.99%);
filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));


/* SAVEETHA ENGINEERING COLLEGE */

position: absolute;
width: 321px;
height: 34px;
left: calc(50% - 321px/2 + 0.5px);
top: calc(50% - 34px/2 - 285px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #2B0C52;

mix-blend-mode: normal;


/* Affiliated to Anna University */

position: absolute;
width: 321px;
height: 34px;
left: calc(50% - 321px/2 + 0.5px);
top: calc(50% - 34px/2 - 66px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #2B3F0A;

mix-blend-mode: normal;


/* NIRF Ranked Autonomous Institiution */

position: absolute;
width: 218px;
height: 48px;
left: calc(50% - 218px/2);
top: calc(50% - 48px/2 + 5px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #2B3F0A;

mix-blend-mode: normal;


/* Line 1 */

position: absolute;
width: 360px;
height: 0px;
left: 0px;
top: 67px;

border: 4px solid #000000;


/* Saveetha Logo 1 */

box-sizing: border-box;

position: absolute;
width: 95px;
height: 87px;
left: calc(50% - 95px/2 + 0.5px);
top: calc(50% - 87px/2 - 174.5px);

background: url(Saveetha Logo.png);


/* Rectangle 1 */

position: absolute;
width: 148px;
height: 35px;
left: calc(50% - 148px/2);
top: calc(50% - 35px/2 + 122.5px);

background: #138B7C;


/* LOGIN */

position: absolute;
width: 125px;
height: 20px;
left: calc(50% - 125px/2 + 0.5px);
top: calc(50% - 20px/2 + 120px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #000000;



/* Login Page */

position: relative;
width: 360px;
height: 640px;

background: linear-gradient(180deg, rgba(187, 191, 191, 0.901) 73.02%, rgba(187, 191, 191, 0) 100%);


/* SAVEETHA ENGINEERING COLLEGE */

position: absolute;
width: 321px;
height: 34px;
left: calc(50% - 321px/2 + 0.5px);
top: calc(50% - 34px/2 - 285px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #2B0C52;

mix-blend-mode: normal;


/* Line 2 */

position: absolute;
width: 360px;
height: 0px;
left: 1px;
top: 68px;

border: 4px solid #000000;


/* Saveetha Logo 2 */

position: absolute;
width: 95px;
height: 87px;
left: calc(50% - 95px/2 - 0.5px);
top: calc(50% - 87px/2 - 173.5px);

background: url(Saveetha Logo.png);


/* Username */

position: absolute;
width: 123px;
height: 25px;
left: 14px;
top: 258px;

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #B412B8;



/* Password */

position: absolute;
width: 123px;
height: 25px;
left: 14px;
top: 318px;

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #B412B8;



/* Rectangle 2 */

position: absolute;
width: 187px;
height: 30px;
left: 154px;
top: 258px;

background: #4A9F9A;


/* Rectangle 3 */

position: absolute;
width: 187px;
height: 30px;
left: 154px;
top: 312px;

background: #4A9F9A;


/* Rectangle 3 */

position: absolute;
width: 148px;
height: 35px;
left: calc(50% - 148px/2 + 1px);
top: calc(50% - 35px/2 + 117.5px);

background: #D9D9D9;


/* Rectangle 4 */

position: absolute;
width: 148px;
height: 35px;
left: calc(50% - 148px/2 + 1px);
top: calc(50% - 35px/2 + 117.5px);

background: #138B7C;


/* LOGIN */

position: absolute;
width: 125px;
height: 20px;
left: calc(50% - 125px/2 + 1.5px);
top: calc(50% - 20px/2 + 115px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #000000;



/* SEC Page */

position: relative;
width: 360px;
height: 640px;

background: linear-gradient(180deg, rgba(187, 191, 191, 0.901) 78.75%, rgba(187, 191, 191, 0) 100%);


/* SAVEETHA ENGINEERING COLLEGE */

position: absolute;
width: 321px;
height: 34px;
left: calc(50% - 321px/2 - 0.5px);
top: calc(50% - 34px/2 - 285px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #2B0C52;

mix-blend-mode: normal;


/* Line 3 */

position: absolute;
width: 360px;
height: 0px;
left: calc(50% - 360px/2);
top: calc(50% - 0px/2 - 252px);

border: 4px solid #000000;


/* Saveetha Logo 3 */

position: absolute;
width: 95px;
height: 87px;
left: calc(50% - 95px/2 - 1.5px);
top: calc(50% - 87px/2 - 173.5px);

background: url(Saveetha Logo.png);


/* Rectangle 5 */

position: absolute;
width: 218px;
height: 52px;
left: calc(50% - 218px/2);
top: calc(50% - 52px/2 - 53px);

background: #4A9F9A;


/* DEPARTMENTS */

position: absolute;
width: 203px;
height: 24px;
left: calc(50% - 203px/2 - 1.5px);
top: calc(50% - 24px/2 - 53px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
/* identical to box height */
text-align: center;

color: #000000;



/* CSE */

position: absolute;
width: 127px;
height: 25px;
left: calc(50% - 127px/2 + 0.5px);
top: calc(50% - 25px/2 + 12.5px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #62260C;



/* IT */

position: absolute;
width: 68px;
height: 26px;
left: calc(50% - 68px/2);
top: calc(50% - 26px/2 + 55px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #62260C;



/* AI-DS */

position: absolute;
width: 198px;
height: 25px;
left: calc(50% - 198px/2);
top: calc(50% - 25px/2 + 96.5px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #62260C;



/* AI-ML */

position: absolute;
width: 212px;
height: 27px;
left: calc(50% - 212px/2);
top: calc(50% - 27px/2 + 134.5px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #62260C;



/* IOT */

position: absolute;
width: 119px;
height: 25px;
left: calc(50% - 119px/2 + 0.5px);
top: calc(50% - 25px/2 + 169.5px);

font-family: 'Inria Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #62260C;

```

## OUTPUT:
![image](https://github.com/Anbuselvan04/Figma/assets/119410896/f3ad2643-19d8-4977-a84f-9df7a534e6af)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
