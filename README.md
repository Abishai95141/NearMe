# Ex04 Places Around Me
## Date: 28.03.2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map1.html

<html>
    <head>
        <title>Map</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Veppampattu</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>ABISHAI 212223240002</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#image-map">
            <img src="Screenshot 2024-01-26 194958.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="BSN Party Hall" title="BSN Party Hall" href="bsn.html" coords="1267,562,1411,625" shape="rect">
    <area target="" alt="Raja National School" title="Raja National School" href="raja.html" coords="78,833,108" shape="circle">
    <area target="" alt="Tata Steel Limited" title="Tata Steel Limited" href="tata.html" coords="1682,562,1845,610" shape="rect">
    <area target="" alt="Balaji Construction and Builders" title="Balaji Construction and Builders" href="balaji.html" coords="1240,840,1403,898" shape="rect">
    <area target="" alt="SRM Cool Point" title="SRM Cool Point" href="srm.html" coords="1769,949,48" shape="circle">
</map>
        </center>  
    </body>
</html>



balaji.html

<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="cyan"><b>Veppampattu</b></font>
        </h1>
        <h3 align="center">
            <font color="lime"></b>Balaji Construction and Builders</font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                Balaji Construction is a full service construction firm specializing in managing high image and technically difficult projects. We’ve been in business since 1997 and operate exclusively in “TAMILNADU”.’ time and money.We uses a variety of delivery methods to meet specific needs of clients including Construction Management, Project Management, Design-build and general contracting. No matter what the delivery method, We takes projects from concept to completion and saves our clients’ time and money.
            </font>
        </p>
    </body>
</html>

bsn.html

<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="cyan"><b>Veppampattu</b></font>
        </h1>
        <h3 align="center">
            <font color="lime"></b>BSN Party Hall</font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                BSN Party Hall, Veppampattu, Thiruvallur is a great venue to host your wedding and reception ceremonies. 
                It is located near the Sri Lakshmi Narasimha Temple which is a known place for the people living nearby. 
                It is also just 5 kilometers away from Veppampattu Railway Station. 
                It allows you to get your own caterer from outside to serve lip-smacking cuisines. 
            </font>
        </p>
    </body>
</html>

raja.html

<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="cyan"><b>Veppampattu</b></font>
        </h1>
        <h3 align="center">
            <font color="red"><b>Raja National School</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                Our School is committed to provide a friendly, safe and happy atmosphere, where, the needs of the student comes first. Our School, works with the parents together to help each child to unveil his or her unique potential. Just as a small drop of water, makes its contribution in the formation of a mighty ocean, our School helps our students to develop
                High self-esteem, Respect for individual,Learn to think for themselves,Benefits of working as a team,Out-of-the-box thinking,Make prudent judgements and
 
            </font>
        </p>
    </body>
</html>

srm.html

<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="cyan"><b>Veppampattu</b></font>
        </h1>
        <h3 align="center">
            <font color="lime"></b>SRM Cool Point</font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                There are limits to the value companies can generate by focusing purely on the price of the products and services they buy. When buyers and suppliers are willing and able to cooperate, they often find ways to unlock new sources of value that benefit them both.A McKinsey survey of more than 100 large organizations in multiple sectors revealed that companies that regularly collaborated with suppliers demonstrated higher growth, lower operating costs, and greater profitability than their industry peers[1].
            </font>
        </p>
    </body>
</html>

tata.html

<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="cyan"><b>Veppampattu</b></font>
        </h1>
        <h3 align="center">
            <font color="lime"></b>Tata Steel Limited</font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                In India, Tata Steel operates an end-to-end value chain that extends from mining to finished steel goods, catering to an array of market segments such as automotive, construction, general engineering etc. The Company sources most of the required raw materials from its captive mines in India, providing raw material security and the competitive advantage of being a low-cost steel producer. The Raw Material Division of Tata Steel supplies almost 100% of iron ore and nearly 21% of clean coal requirements for steel manufacturing facilities in India, while the rest is imported. The Company also operates manganese and chromite mines.
            </font>
        </p>
    </body>
</html>

```
## OUTPUT
![web1](https://github.com/Abishai95141/NearMe/assets/139335314/d6cc4625-d709-4c77-9944-7bda73cd3325)


![image](https://github.com/Abishai95141/NearMe/assets/139335314/627f6190-9ff3-44d9-aa1f-3904933da81d)


![image](https://github.com/Abishai95141/NearMe/assets/139335314/71f21e2d-63b7-4ccc-b2b9-c4960b609fe2)

![image](https://github.com/Abishai95141/NearMe/assets/139335314/e38924ba-bc17-48e2-a958-d3ed4ea89ce9)
![image](https://github.com/Abishai95141/NearMe/assets/139335314/c6a1c939-b8c8-4725-9ffe-2970b955c735)


![image](https://github.com/Abishai95141/NearMe/assets/139335314/9faead5c-3b6b-4a1e-822c-42ba065f1bd7)



## RESULT
The program for implementing image maps using HTML is executed successfully.
